# Space Robotics Workshop @ ICRA 2026

This repository hosts the static website for the Space Robotics Workshop at ICRA 2026.

## Structure

- `index.html`: Main page with all workshop sections
- `styles.css`: Styles for the site

## Edit Content

Open `index.html` and update:
- Title, dates, and location in the hero section
- Six invited speakers and affiliations in the `Invited Speakers` section
- Six organizers and affiliations in the `Organizers` section
- Schedule table rows
- Call for Papers topics and text
- Submission details (portal link, formatting, deadlines)
- Timeline dates
- Contact email and venue details

## Local Preview

You can open `index.html` directly in a browser. For a simple local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy (GitHub Pages)

1. Commit and push changes to `main`.
2. In your repository settings, go to Pages and set:
   - Source: `Deploy from a branch`
   - Branch: `main` → `/ (root)`
3. The site will be available at the repository's Pages URL.

## Credits

Styled after the RSS 2025 Dexterous Manipulation Workshop site: `https://dex-manipulation.github.io/rss2025/`.
