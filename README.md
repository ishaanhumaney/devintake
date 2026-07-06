# DevIntake

A lightweight, accessible, and ready-to-deploy frontend intake form built specifically for agencies and teams onboarding freelance developers or contract engineers.

This interface tackles the classic data-gathering phase cleanly. It skips heavy frameworks and relies on pure, semantic markup to maximize performance and maintain flexibility.

## Key Features
* **Semantic Form Fields:** Hand-crafted input layouts tracking real developer metrics like availability models, tech stacks, and project preferences.
* **Built-in Client-Side Validation:** Utilizes native HTML5 validation constraints alongside styled error wrappers.
* **Responsive Architecture:** Scalable styling optimized for mobile screens, tablets, and wide browser viewports.
* **Zero Dependencies:** Pure vanilla HTML and CSS, eliminating maintenance overhead and dependency vulnerabilities.

## Tech Stack Breakdown
* **Markup:** HTML5 (Semantic elements)
* **Styling:** CSS3 (Flexbox/Grid structure layout)
* **CI Automation:** GitHub Actions (HTML validation checks)

## Prerequisites & Web-Based Quick Start

Since this is a vanilla frontend project, you don't need compilation tools, Node.js, or local setup packages.

### Option A: Run in the Browser (GitHub Codespaces)
1. At the top right of this repository page, click the green **Code** button.
2. Select the **Codespaces** tab, then click **Create codespace on main**.
3. Once the environment spins up, use any simple preview extension or open `index.html` directly to interact with the layout.

### Option B: Local Setup
If you want to view it locally, just clone the repo and open the file:
```bash```
git clone [https://github.com/YOUR-USERNAME/devintake.git](https://github.com/YOUR-USERNAME/devintake.git)
cd devintake
# Open index.html in any desktop browser

## Project Structure

devintake/
├── .github/

│   └── workflows/

│       └── ci.yml      # Automated HTML5 syntax checking

├── .gitignore          # Basic environment filter

├── index.html          # Core structure and semantic intake layout

├── README.md           # Documentation

└── style.css           # Grid systems and interface styling

## Roadmap
[ ] Implement full stylesheet matching standard component UI frameworks.

[ ] Add client-side validation logic using vanilla JavaScript.

[ ] Include dark mode support via CSS variables.

[ ] Build target handlers for Formspree, Netlify Forms, or Web3Forms integrations.
