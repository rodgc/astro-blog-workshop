# Rod's Web Dev Blog

A modern blog website built with Astro, TypeScript, and Tailwind CSS, featuring responsive design and custom typography scaling.

## 🚀 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── index.astro (Home page)
│   │   ├── about.astro (About page)
│   │   └── post.astro (Single post page)
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── postcss.config.js
├── package.json
└── tsconfig.json
```

## 🛠️ Tech Stack

- **Astro** - Static site generator
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS processing
- **Vite** - Build tool

## 🎨 Design Features

### Typography Scale

The project uses a responsive typography scale generated with Utopia:

- Scales from 360px to 1440px viewport
- Base sizes: 17px to 19px
- Scale ratios: 1.125 to 1.2
- Custom CSS variables for all text sizes

### Design System

- **Colors**: Custom green palette (#EAF4F0, #318C66, #236348)
- **Fonts**: Instrument Sans (headings) and Geist (body text)
- **Components**: Header, Footer, Article cards, Sidebar widgets
- **Layouts**: Responsive grid with sidebar

### Pages

1. **Home** - Blog listing with hero section, article grid, and sidebar
2. **About** - Personal profile with experience and skills sections
3. **Post** - Single article layout with content and sidebar

## 🚀 Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the development server:

   ```bash
   npm run dev
   ```

3. Open [http://localhost:4321](http://localhost:4321) in your browser

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run astro` - Run Astro CLI commands

## 🎯 Design Reference

This project was built based on Figma designs:

- **Home page**: Blog listing with article cards and sidebar
- **Post page**: Single article layout with hero image
- **About page**: Personal profile with experience timeline

## 📱 Responsive Design

The website is fully responsive and adapts to different screen sizes:

- Mobile-first approach
- Flexible grid layouts
- Scalable typography
- Touch-friendly interactions

## 🔧 Configuration

### Tailwind CSS

Configured with custom colors and typography. See `astro.config.mjs` for Vite plugin setup.

### PostCSS

Basic configuration with Tailwind CSS and Autoprefixer. See `postcss.config.js`.

### Typography

Custom CSS variables defined in `src/styles/global.css` for fluid typography scaling.

## 📄 License

This project is for educational and demonstration purposes.
