# Disaster & Response Timeline 🌪️

A **React** frontend project visualizing disaster events, volunteer responses, and recovery phases on an interactive timeline. Perfect for portfolios and disaster management demos.

[![Vite](https://img.shields.io/badge/Vite-B3735F?style=for-the-badge&logo=vite&logoColor=white)](https://vite.dev/)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## ✨ **Live Demo**
[View Demo](http://localhost:5173) ← Replace with your deployed URL later

## 🎮 **Features**

- **Interactive Timeline** - Vertical layout with alternating disaster cards
- **Smart Filters** - Disaster type, region, date sorting (newest/oldest)
- **Simulation Mode** - Auto-play disasters with highlighted active item
- **Rich Data** - Severity levels, response phases, volunteers, resources
- **Fully Responsive** - Desktop, tablet, mobile layouts
- **Modern UI** - Glassmorphism design, smooth animations, dark theme


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is enabled on this template. See [this documentation](https://react.dev/learn/react-compiler) for more information.

Note: This will impact Vite dev & build performances.

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.



## 📱 **Screenshots**
*(Add these after first deploy)*

| Desktop View | Mobile View |
|--------------|-------------|
| ![Desktop](screenshots/desktop.png) | ![Mobile](screenshots/mobile.png) |

## 🛠 **Tech Stack**

| Frontend | Tools | Styling |
|----------|-------|---------|
| React 18+ | Vite | CSS3 |
| JavaScript ES6+ | clsx | Custom Design |
| React Hooks | Local State | Responsive |

## 🚀 **Quick Start**

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/disaster-response-timeline.git
cd disaster-response-timeline

# Install dependencies
npm install

# Run development server
npm run dev

Open http://localhost:5173


Project Structure
disaster-response-timeline/
├── public/
├── src/
│   ├── components/
│   │   ├── Timeline.jsx
│   │   ├── DisasterCard.jsx
│   │   ├── Filters.jsx
│   │   └── SimulationControls.jsx
│   ├── data/
│   │   └── disasters.js
│   ├── App.jsx
│   ├── main.jsx
│   └── styles.css
├── package.json
└── README.md


🎯 How to Use
Filter disasters by type (Earthquake, Flood, etc.) or region

Sort by newest/oldest date

Manual simulation: Click "Next disaster"

Auto-play: Click "Start auto-play" (2.5s intervals)

Responsive: Resize browser or use dev tools for mobile view


🧪 Sample Data
Disaster	  Location	      Volunteers	  Severity
Cyclone       Aurora	      Chattogram, BD	320	🟠 4/5
Megathrust    Quake	          Pacific NW, USA	800	🔴 5/5
River         Flood	          Sunamganj, BD	    210	🟡 3/5



Note: Fictional data for demonstration only.

🔧 Customization Ideas
🌍 Add real data from disaster APIs

🗺️ Map integration (Leaflet, SVG maps)

📊 Charts (Chart.js for volunteer trends)

🎨 Theme toggle (dark/light modes)

♿ Accessibility (ARIA labels, keyboard nav)

📱 PWA (offline support)



🚀 Deployment
Vercel (Recommended)

npm install -g vercel
vercel --prod

Netlify
Drag dist/ folder after npm run build



GitHub Pages

npm install -g gh-pages
npm run deploy



📊 Development Scripts

npm run dev      # Start dev server
npm run build    # Build for production
npm run preview  # Preview production build




🎨 Design Decisions
Dark theme - Better for data visualization

Glassmorphism - Modern, professional look

Alternating timeline - Clear visual hierarchy

No external libs - Lightweight, fast loading

Mobile-first CSS - Responsive breakpoints

🤝 Contributing
Fork the repo

Create feature branch (git checkout -b feature/amazing-feature)

Commit changes (git commit -m 'Add amazing feature')

Push (git push origin feature/amazing-feature)

Open Pull Request

📄 License
MIT License - Use for portfolios, learning, or commercial projects.




Made with ❤️ for disaster management visualization
Built by Md. Jubayer Al Jami • January 2026