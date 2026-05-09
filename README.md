# ReleaseSpark

> Turn GitHub commits into clean, organized changelogs instantly.

**Live:** https://releasespark.vercel.app

## Features

- Zero config — paste a GitHub repo URL and go
- No login required for public repos
- Parses [Conventional Commits](https://www.conventionalcommits.org/) spec automatically
- Groups by type: Features, Bug Fixes, Docs, Breaking Changes, and more
- Export as Markdown or copy to clipboard
- Mobile responsive, dark theme, fast

## How it works

1. Paste any public GitHub repo URL
2. Choose a branch, tag, or commit SHA range (optional)
3. Get a formatted changelog grouped by commit type

## Tech Stack

- Vanilla HTML/CSS/JS (no build step)
- GitHub REST API (public, unauthenticated for public repos)
- Tailwind CSS (CDN)
- Deployed on Vercel

## Development

Just open `index.html` — no build step needed.

## License

MIT
