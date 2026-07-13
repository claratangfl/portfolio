# Data Analytics Portfolio

Four case studies with interactive Chart.js visualisations, hosted on GitHub Pages.

## Case Studies

### Referral Quality Analysis
**Context:** Neobank referral program, 6,393 referrals across two bonus tiers.

Investigated whether doubling the referral bonus improved customer quality. Found that inviter behaviour and card activation predicted retention far more than bonus size. Modelled policy changes that cut cost per active customer by 33%.

### Candidate Segmentation Framework
**Context:** Major job platform, 283 candidates across a marketing funnel.

Designed a lifecycle-based segmentation framework with six stages, mapped each to specific marketing actions, and validated the approach against real conversion data. Conversion ranged from 12% to 16.4% across segments.

### MQL-to-SAL Pipeline Diagnosis
**Context:** HR SaaS platform, 33,076 leads following a 3,270% volume spike.

Diagnosed why MQL-to-SAL conversion was falling despite record lead volumes. Identified capacity constraints, data quality gaps, and qualification issues. Delivered a 30/60/90 day action plan.

### Subscription Growth Modelling
**Context:** D2C pet food company, 10,000 active subscriptions.

Assessed data quality across six source tables, designed a medallion architecture for reliable metrics, and calculated 11% QoQ growth. Found that product fit drove 48% of voluntary churn.

## Tech

- Static HTML + CSS
- Chart.js v4.4.4 for interactive visualisations
- Responsive, light/dark theme via `prefers-color-scheme`

## Local Development

```bash
python3 -m http.server 8090
```

Then open `http://localhost:8090`.
