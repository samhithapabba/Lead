# LeadFlow – Lead Management System (CRM)

A responsive, frontend-only CRM application built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Simulated login and registration (demo credentials: `demo@leadflow.com` / `demo123`)
- Dashboard with lead statistics and pipeline/source charts
- Create, view, edit and delete leads
- Search, filter and sort the lead directory
- Kanban-style pipeline with five lead statuses
- Follow-up scheduler with completion tracking
- Convert leads into customers
- Reports, source analysis and activity timeline
- Export leads to CSV
- Dark mode
- Responsive sidebar and mobile layout
- Data persistence using browser `localStorage`

## Run locally
1. Download or clone this repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. Sign in with `demo@leadflow.com` and `demo123`.

No database, backend or build tools are required.

## Project files
- `index.html` – page structure and forms
- `style.css` – styling and responsive design
- `script.js` – application logic and local data management

## Important note
Authentication is simulated and data is stored in the current browser only. This is a learning project, not a production CRM. Do not enter real or sensitive customer information.

## Deployment
For GitHub Pages: push these files to a public GitHub repository, then open **Settings → Pages**, choose the `main` branch and `/ (root)` folder, and save.
