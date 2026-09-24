# Align Software Consulting — alignsoft.net

Static marketing site (plain HTML/CSS/JS, no build step).

## Positioning
AI-first consultancy:
1. **AI services** (primary): assessments, document intelligence, knowledge assistants, agents, AI in existing apps, guardrails/training
2. **Automation**: integrations, pipelines, workflow automation
3. **Legacy application support**: maintenance retainers for Access/VBA, VB.NET, C#, WinForms/WPF, SQL Server

## Files
- `index.html`: all content, SEO meta, JSON-LD
- `styles.css`: design tokens at the top (`:root`)
- `script.js`: mobile menu and footer year

## Deploy
Hosted on a Cloudflare Worker (`asc`) with static assets, built from this repo.
Pushing to `main` deploys the site. The Worker is attached to `alignsoft.net`
as a custom domain, and `www` is a proxied CNAME to `alignsoft.net`.

The public contact email is hello@alignsoft.net.
