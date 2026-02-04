# OneLoop Labs — Website

Enterprise SAP Integrations, Built to Ship.

## Stack

- **Frontend:** Pure HTML/CSS/JS (no framework)
- **Hosting:** Azure Static Web Apps (Free tier)
- **CI/CD:** GitHub Actions → auto-deploy on push to `main`
- **Design:** Dark theme, teal accent (#0ea5a0), Inter + JetBrains Mono

## Local Development

Just open `index.html` in a browser, or use any static file server:

```bash
npx serve .
```

## Deployment

Pushes to `main` auto-deploy via GitHub Actions to Azure Static Web Apps.

**Setup required:**
1. Create an Azure Static Web App resource
2. Add the deployment token as a GitHub secret: `AZURE_STATIC_WEB_APPS_API_TOKEN`
3. (Optional) Configure custom domain in Azure portal

## Project Structure

```
├── index.html                     # Home page
├── css/styles.css                 # Design system + all styles
├── js/main.js                     # Mobile nav, smooth scroll, scroll animations
├── assets/images/                 # Product screenshots, icons
├── assets/logos/                  # Partner badges, company logo
├── staticwebapp.config.json       # Azure SWA security headers
├── .github/workflows/             # CI/CD pipeline
└── README.md
```

## Phases

- **Phase 1** ✅ Home page + Azure deploy
- **Phase 2** — Product page + contact flow
- **Phase 3** — About page + SEO + analytics
- **Phase 4** — Blog + content engine

---

© 2026 OneLoop Labs. All rights reserved.
