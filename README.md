# Nuvei: Intelligent Account Routing & Enrichment

> Interactive 16-slide presentation showcasing a complete automation workflow design for sales operations optimization.

## 🎯 Project Overview

This presentation demonstrates a comprehensive solution to a **sales automation design challenge** posed by Nuvei. The task required designing how to build an intelligent account routing and enrichment process that:

1. **Triggers & Logic** — Automatic detection and deduplication of new accounts
2. **Enrichment** — Multi-source data enrichment via Clay APIs, Claygent, Signals, and contextual analysis
3. **Relevant Contacts** — AI-powered identification of decision-makers and key contacts
4. **Duplicate Prevention** — Smart deduplication via domain/LinkedIn matching
5. **Sales Visibility** — Seamless Salesforce integration with custom fields and notifications
6. **Scalability** — AWS Lambda serverless architecture for 1,000 to 100,000+ accounts

## 📊 Presentation Features

### Design
- **Dark Mode Portfolio Style** — Cyan (#00d9ff) & Lime Green (#00ff88) accents on dark background
- **Glass-Morphism Effects** — Modern glassmorphic card designs with blur and backdrop filters
- **Responsive Layout** — Two-column grids, flexible components, optimized spacing
- **Smooth Animations** — Cubic bezier transitions, floating elements, scale effects

### Navigation
- **Collapsible Sidebar** — Expandable navigation index with 16 slide titles
  - Hover to expand / Click button to toggle
  - Active slide highlighting
- **Keyboard Navigation** — Arrow keys to move between slides
- **Dot Indicators** — Visual slide counter at the bottom
- **Slide Counter** — Current slide / Total slides display

### Content (16 Slides)
1. **Cover** — Presentation title & context
2. **The Problem** — Incomplete data & inefficient assignment
3. **The Solution** — 3 pillars of the system
4. **How It Works** — 10-step workflow overview
5. **STEP -1** — Intelligent deduplication logic
6. **STEP 0** — Validation gate & enrichment steps 1-5
7. **STEP 6** — Agent AI analysis
8. **STEP 7-8** — Quality scoring & seller matching intro
9. **Deep Dive** — Intelligent seller matching algorithm
10. **STEP 9** — Manager decision & approval
11. **Seller Ready** — Account ready for SDR action
12. **Salesforce Integration** — Visibility & custom fields
13. **Scalability** — Infrastructure from 1K to 100K+ accounts
14. **ACME Corp Case** — Real-world 18-minute workflow example
15. **Learning Loop** — Continuous improvement through feedback
16. **The Result** — Outcomes & benefits

### Visual Content
- Workflow diagrams
- Enrichment card mockups
- Manager notification UI
- Account executive mobile/desktop interface
- Salesforce integration examples

## 🚀 How to View

1. **Open in Browser** → `nuvei_portfolio_style.html`
2. **Navigate** → 
   - Arrow keys (← →) or click navigation buttons
   - Click sidebar items to jump to any slide
   - Use toggle button (☰) to expand/collapse sidebar

## 📁 Project Structure

```
nuvei-presentation/
├── nuvei_portfolio_style.html    # Main presentation file
├── nuvei_visual_content/         # Supporting images & diagrams
│   ├── workflow_diagram.jfif
│   ├── enrichment_card.jfif
│   ├── manager_notification.jfif
│   ├── ae_mobile_desktop.jfif
│   └── salesforce_integration_views.jfif
└── README.md                      # This file
```

## 💡 Key Design Decisions

### Architecture
- **Serverless (AWS Lambda)** for horizontal scalability without re-architecture
- **Parallel enrichment** via concurrent API calls (Clay, Claygent, Signals)
- **Asynchronous workflows** to handle thousands of accounts per month

### UX/Design
- **Portfolio-style dark mode** to appeal to tech-savvy recruiters
- **Sidebar navigation** for intuitive browsing of complex workflow
- **Case study example** to demonstrate practical application

### Process Flow
1. **Trigger** — New account detected in system
2. **STEP -1** — Dedup check (domain/LinkedIn)
3. **STEP 0** — Validation gate (domain, ICP, SDR assignment)
4. **STEPS 1-5** — Parallel enrichment (10 minutes)
5. **STEP 6** — AI agent analysis (2 minutes)
6. **STEP 7** — Quality scoring (10 seconds)
7. **STEP 8** — Seller matching (5 seconds)
8. **STEP 9** — Manager approval (1 minute)
9. **Result** — Account ready to call in 18 minutes total

## 🎓 What This Demonstrates

- **Analytical Thinking** — Breaking down complex sales ops into logical steps
- **Automation Design** — Workflow orchestration, conditional logic, error handling
- **Scalability** — Infrastructure planning for 100x growth
- **User Experience** — Thoughtful design for sales teams & managers
- **Technical Communication** — Explaining complexity visually

## 📖 Usage Notes

- **Self-contained** — No external dependencies, works offline
- **Responsive** — Optimized for desktop viewing (1920px+ recommended)
- **Fast load** — Embedded images, no CDN calls
- **Keyboard-friendly** — Full keyboard navigation support

## 🔗 Links

- **Live Demo** → Open `nuvei_portfolio_style.html` in a modern browser
- **GitHub** → https://github.com/quim-coder/nuvei-presentation
- **Contact** → Available for interview discussions

---

**Created:** September 2026  
**Technology Stack** — HTML5, CSS3, JavaScript (Vanilla)  
**Design Framework** — Space Grotesk typography, CSS Grid, Flexbox, Glass-morphism
