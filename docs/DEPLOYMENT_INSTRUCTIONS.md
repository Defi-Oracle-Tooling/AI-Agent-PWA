
# Deployment Instructions: AI Agent PWA

## Prerequisites
- Node.js v18+
- pnpm installed
- Azure CLI + GitHub CLI
- Azure Subscription with Function + Static Web App support

## Setup

```bash
pnpm install
pnpm run build
```

## Dev Server

```bash
pnpm run dev
```

## Deploy to Azure

1. Create Static Web App + Azure Functions
2. Push code to GitHub
3. Configure deployment token
4. Enable GitHub Actions

## Notes

- API keys must be entered in the settings panel
- Optional: add .env.local for override
- All offline features pre-enabled
