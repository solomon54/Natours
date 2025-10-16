# Natours

[![Netlify Status](https://api.netlify.com/api/v1/badges/some-id/deploy-status)](https://app.netlify.com/sites/solomon-natours/deploys)  
![Screenshot of Natours Hero Section](https://solomon-natours.netlify.app/assets/images/hero-small.jpg) *(Live Demo: [solomon-natours.netlify.app](https://solomon-natours.netlify.app/))*

## Overview

Natours is a modern, responsive landing page for an adventure travel agency, showcasing exciting outdoor tours for thrill-seekers. Built with a focus on clean design and user engagement, it highlights breathtaking nature experiences, popular tour packages, and real customer testimonials. The site's tagline—"Outdoors Is where happens life"—captures its essence: inspiring users to explore the world, meet nature, find their way, and live healthier through unforgettable adventures.

Key highlights:
- **Hero Section**: Eye-catching headline with a call-to-action to discover tours.
- **Popular Tours**: Three curated options (Sea Explore, Forest Hiker, Snow Adventurer) with details on duration, group size, guides, accommodations, difficulty, and pricing.
- **Testimonials**: Genuine stories from happy customers, like "I had the best week ever with my family" (Hlina Teshale) and "Do you believe it! My life is completely changed now" (Solomon Tsehay).
- **Interactive Elements**: Smooth-scrolling CTAs ("Discover our tours", "Book now!", "Learn more →") leading to booking popups and story sections.

The design features a vibrant green palette (primary: #55c57a), elegant typography (Lato font), and mobile-first responsiveness for seamless viewing on all devices.

## Features

- **Responsive Layout**: Fully mobile-optimized with fluid grids and media queries.
- **SASS-Powered Styling**: Organized using the 7-1 pattern (Abstracts, Base, Components, Layout, Pages, etc.) for scalable, maintainable CSS.
- **Interactive CTAs**: Buttons trigger popups and section navigation for better user flow.
- **Tour Cards**: Detailed, visually appealing cards with pricing and booking links.
- **Testimonial Slider**: Placeholder for dynamic quotes (expandable with JS).
- **Browser Compatibility Notice**: Fallback for unsupported browsers.

## Tech Stack

- **Frontend**: HTML5, Sass (compiled to CSS)
- **Build Tools**: Node.js with Sass CLI for compilation
- **Fonts & Icons**: Google Fonts (Lato), Custom icon font (commented in HTML)
- **Deployment**: Netlify for static hosting
- **No Backend/JS**: Pure frontend (vanilla JS can be added for popups/animations)

## Getting Started

### Prerequisites

- Node.js (v14+ recommended) and npm
- A code editor (e.g., VS Code with Live Sass Compiler extension for auto-compilation)
- Git for version control

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/natours.git
   cd natours
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Compile Sass (watch mode for development):
   ```
   npm run compile:sass
   ```
   This generates `css/style.css` from `sass/main.scss`.

### Usage

1. Open `index.html` in a browser or use a local server (e.g., VS Code Live Server extension).
2. Edit Sass partials in `/sass/` (e.g., add colors in `abstract/_variables.scss`).
3. Changes auto-compile to CSS via the watcher.
4. Test responsiveness by resizing the browser or using dev tools.

Example: To customize the primary color, update `$color-primary` in `sass/abstract/_variables.scss` and save—styles update instantly.

## Deployment

This project is deployed to Netlify for free static hosting:

1. Push your code to GitHub.
2. Connect your repo to [Netlify](https://netlify.com) via drag-and-drop or CLI.
3. Set build command: `npm run compile:sass` (one-time, not watched).
4. Publish directory: `/` (root).
5. Your site goes live at a custom URL like `solomon-natours.netlify.app`.

Live example: [https://solomon-natours.netlify.app/#cta](https://solomon-natours.netlify.app/#cta)

## Contributing

Contributions are welcome! Please:

1. Fork the repo and create a feature branch (`git checkout -b feature/amazing-feature`).
2. Commit changes (`git commit -m 'Add amazing feature'`).
3. Push to the branch (`git push origin feature/amazing-feature`).
4. Open a Pull Request.

For major changes, open an issue first to discuss.

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

---

*Built with ❤️ by [Solomon Tsehay](mailto:solomontsehay@example.com). Inspired by Jonas Schmedtmann's Advanced CSS course.*
