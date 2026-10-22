# 🚀 1-Click Deployment Guide — Hamdi Soudani B2B Sprints & Subcontracting Portfolio

This standalone, high-converting 1-page B2B engineering portfolio is located at:
`c:\Users\siham\OneDrive\Desktop\opportunity_hunting\portfolio\index.html`

It is **100% self-contained** (pure semantic HTML5, modern CSS variables with Linear/Vercel/Raycast aesthetic, and vanilla JavaScript). It requires **zero build steps**, no `node_modules`, and no complex bundlers.

---

## ⚡ Instant Bilingual Switcher Mechanics

The portfolio features an active URL query parameter parser:
- **French Version for Francophone Agencies / ESNs:**  
  `https://your-domain.vercel.app/?lang=fr`  
  *(Automatically switches all badges, packages, technical terms, and legal Article 259-1 CGI text to French).*
- **English Version for Global AI Startups & European Founders:**  
  `https://your-domain.vercel.app/?lang=en`  
  *(Defaults to English with USD/EUR dual pricing, agentic sprint breakdown, and global compliance).*

---

## 🌐 30-Second Production Deployment Options

### Option 1: Vercel (Recommended — Fastest 1-Command Deploy)

1. Open PowerShell or Terminal in the `portfolio` directory:
   ```powershell
   cd c:\Users\siham\OneDrive\Desktop\opportunity_hunting\portfolio
   ```

2. Run Vercel CLI (zero configuration needed):
   ```bash
   npx vercel --prod
   ```
3. Follow the 2-step prompt (select default scope and link to project). You get an instant SSL-secured public URL (e.g. `https://hamdi-soudani-sprints.vercel.app`).

---

### Option 2: Cloudflare Pages (Free & Ultra-Fast Global CDN)

1. In PowerShell:
   ```powershell
   cd c:\Users\siham\OneDrive\Desktop\opportunity_hunting\portfolio
   npx wrangler pages deploy . --project-name=hamdi-soudani-portfolio
   ```
2. Your portfolio is deployed globally in under 20 seconds.

---

### Option 3: Netlify Drop / CLI

1. In PowerShell:
   ```powershell
   cd c:\Users\siham\OneDrive\Desktop\opportunity_hunting\portfolio
   npx netlify deploy --prod --dir=.
   ```
2. Or drag and drop the `portfolio` folder directly into [app.netlify.com/drop](https://app.netlify.com/drop).

---

### Option 4: GitHub Pages (Live in Production! 🚀)

Your portfolio is already deployed and live on GitHub Pages:
- **Live URL (Default English):** [https://hamdisoudani.github.io/b2b-engineering-menu/](https://hamdisoudani.github.io/b2b-engineering-menu/)
- **Live URL (French for ESNs / Agencies):** [https://hamdisoudani.github.io/b2b-engineering-menu/?lang=fr](https://hamdisoudani.github.io/b2b-engineering-menu/?lang=fr)
- **Repository:** [https://github.com/hamdisoudani/b2b-engineering-menu](https://github.com/hamdisoudani/b2b-engineering-menu)

---

## 💻 Local Testing & Preview

To preview the portfolio locally with zero dependencies:

### Via Python:
```powershell
cd c:\Users\siham\OneDrive\Desktop\opportunity_hunting\portfolio
python -m http.server 8080
```
Then visit in your browser:
- French: [http://localhost:8080/?lang=fr](http://localhost:8080/?lang=fr)
- English: [http://localhost:8080/?lang=en](http://localhost:8080/?lang=en)

### Via Direct File Launch:
You can also double-click `index.html` or run:
```powershell
start c:\Users\siham\OneDrive\Desktop\opportunity_hunting\portfolio\index.html
```

---

## 🎯 High-Yield Outreach Usage Cheat Sheet

When contacting CTOs, Founders, or Agency Leads:

### 1. Francophone Web Agencies & AI Studios (Batch 1 - France)
> **Pitch Link:** `https://your-portfolio.vercel.app/?lang=fr`  
> **Offer:** *Renfort Technique & Sous-Traitance Agence (220€ à 250€ HT/jour)*  
> **Key Hook:** 0% TVA (Art. 259-1 CGI autoliquidation), pas de charges patronales, marge agence >65% sur refacturation à 750€+/j, intégration Slack/Git en 24h.

### 2. Global AI Startups & Tech Studios (Batch 2 & 3 - EU/US)
> **Pitch Link:** `https://your-portfolio.vercel.app/?lang=en`  
> **Offer:** *10-Day Production Agentic / GraphRAG Sprint ($1,800 Fixed Scope)*  
> **Key Hook:** Stateful LangGraph architecture, CopilotKit canvas UI, zero-hallucination Neo4j GraphRAG, direct GitHub PR handover on Day 10.
