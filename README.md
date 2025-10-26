# publicprofile

This is my personal website built with Jekyll and the Minima theme.

## Features

- **Home Page**: Welcome message and navigation overview
- **Bio**: Background, education, professional experience, skills, and personal interests
- **Research Interests**: Current research areas, publications, collaborations, and research philosophy
- **Portfolio**: Featured projects, professional contributions, awards, and skills showcase
- **Upcoming Events**: Scheduled events, past events, and speaking availability

## Local Development

### Prerequisites

- Ruby (3.0 or higher)
- Bundler

### Installation

1. Install dependencies:
   ```bash
   bundle install
   ```

2. Start the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```

3. Open your browser and visit: `http://localhost:4000`

### Building for Production

To build the static site:
```bash
bundle exec jekyll build
```

The generated site will be in the `_site` directory.

## Customization

- **Site Title & Description**: Edit `_config.yml`
- **Content**: Edit the markdown files (`index.md`, `bio.md`, `research.md`, `portfolio.md`, `events.md`)
- **Contact Email**: Update the email in `_config.yml`

## Theme

This site uses the [Minima](https://github.com/jekyll/minima) theme, which provides a clean, responsive design.

