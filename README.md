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
Hosted on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).
Pushing to `main` publishes the site. The `CNAME` file sets the custom domain
(`www.alignsoft.net`); don't delete it.

DNS is at Cloudflare:
- `alignsoft.net`: A → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- `www`: CNAME → jbylsma1.github.io

The public contact email is hello@alignsoft.net.
