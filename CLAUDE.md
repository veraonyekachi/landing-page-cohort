# Landing Page Cohort — Project Brief

## What This Project Is
Vera Onyekachi (AE at Clay.com) is building personalized landing pages for 5 prospects who requested a Clay demo. Each page is a standalone HTML file that opens in a browser — no hosting, no installation needed. The goal is to close deals by sending each prospect a custom page that speaks directly to their role, company context, and pain points.

## Prospects (from CSV)
| Name | Title | Company | Email | LinkedIn |
|---|---|---|---|---|
| Sarah Mitchell | VP of Revenue Operations | Retool | sarah.mitchell@retool.com | linkedin.com/in/sarahmitchell |
| Marcus Chen | Head of Growth | Linear | marcus.chen@linear.app | linkedin.com/in/marcuschen |
| Emily Rodriguez | Director of Sales Development | Loom | emily.rodriguez@loom.com | linkedin.com/in/emilyrodriguez |
| James Okonkwo | GTM Engineer | Webflow | james.okonkwo@webflow.com | linkedin.com/in/jamesokonkwo |
| Rachel Goldstein | VP of Sales | Airtable | rachel.goldstein@airtable.com | linkedin.com/in/rachelgoldstein |

## Source Files
- `landing-page-prospects - landing-page-prospects.csv` — prospect data
- `clay_icp.docx` — Clay's Ideal Customer Profile (pain points, decision makers, anti-ICP)
- `clay_value_prop.docx` — Clay's value proposition, differentiators, stats, use cases

## Build Decisions (agreed with Vera)
- **Format:** Self-contained HTML files, open in browser locally (double-click to open)
- **Personalization depth:** Deep — company-specific stats, role-specific pain points, recent news
- **Design:** Dark theme matching Clay's brand (teal #00D4B8) + each prospect's company brand colors
- **Hero layout:** Two-column — personalized headline left, floating "Clay enrichment card" right (showing real company data)
- **CTA:** Calendly booking link, personalized per prospect using pattern: `https://calendly.com/vera-onyekachi/[first-name]-[last-name]`
- **Sections:** Nav (dual logos) → Hero → Stats strip → Pain points (3 cards) → Solution (3 cards + quote) → Social proof → CTA → Footer
- **No external dependencies** except Google Fonts (requires internet to render fonts, but works offline with fallbacks)

## Company Research Summary

### Retool (Sarah Mitchell — VP RevOps)
- $138.6M ARR, 466 employees (↑ from 340), $3.2B valuation
- 68 quota-carrying sales reps
- Pain: Enrichment coverage ~55%, fragmented stack, reps spending ~40% of day on research
- Clay angle: Waterfall enrichment, CRM consolidation, Claygent AI research for 68-rep team
- Brand colors: Orange `#F05C28`, dark navy

### Linear (Marcus Chen — Head of Growth)
- $100M ARR, ~178–234 employees, $1.3B valuation
- Closed $82M Series C in June 2025 (Accel-led)
- 18,000+ paying customers (OpenAI, Perplexity, Cursor, Ramp, Vercel)
- GTM model: PLG + emerging sales (only 20% of team in sales)
- Pain: PLG-to-sales handoff leaky, no outbound infrastructure, growth experiments blocked by data gaps
- Clay angle: Intent-based outbound, product signal enrichment, fast GTM experimentation
- Brand colors: Purple `#5E6AD2`, very dark minimal aesthetic

### Loom (Emily Rodriguez — Director of Sales Development)
- Acquired by Atlassian for $975M (completed Nov 2023)
- 25M+ users, 200K+ customers
- Now operating as part of Atlassian's enterprise ecosystem
- Pain: SDRs spending 3–4 hrs/day on research, personalization at scale hard, enrichment gaps mid-sequence
- Clay angle: Claygent automates SDR research, waterfall enrichment, personalization at scale
- Brand colors: Violet `#625DF5`, Atlassian blue `#0052CC`

### Webflow (James Okonkwo — GTM Engineer)
- $212.5M ARR, ~1,600 employees, $4B valuation, $336M raised
- Only 7 quota-carrying sales reps (very lean)
- Already GTM-engineering forward — Webflow is cited as one of the early adopters of GTM engineering (a term Clay helped coin)
- Pain: Connecting 8+ GTM tools requires custom code, enrichment dead-ends break workflows, AI research outputs are unstructured
- Clay angle: This is THE builder persona — 150+ native integrations, spreadsheet UX, Claygent for structured AI research
- Brand colors: Blue `#4353FF`, dark aesthetic

### Airtable (Rachel Goldstein — VP Sales)
- $478M ARR, ~947 employees, $11.7B valuation, $1.4B raised
- 134 quota-carrying sales reps
- IPO on horizon (cash flow positive late 2024, CFO signaled possible IPO)
- Acquired DeepSky AI in October 2025, launched "Superagent" product
- Pain: CRM data degrades at 134-rep scale, enrichment can't keep up, personalization impossible without more headcount
- Clay angle: Automated CRM enrichment, waterfall at enterprise scale, AI personalization without headcount growth
- Brand colors: Yellow `#FCB400`, blue `#2D7FF9`

## Files Built So Far
| File | Status |
|---|---|
| `sarah-mitchell-retool.html` | ✅ Complete |
| `marcus-chen-linear.html` | ✅ Complete |
| `emily-rodriguez-loom.html` | ⏳ Not started |
| `james-okonkwo-webflow.html` | ⏳ Not started |
| `rachel-goldstein-airtable.html` | ⏳ Not started |

## What Remains
1. Build `emily-rodriguez-loom.html` (Loom/Atlassian — Director of Sales Dev)
2. Build `james-okonkwo-webflow.html` (Webflow — GTM Engineer)
3. Build `rachel-goldstein-airtable.html` (Airtable — VP Sales)
4. Get Vera's review on Sarah's page (was in progress when session ended — she asked to see it first)
5. Apply any design/content feedback from review to all pages
6. Replace placeholder Calendly URLs with Vera's real Calendly links when available

## Vera's Preferences & Notes
- Non-technical user — explain things in plain terms
- Wants creativity in design, not just a template
- Pages must be 100% readable and well-structured
- Dual branding: Clay brand + prospect's company brand on every page
- Mindful of Claude credit usage — batch work efficiently
- Calendly links follow pattern: `https://calendly.com/vera-onyekachi/[firstname]-[lastname]`
- Vera's email: veraonyekachi31@gmail.com
