# 🌐 Web Development Projects Portfolio

Welcome to my **Web Development Projects Repository**!
This collection showcases five full-stack frontend projects built during my internships in 2026, demonstrating modern web technologies, responsive design, and user-centric development practices.

> 👩‍💻 **Author:** Mokkapati KavyaSri &nbsp;|&nbsp; 📚 **BTech CSE · 3rd Year**  
> 🎓 **Batch:** 2026 &nbsp;|&nbsp; 📍 **Bhimavaram, Andhra Pradesh, India**  
> 🔗 **GitHub:** [@mokkapatikavyasri-dot](https://github.com/mokkapatikavyasri-dot)

---

## 📂 Project Overview

| # | Project | Type | Tech Stack | Status |
|---|---------|------|-----------|--------|
| 1 | **Portfolio Website** | Personal Portfolio | HTML, CSS, JavaScript | ✅ Complete |
| 2 | **Portfolio Website v2** | Enhanced Portfolio | HTML, CSS, JS, Dark/Light Mode | ✅ Complete |
| 3 | **Today's List** | Task Manager | HTML, CSS, Vanilla JS, LocalStorage | ✅ Complete |
| 4 | **Stratos Weather** | Weather App | HTML, CSS, JS, Open-Meteo API | ✅ Complete |
| 5 | **ShopKart** | E-commerce Catalog | HTML, CSS, Modular JS, FakeStore API | ✅ Complete |

---

## 🚀 Project Details

### 1️⃣ Portfolio Website (v1)

**Purpose:** Professional personal portfolio built for Thiranex Web Development Internship.

**Key Features:**
- ✨ Semantic HTML5 with WCAG accessibility compliance
- 🎨 Modern dark purple gradient design with smooth animations
- 📱 Fully responsive mobile-first CSS Grid & Flexbox layout
- ♿ ARIA labels, skip links, keyboard navigation
- 🔍 SEO meta tags (Open Graph, title, description)
- 📧 Contact form with input validation
- 🎯 About section with internship stats
- 💼 Projects showcase with GitHub links
- 🎨 CSS variables for consistent theming

**Technologies:** HTML5, CSS3, Semantic Markup, Accessibility (WCAG)

**Key Concepts:**
- Semantic HTML structure (`<section>`, `<article>`, `<nav>`)
- CSS Grid for layout (`grid-template-areas`)
- CSS custom properties (variables)
- Flexbox for alignment
- Form accessibility with labels and ARIA
- Skip links for keyboard users
- Meta tags for SEO and social sharing

---

### 2️⃣ Portfolio Website (v2 — Enhanced)

**Purpose:** Improved version with interactive features and theme switching.

**Key Features:**
- 🌙 Dark/Light mode toggle with localStorage persistence
- 🎨 CSS custom properties supporting dual themes
- 📱 Mobile hamburger navigation menu
- ⚡ Smooth transitions and animations
- 🏆 Stats cards with hover effects
- 💻 Featured project section spanning 2 columns
- 🎯 Enhanced contact form with side-by-side layout
- 🔗 Social links in footer
- ✅ Full accessibility maintained

**Technologies:** HTML5, CSS3 (Grid, Flexbox, Animations), Vanilla JavaScript

**Key Concepts:**
- CSS data attributes for theme switching (`data-theme`)
- JavaScript event listeners for interactivity
- Theme persistence with localStorage
- CSS Grid with `grid-template-columns` and gap
- Media queries for responsive breakpoints (@media)
- `classList` manipulation in JavaScript
- Dynamic HTML rendering with `innerHTML`

---

### 3️⃣ Today's List — Task Manager

**Purpose:** Minimalist task management app with persistent storage.

**Key Features:**
- ✅ Add, edit, delete tasks with inline editing
- 📊 Progress bar showing completion percentage
- 🏷️ Filter tabs: All, Active, Completed
- 🎨 Elegant serif typography (DM Serif Display)
- 💾 LocalStorage persistence across sessions
- ⏰ Relative timestamps ("2m ago", "1h ago")
- 🗑️ Clear completed tasks in one click
- 🎯 Drag-and-drop task reordering
- 🎨 Calm color palette: sage green, amber, paper white
- ♿ Accessible form controls and ARIA labels

**Technologies:** HTML5, CSS3, Vanilla JavaScript, LocalStorage API

**Key Concepts:**
- Array methods: `filter()`, `map()`, `reduce()`, `find()`
- localStorage for data persistence
- Event delegation for dynamic elements
- Date/time calculations for relative timestamps
- CSS animations (`slideIn`, `floating`)
- Drag and drop event handling
- Form input validation
- Empty state UI patterns

---

### 4️⃣ Stratos — Live Weather Dashboard

**Purpose:** Real-time weather application powered by free Open-Meteo API.

**Key Features:**
- 🌡️ Current temperature, feels-like, conditions
- 💨 Wind speed, direction, gust, humidity, pressure
- 👁️ Visibility with visual progress bar
- 🌅 Sunrise/sunset times (timezone-aware)
- ☁️ Cloud cover percentage display
- 🔍 City search with autocomplete suggestions
- 📍 Geocoding integration (Open-Meteo)
- 🌍 Automatic timezone detection
- 🎨 Glassmorphism UI with animated starfield
- 📊  6-metric grid layout with icons
- ✅ Error handling and user feedback (toast notifications)

**Technologies:** HTML5, CSS3 (Grid, Flexbox, Glassmorphism), Vanilla JavaScript, Fetch API

**External APIs:**
- **Open-Meteo Geocoding API** — Location search (free, no key)
- **Open-Meteo Forecast API** — Live weather data (free, no key)

**Key Concepts:**
- Async/await with error handling
- Fetch API for HTTP requests
- DOM manipulation and event listeners
- CSS Grid for metric cards
- Debouncing search input (350ms timer)
- WMO weather code mapping (95+ conditions)
- UTC clock display with `toLocaleTimeString()`
- Relative time zones with timezone parameter
- Loading states and spinner animation
- Toast notifications for user feedback

---

### 5️⃣ ShopKart — E-commerce Product Catalog

**Purpose:** Modern e-commerce frontend built as Thiranex Capstone Project.

**Key Features:**
- 🏪 Product grid with lazy loading
- 🔍 Search products with debouncing
- 📂 Filter by category (8+ categories)
- 📊 Sort: default, price (asc/desc), rating, name A-Z
- ⭐ Star ratings with review count
- 🛒 Shopping cart with persistent storage
- 💰 Real-time cart total, shipping calculation
- 📱 Product detail page with quantity control
- 🎨 Responsive CSS Grid layout
- 🌊 Glassmorphic card design with shadows
- 💳 Checkout simulation
- 📱 Mobile hamburger navigation
- 🚀 Modular JavaScript architecture

**Technologies:** HTML5, CSS3 (Grid, Flexbox, Variables), Vanilla JavaScript (Modular), Fetch API

**External API:**
- **FakeStore API** — Free e-commerce REST API with 20 products across 4 categories

**Key Concepts:**
- Client-side routing (hash-based SPA)
- Modular JavaScript architecture (State, Router, API, UI modules)
- Async/await with Promise.all() for parallel API calls
- Array methods: `find()`, `filter()`, `sort()`, `map()`
- localStorage for cart persistence
- CSS Grid with `auto-fit` and `minmax()`
- Product card hover effects and animations
- Loading skeletons (shimmer animation)
- Search filtering with `includes()` and `toLowerCase()`
- Multi-criteria sorting
- Toast notifications
- Form handling and validation
- Star rating display system

---

## 💻 Technologies Stack

### Frontend
- **HTML5** — Semantic markup, accessibility (ARIA, skip links)
- **CSS3** — Grid, Flexbox, custom properties, animations, media queries
- **JavaScript (Vanilla)** — ES6+ syntax, async/await, DOM manipulation, event handling

### Storage
- **LocalStorage API** — Persistent data across sessions
- **In-Memory State** — React-like state management patterns

### APIs
- **Open-Meteo Geocoding & Forecast API** — Live weather data (free)
- **FakeStore API** — E-commerce mock data (free)
- **Fetch API** — HTTP requests with async/await

### Design Patterns
- **CSS Variables** — Design token system for theming
- **Flexbox & CSS Grid** — Responsive layouts
- **Modular JavaScript** — Separation of concerns (Router, State, API, UI modules)
- **Client-Side Routing** — Hash-based SPA navigation
- **Mobile-First Responsive Design** — Mobile → Tablet → Desktop

---

## 🛠️ How to Run Each Project

All projects are **standalone HTML files** that run directly in the browser — no build tools or backend required.

### Option 1: Direct File Opening (Quickest)
Simply download the HTML file and double-click to open in your browser.

### Option 2: Local Web Server (Recommended for API projects)
Some projects (Weather, ShopKart) use fetch requests that work better with a local server.

**Using Python 3:**
```bash
# Navigate to project folder
cd path/to/project

# Start local server
python -m http.server 8000

# Open http://localhost:8000 in browser
```

**Using Node.js (http-server):**
```bash
npm install -g http-server
http-server
# Open http://localhost:8080
```

### Individual Project Setup

**1. Portfolio Website v1 & v2**
- Open HTML file directly in browser
- No dependencies, works offline
- Dark/light mode toggle (v2 only)

**2. Today's List**
- Open HTML file directly
- Data saved to browser's localStorage
- Works completely offline

**3. Stratos Weather**
- Open HTML file directly OR use local server
- Requires internet connection (calls Open-Meteo API)
- Default city: London
- Search suggestions appear as you type

**4. ShopKart E-commerce**
- Open HTML file directly OR use local server
- Requires internet connection (calls FakeStore API)
- Cart data saved to localStorage
- Browse, search, filter, add to cart, checkout

---

## 📊 Project Comparison

| Feature | Portfolio v1 | Portfolio v2 | Today's List | Weather | ShopKart |
|---------|---|---|---|---|---|
| Interactivity | Low | Medium | High | High | High |
| Local Storage | ❌ | ✅ | ✅ | ❌ | ✅ |
| API Integration | ❌ | ❌ | ❌ | ✅ | ✅ |
| Dark/Light Mode | ❌ | ✅ | ❌ | ❌ | ❌ |
| Mobile Menu | ❌ | ✅ | ❌ | ❌ | ✅ |
| Accessibility | ✅ WCAG | ✅ WCAG | ✅ | ✅ | ✅ |
| Responsive | ✅ | ✅ | ✅ | ✅ | ✅ |
| Lines of Code | ~400 | ~800 | ~500 | ~650 | ~1500+ |

---

## 🎓 Learning Outcomes

### HTML & CSS Mastery
- Semantic HTML5 structure for accessibility
- CSS Grid for complex layouts
- CSS Flexbox for flexible alignment
- CSS custom properties for theming
- Responsive design with media queries
- Animation and transition techniques
- Glassmorphism and modern design patterns

### JavaScript Fundamentals
- Event handling (click, input, drag, submit)
- DOM manipulation (`querySelector`, `classList`, `innerHTML`)
- Array methods (`map`, `filter`, `find`, `reduce`, `sort`)
- Async/await and Promises
- Fetch API for HTTP requests
- localStorage for persistence
- Higher-order functions and callbacks

### Software Architecture
- Client-side routing patterns
- Modular JavaScript (separation of concerns)
- State management (localStorage + in-memory)
- API integration best practices
- Error handling and user feedback
- Accessibility (WCAG, ARIA, keyboard navigation)

---

## 🎯 Key Achievements

✅ **All projects are fully responsive** — Mobile, tablet, desktop  
✅ **Accessibility-first approach** — WCAG compliance, ARIA labels, keyboard navigation  
✅ **Production-ready code** — Clean, documented, modular architecture  
✅ **Zero external dependencies** — Vanilla JavaScript, no frameworks or libraries  
✅ **Real API integration** — Live weather data, mock e-commerce products  
✅ **Persistent storage** — localStorage for tasks and cart  
✅ **Modern design** — Glassmorphism, gradients, smooth animations  
✅ **Performance optimized** — Lazy loading, debouncing, efficient DOM queries  

---

## 📚 Code Quality

### JavaScript Best Practices
- ✅ Strict mode (`'use strict'`)
- ✅ Semantic variable names
- ✅ DRY principle (Don't Repeat Yourself)
- ✅ Comments for complex logic
- ✅ Error handling with try-catch
- ✅ Input validation and sanitization
- ✅ Modular function organization

### CSS Best Practices
- ✅ CSS variables for maintainability
- ✅ Mobile-first responsive design
- ✅ Organized style sections with comments
- ✅ Reusable utility classes
- ✅ Consistent spacing and typography
- ✅ Box-sizing: border-box
- ✅ Semantic class naming

### HTML Best Practices
- ✅ Semantic elements (`<section>`, `<article>`, `<nav>`)
- ✅ Proper heading hierarchy (h1 → h6)
- ✅ ARIA labels for accessibility
- ✅ Form labels with `<label>` tags
- ✅ Image alt attributes
- ✅ Skip links for keyboard users
- ✅ Meta tags for SEO

---

## 🚀 Deployment

All projects are ready to deploy on:
- **Netlify** — Drag & drop HTML file
- **Vercel** — Connect GitHub repo
- **GitHub Pages** — Enable in repo settings
- **Any static host** — No server required

**Recommended:** Use Netlify or Vercel for automatic deployments from GitHub.

---

## 📖 Browser Compatibility

| Browser | v1 | v2 | List | Weather | ShopKart |
|---------|----|----|------|---------|----------|
| Chrome/Edge | ✅ | ✅ | ✅ | ✅ | ✅ |
| Firefox | ✅ | ✅ | ✅ | ✅ | ✅ |
| Safari | ✅ | ✅ | ✅ | ✅ | ✅ |
| Mobile browsers | ✅ | ✅ | ✅ | ✅ | ✅ |

---

## 🤝 Contributing

These projects were built for educational purposes. Feel free to:
- Fork and modify for learning
- Add features (dark mode, more filters, animations)
- Improve accessibility further
- Optimize performance
- Adapt for your own portfolio

---

## 📄 License

These projects are provided as educational examples. Use, modify, and share freely with attribution.

---

## 🔗 Links & Resources

**Author's Links:**
- 🐙 GitHub: [@mokkapatikavyasri-dot](https://github.com/mokkapatikavyasri-dot)
- 🏢 Thiranex: [thiranex.in](https://thiranex.in)

**APIs Used:**
- 🌤️ Open-Meteo Weather: [open-meteo.com](https://open-meteo.com)
- 🛍️ FakeStore API: [fakestoreapi.com](https://fakestoreapi.com)

**Internships:**
- CodeAlpha, DecodeLabs, Alfido Tech, Thiranex, Future Interns, SkillCraft Technology

---

## 📞 Contact

**Email:** mokkapatikavyasri@gmail.com  
**Location:** Bhimavaram, Andhra Pradesh, India  
**Status:** BTech CSE Student · 3rd Year · Batch 2026

---

*Built with ❤️ by Mokkapati KavyaSri · Thiranex Web Development Internship 2026*
