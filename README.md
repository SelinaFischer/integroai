#  Website build documentation
> **Version 1.0** | November 2025

This repository contains the source code for the static website, built to be lightweight, fast, and easily maintainable.

---

## 🛠 Technology Stack
The website uses a simple, maintainable stack optimised for fast deployment and easy updates.

| Component | Technology | Description |
| :--- | :--- | :--- |
| **Frontend** | HTML5 / CSS3 / Vanilla JS | Single-page structure with CSS variables and minimal JS  |
| **Typography** | Google Fonts | Inter font family (Weights: 300-800) |
| **Hosting** | GitHub Pages | Free static site hosting  |
| **DNS/SSL** | Cloudflare | DNS management and SSL enforcement |
| **Integrations** | Calendly | Discovery call booking system |

---

## 📂 Repository Structure
<details>
<summary><b>Click to view file structure</b></summary>

The GitHub repository is organised as follows:

```text
/integroai/
├── index.html          → Main website file 
├── logo.png            → Company logo (nav bar) 
├── CNAME               → Custom domain config 
├── favicons/           → Browser tab icons 
│   ├── favicon.ico
│   ├── favicon-32x32.png
│   └── apple-touch-icon.png
└── images/             → Website images 
    └── hero-bg.png     → Hero background 
Naming Conventions:

Use lowercase for all filenames.

Use hyphens instead of spaces (e.g., hero-bg.png).

Avoid double extensions (e.g., hero-bg.png.png).

</details>

🎨 Branding & Design System
<details> <summary><b>Click to view Colour Palette & Typography</b></summary>

Colour Palette
CSS variables are defined in :root for consistent theming:

🔵 Primary: #012f46 (Dark navy - main brand colour) 

🟤 Accent: #b8987f (Warm tan - buttons, highlights) 

📜 Tagline: #E5C9A8 (Light beige) 

🌊 Green: #bacbcb (Muted teal - accents) 

⚪ Light BG: #fafbfc (Off-white - section backgrounds) 

🌑 Neutral: #4a4a4a (Dark grey - body text) 

Typography

Font: Inter (Google Fonts) 


Weights: 300, 400, 500, 600, 700, 800 


Base Line-Height: 1.7 

</details>

🧩 Key Website Sections
<details> <summary><b>Click to view Section Breakdown</b></summary>


Hero Section: Full-width background (hero-bg.png) with 40-50% opacity overlay. Headline: "AI Solutions Simplified".



Journey Section: Four-step process grid: Discover, Strategise, Implement, Grow.


Why AI Fails: Pyramid layout (3+2) highlighting leadership, priority, and data gaps .


Services: 2x2 grid covering Assessment, Strategy, Training, and Implementation .


The Framework: "Simplify • Amplify • Grow" pyramid with three colour-coded tiers .

Interactive Sections:


About: Collapsible section containing values and founder perspective .


FAQ: 9 expandable questions answering common client queries .

</details>

⚙️ Development & Features
Collapsible Logic
To reduce page length while keeping content accessible, the "About" and "FAQ" sections use JavaScript-powered collapsible functionality.

JavaScript

// Example Logic unction toggleAboutSection() {
  const section = document.querySelector('.collapsible-section');
  section.classList.toggle('active');
}
Visual Indicators

Collapsed: Shows [+] icon.


Expanded: Icon rotates 45° to show [×].

Favicons
Favicons are generated for universal browser support and stored in the favicons/ folder .

🚀 Deployment Guide
<details> <summary><b>View Deployment Steps</b></summary>

1. GitHub Pages
Go to Settings → Pages.

Select source: Deploy from a branch (main / root).

Enter custom domain: integroai.tech.

Ensure Enforce HTTPS is enabled.

2. Cloudflare DNS

CNAME (@): Target yourusername.github.io.


CNAME (www): Target yourusername.github.io.


SSL/TLS: Set to "Full" and enable "Always Use HTTPS" .

</details>

🔮 Future Enhancements
[ ] Blog/Articles section for thought leadership 

[ ] Case studies showcasing client results 

[ ] Testimonials carousel 

[ ] Newsletter signup integration 

[ ] Analytics integration (Google Analytics, Plausible)
