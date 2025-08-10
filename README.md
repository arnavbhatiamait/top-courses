# Top Courses (React + API)

A simple, responsive courses explorer that fetches course data via an API and lets users browse and filter popular courses across categories with a clean, card-based UI.

- Live site: https://arnavbhatiamait.github.io/top-courses/

## Features
- Browse curated “top courses” pulled dynamically from an API.
- Category filters to switch between domains (e.g., Web, Data, DevOps).
- Clean, mobile-friendly UI with course cards.

## Tech Stack
- React (component-based UI)
- JavaScript (fetching/parsing API responses)
- HTML/CSS for layout and styling

## Getting Started

1) Clone and install
- git clone https://github.com/arnavbhatiamait/top-courses.git
- cd top-courses
- npm install

2) Configure data source
- If the project fetches from a public JSON endpoint or local JSON, confirm the API/base URL in the code and adjust if needed.

3) Run locally
- npm start
- Open http://localhost:3000

4) Build
- npm run build

## Usage
- Open the live site and pick a category to see top courses for that domain.
- Scroll through cards for title, brief details, and quick at-a-glance info.
- Switch categories to load a different set of courses.

## Project Structure
- src/components — Reusable UI components (e.g., filters, course cards)
- src/data or API service — Fetching/parsing course data
- public/ — Static assets

## Improvements Roadmap
- Search box for course titles/keywords
- Persist selected category in URL or localStorage
- Loading and error states for network failures
- Pagination or infinite scroll for long lists
- Tag filters (difficulty, provider) for finer control

## License
- Add or update a LICENSE file as appropriate.
