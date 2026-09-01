# Prospect Automation Engine (PAE) Landing Page

## Overview
Premium landing page for the Prospect Automation Engine skill powered by SalesGency. Built with the tastyskill.dev design framework featuring OLED dark theme, cobalt blue accents (#2563EB), split-screen hero layout, and animated grid backgrounds.

## Features

### Design System
- **OLED Dark Theme**: Pure black (#000000) background for premium aesthetics
- **Cobalt Accent Color**: #2563EB primary, with light (#3b82f6) and dark (#1d4ed8) variants
- **Animated Grid Background**: Continuous movement creating depth and motion
- **Split-Screen Hero**: Left content, right workflow visualization
- **Responsive Layout**: Mobile-first, tablet, and desktop optimized

### Content Sections

1. **Hero Section**
   - Split-screen layout with 6-step workflow visualization
   - Key stats: 3.4× reply rate, 20+ hours saved, 30 days to live
   - Dual CTAs for engagement and architecture exploration

2. **6-Step Workflow** (`#workflow`)
   - Lead Intake & NLP Search
   - Get Companies & Contacts
   - Deep Web & Account Research
   - Pain Point Hypothesis
   - Custom AI Copywriting (PAS)
   - CRM Sync & Sequencer Dispatch
   - Interactive hover states with cobalt accents

3. **9-Node n8n Pipeline** (`#pipeline`)
   - Visual flow diagram of the automation architecture
   - Schedule Trigger → Data Normalizer → Deduplication Query
   - Data Tool Adapter → AI Research & PAS Copy → Approval Switch
   - CRM Contact Creation → Sequence Enrollment → Review Alert

4. **Value Propositions** (`#value`)
   - Live in 30 Days
   - You Own the Architecture
   - Built for Frontline Reps
   - 3.4× Higher Reply Rate
   - 20+ Hours Saved Per Rep/Week
   - CRM Shield & Data Quality

5. **Architecture** (`#architecture`)
   - Four-layer stack visualization:
     - Layer 1: Ingestion Layer
     - Layer 2: Data Enrichment
     - Layer 3: AI Reasoning Core (Claude 3.5 Sonnet)
     - Layer 4: CRM Shield & Sequencer

6. **Tech Stack** (`#tech`)
   - n8n Workflows
   - Clay (enrichment)
   - ZoomInfo (firmographic data)
   - Apollo (email verification)
   - Claude 3.5 Sonnet (AI reasoning)
   - HubSpot/Salesforce (CRM)
   - Slack (alerts)

7. **Positioning** (`#positioning`)
   - For Sales Leaders: Scale outbound without hiring
   - For AI Engineers: Clone & white-label the skill
   - For RevOps Teams: Full observability
   - For Founders: Revenue-generating AI skill ($15K–$50K per implementation)

8. **CTA Section**
   - Final conversion point with dual CTAs
   - Links to SalesGency website and GitHub repo

## Technical Details

### Single-File Architecture
- **Zero Dependencies**: All CSS and JavaScript inline
- **Production-Ready**: No build step required
- **40KB Total Size**: Optimized for fast loading
- **1,171 Lines**: Fully commented and maintainable

### Animations
- Grid background continuous animation (20s loop)
- Scroll-triggered fade-in animations
- Hover effects on cards and buttons
- Smooth anchor link scrolling

### Responsive Breakpoints
- Desktop: 1024px+ (two-column layouts)
- Tablet: 768px–1024px (single column)
- Mobile: <768px (stacked layouts)

### Color Palette
```css
--cobalt: #2563EB          /* Primary brand color */
--cobalt-dark: #1d4ed8     /* Hover states */
--cobalt-light: #3b82f6    /* Highlights */
--oled-black: #000000      /* Background */
--dark-900: #0a0a0a        /* Card backgrounds */
--dark-800: #111111        /* Elevated surfaces */
--dark-700: #1a1a1a        /* Borders */
--dark-600: #222222        /* Hover states */
--text-primary: #ffffff    /* Headings */
--text-secondary: #a0a0a0  /* Body copy */
--text-tertiary: #707070   /* Labels */
```

## Usage

### View Locally
```bash
open /tmp/pae-landing/index.html
```

### Deploy
Upload `index.html` to any static hosting service:
- GitHub Pages
- Vercel
- Netlify
- AWS S3 + CloudFront
- Custom domain

### Customize
All styles are inline CSS variables in the `<style>` block. Update:
- `:root` variables for colors
- Section content in HTML
- Grid layouts in CSS Grid sections

## Links
- **SalesGency Website**: https://www.salesgency.com
- **Services Page**: https://www.salesgency.com/services.html
- **GitHub Repo**: https://github.com/diamitani/salesgency-pae-proposal

## Credits
- **Design Framework**: tastyskill.dev methodology
- **Content**: SalesGency PAE proposal documentation
- **Built**: August 2026 for AI agent skill positioning

---

**Status**: Production-ready, single-file HTML, zero dependencies
