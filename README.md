# Autopilot Digital Agency Stack

## Includes:
- n8n (automation)
- EspoCRM (CRM)
- Mixpost (social scheduling)
- PostHog (analytics)
- Formbricks (form builder)
- Caddy (reverse proxy + HTTPS)
- Portainer (Docker UI)

## Quick Start
1. Clone the repo
2. Replace subdomains in `Caddyfile` with your own
3. Add DNS records pointing subdomains to your server IP
4. Run:
   ```bash
   docker compose up -d
   ```
5. Deploy `public/index.html` to Netlify

## Prebuilt n8n Flows:
- Lead scraper → CRM
- Cold email + WhatsApp
- Demo booking follow-up

## 🚀 One-Click Deploy

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)
