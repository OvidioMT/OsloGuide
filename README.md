# OsloGuide v1.0

## Description

**OsloGuide** is a responsive web-based travel guide dedicated to showcasing the primary tourist attractions of Oslo, Norway. Developed as a clean and modern landing page, it provides users with essential information about historical sites, museums, and natural landmarks.

The project focuses on User Experience (UX) and Visual Hierarchy, ensuring that travelers can quickly browse through the city's highlights. It features a curated selection of locations, each accompanied by descriptive content and high-quality imagery to inspire future visitors.

The system is built with a lightweight architecture, prioritizing fast loading times and cross-browser compatibility without the need for heavy external frameworks.

---

# Features

* **Responsive Web Design:** Fully optimized for mobile, tablet, and desktop viewing.
* **Curated Content:** Organized sections for major landmarks like the Vigeland Park, Fram Museum, and the Opera House.
* **Intuitive Navigation:** Sticky navigation bar for seamless browsing across different sections.
* **Interactive UI:** Hover effects and smooth transitions to improve user engagement.
* **Visual Integration:** Use of high-resolution imagery to provide an immersive travel preview.

---

# Site Sections

The guide is divided into logical segments to facilitate information consumption:

* **Hero Section:** High-impact visual introduction to the city of Oslo.
* **Destinations / Attractions:** Individual cards or sections detailing the history and significance of each site.
* **About / Mission:** Brief overview of the guide's purpose.
* **Footer:** Contact information and social links.

---

# Project Structure

The project follows a standard frontend organization to ensure maintainability.

```
OsloGuide/
│
├── css/             # Stylesheets (layout, typography, and responsiveness)
├── img/             # Optimized image assets (landmarks and icons)
├── js/              # Client-side interactivity scripts
├── index.html       # Main entry point and structural markup
└── README.md        # Project documentation
```

### Component Overview

**index.html**
* Defines the semantic structure of the site.
* Implements SEO best practices with appropriate meta tags.

**css/**
* Contains the design system, including color palettes (inspired by Nordic minimalism) and grid/flexbox layouts.

**img/**
* Stores compressed visual assets to ensure high performance and fast "First Contentful Paint" (FCP).

---

# Tech Stack

### Frontend Core
* **HTML5** — Semantic structure.
* **CSS3** — Custom styling and responsive layouts (Media Queries).
* **JavaScript** — DOM manipulation and navigation logic.

### Deployment & Hosting
* **GitHub Pages** — Hosting for the live production environment.

---

# Project Setup

## 1. Clone the repository

```bash
git clone https://github.com/OvidioMT/OsloGuide.git
cd OsloGuide
```

##2. Local Development
Since this is a static site, you don't need to install dependencies via npm or pip. You can simply:

1. Open index.html directly in your browser.
2. OR use a local server (like "Live Server" in VS Code) for real-time updates.

##3. Deployment
To deploy your own version:

1. Push your changes to your GitHub repository.
2. Go to Settings > Pages.
3. Select the main branch as the source and click Save.

---

# Credits

### Author

* Ovidio Martinez Taleno
