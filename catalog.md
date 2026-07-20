# nolimitz-catalog

The authoritative service catalog for **Nolimitz** — what we offer, what we build, and how we price it. This is the single source of truth for our chatbot, marketing agents, and anyone on the team creating client-facing materials.

> **Texas-built. Nationally deployed.**  
> Enterprise AI, Web & Cloud — Driven, Not Just Used.

---

## Structure

```
catalog.json          ← source of truth (machine-readable)
catalog.md            ← human-readable version (synced from JSON)
service-catalog.md    ← detailed reference (human-first, for deep work)
```

**`catalog.json`** is the canonical source. Update it and regenerate everything else.

---

## Four Core Practices

| Service | URL | Description |
|---|---|---|
| **AI Agents** | `/services/ai-agents` | Edge-native agents, multi-agent architecture, AI coaching |
| **App Development** | `/services/app-development` | Prototype → production, website modernization, custom apps |
| **Cloud & Infrastructure** | `/services/cloud-infrastructure` | AWS, Cloudflare, serverless, managed hosting |
| **AI Strategy** | `/services/ai-strategy` | Consulting, custom ML, document processing, predictive analytics |

---

## Web Application Pricing

| Tier | Price | What's Included |
|---|---|---|
| **Essential** | $850–$1,100 | 3-5 page static site, responsive, contact form, basic SEO |
| **Content** | $1,500–$1,800 | Everything in Essential + CMS, blog, dynamic content |
| **Web App** | $4,000+ | Custom functionality, API integrations, dynamic sections, member systems |

See `[pricing-web-apps.md](pricing-web-apps.md)` for full scope details and add-ons.

---

## Add-Ons

| Add-on | Price |
|---|---|
| **Chatbot / AI Contact Assistant** | $500 setup + $100/year |
| Performance hardening | $150–$300 |
| Advanced SEO | $300–$400 |
| Analytics setup | $100 |
| Content writing | $250–$500 |
| Domain setup / DNS | $75 |

---

## Hosting & Maintenance

| Plan | Monthly | Includes |
|---|---|---|
| **Basic** | $50 | Hosting, SSL, monitoring, backups, security patching |
| **Performance** | $75 | Basic + analytics, error tracking, CDN, Core Web Vitals |
| **Managed** | $150 | Performance + 2hrs/mo content updates, status page, priority support |

---

## Products We Own

- **WaveMaker Podcast Studio** — AI-powered production, editing, distribution ([wavemaker.bigripple.ai](https://wavemaker.bigripple.ai))
- **BigRipple AI Marketing Platform** — AI agents for campaigns, outreach at scale (coming soon)
- **Our Community Spot** — Modern HOA management platform
- **Agentic Software Engineering Team** — Autonomous agents that plan, code, test, ship end-to-end
- **Claude Certified Architect Study Cast** — Free podcast on Spotify, built with WaveMaker

---

## What We Do NOT Do

- Generic strategy platitudes — only actionable engineering
- Vaporware — no proof-of-concept-only engagements
- Vendor lock-in — model-agnostic, infrastructure-agnostic
- Bloated enterprise contracts — we scale with your reality

---

## How to Use

### For the Chatbot

Fetch the JSON directly from GitHub:

```
GET https://raw.githubusercontent.com/nolimitz/nolimitz-catalog/main/catalog.json
```

The chatbot loads this on startup and indexes it for service/pricing lookups. No API needed — GitHub raw serves the file.

### For Marketing Agents

- Edit `catalog.json` for all service/pricing updates
- Reference `service-catalog.md` for deep-dive service details
- Use the comparison table and add-on lists when writing content
- Never promise anything that isn't in the catalog

### For the Team

All client-facing materials (proposals, content, ads, outreach) should align with this catalog. If it's not here, we don't sell it.

---

*Updated automatically from catalog.json. Last sync: 2026-07-20*
