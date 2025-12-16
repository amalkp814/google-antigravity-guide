# Google Antigravity: The Safe Coding Handbook

A responsive, single-page infographic guide designed to help developers navigate Google Antigravity, the agent-first IDE. This dashboard visualizes safety protocols, workflows, and best practices for managing autonomous AI coding agents.

Live Demo

> [google-antigravity-guide](https://amalkp814.github.io/google-antigravity-guide/)

View the Live Site

✨ Features

- **Interactive Visualizations:**
	- **Safety Chart:** Compares risk levels of different terminal modes (Turbo vs. Auto vs. Off).
	- **Consistency Radar:** Visualizes the trade-offs between "Fast Mode" and "Planning Mode".
	- **Workflow Timeline:** A CSS-only vertical timeline showing the "Follow a Plan" trajectory.

- **AI Integration (Gemini):**
	- **Risk Analyzer:** Evaluates terminal commands and recommends safety settings.
	- **Agent Planner:** Generates architectural task lists for projects.

✨ Tech Stack

- Single-file `index.html` (HTML5)
- Tailwind CSS (via CDN) for responsive styling
- Chart.js (via CDN) for data visualization
- Google Gemini API (optional; via JS fetch)

🛠️ Usage

1. Clone or download this repository.
2. Open `index.html` in any modern web browser.
3. To use the AI features, enter your Gemini API Key in the input field at the bottom of the page.

Note: This repository does not include a preconfigured API key. You must sign up with the provider and create an API key yourself (signup may be required). For a quick test:

- Visit https://aistudio.google.com or your cloud provider's console.
- Create or retrieve a Gemini (or compatible) API key.
- Paste the key into the `Gemini API Key` field on the site and then run the AI tools.

📦 Deployment

This project is designed for GitHub Pages.

1. Go to your repository Settings > Pages.
2. Select the `main` branch as the source.
3. Save, and your site will be live.

📄 License

MIT License