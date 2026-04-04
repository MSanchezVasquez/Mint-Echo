# Moises Sanchez | Portfolio (MCodex)

![Moises Sanchez Portfolio](./public/images/moschino-banner.jpg)
## 🎯 Overview

**MOSCHINO Portfolio** is a high-performance personal website built with Astro and TailwindCSS. It is a heavily customized version of the NeonMint template, refactored to feature a **Riptide Blue** aesthetic, improved accessibility, and a focused professional identity.

This project showcases my journey as a **FrontEnd Developer**, my projects, and my technical blog.

## 📁 Project Structure

```bash
└── 📁MoschinoPortfolio
    └── 📁public
        ├── android-chrome-192x192.png
        ├── android-chrome-512x512.png
        ├── apple-touch-icon.png
        ├── favicon-16x16.png
        ├── favicon-32x32.png
        ├── favicon.ico
        └── 📁images
            ├── 📁posts    # Blog post images
            └── 📁projects # Portfolio project images
        └── site.webmanifest
    └── 📁src
        ├── 📁components  # UI & Logic components
        │   ├── 📁blog    # Blog specific components (cards, lists)
        │   ├── 📁layout  # Nav, Footer, specialized wrappers
        │   ├── 📁portfolio # Project showcase components
        │   └── 📁ui      # Buttons, Capsules, Tags, Headings
        ├── 📁icons       # SVG Technology icons
        ├── 📁layouts     # Page structures (Base, Post, Project)
        ├── 📁pages       # Routes
        │   ├── about-me.md
        │   ├── 📁blog
        │   ├── index.astro
        │   └── rss.xml.js
        ├── 📁styles
        │   └── global.css # Custom Tailwind directives & scrollbar styles
        └── 📁utils
            └── languages.ts # Centralized tech stack configuration
    ├── astro.config.mjs
    ├── tailwind.config.js
    └── package.json

```

## 🛠️ Technology Stack

* **Framework**: Astro v5.0+
* **UI Library**: Preact (for interactive islands)
* **Styling**: TailwindCSS v4.0+
* **Icons**: astro-icon
* **Content**: Markdown & MDX
* **Performance**: @vercel/speed-insights
* **Deployment**: Vercel / Netlify

## ✨ Key Features

1. **🚀 Riptide Blue Theme**
* A consistent, custom color palette replacing the default green/mint.
* Dark mode support with deep zinc backgrounds and blue accents.


2. **⚡ Performance First**
* 100/100 Lighthouse score.
* Zero-JS by default (except for interactive islands).
* Optimized images and assets.


3. **📝 Tech Blog & Portfolio**
* Markdown-based content management.
* Tagging and categorization system.
* Code syntax highlighting with "Copy" functionality.


4. **🎨 Modern UI**
* Glassmorphism effects.
* Animated borders and transitions.
* Responsive design (Mobile-First).



## 🚀 Getting Started

To run this project locally:

1. **Clone the repository**
```bash
git clone [https://github.com/tu-usuario/tu-repo.git](https://github.com/tu-usuario/tu-repo.git)
cd tu-repo

```


2. **Install Dependencies**
```bash
npm install
# or
pnpm install

```


3. **Start Development Server**
```bash
npm run dev

```


4. **Build for Production**
```bash
npm run build

```



## ⚙️ Customization

### 🔧 Adding New Technologies

To display new tools in the "Tech Stack" or project cards:

1. **Add the Icon**: Place the SVG file in `src/icons`. Recommended source: [SVGL](https://svgl.app/).
2. **Register it**: Open `src/utils/languages.ts` and add:
```typescript
nextjs: {
    name: "Next.js",
    iconName: "nextjs", // Must match filename in src/icons
},

```



### 🎨 Colors

The color palette is defined in `global.css` and `tailwind.config.js` (if extended). The primary colors are based on the **Riptide** and **Blue** scales, replacing the original Mint colors.

## 🤝 Contributing

This is a personal portfolio, but suggestions are welcome!

1. Fork the repository
2. Create a feature branch
3. Submit a Pull Request

## 📄 License

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

---

Based on the [NeonMint](https://github.com/EFEELE/NeonMint) template by EFEELE.
Refactored and customized by **Moises Sanchez (MOSCHINO)**.
