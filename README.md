# Compatto Furnishing

A modern, responsive website for Compatto Furnishing - Greece's premier furniture solutions provider.

## Features

- 🎨 Modern, responsive design with Tailwind CSS
- 📱 Mobile-first approach with custom breakpoints
- 🚀 Fast loading with optimized CSS
- 🎯 Clean, professional UI for the furnishing industry
- 🔤 Google Fonts integration (Inter, Archivo, Inter Tight)
- 🎨 Custom color palette and design system
- ♻️ Refactored codebase following best practices

## Project Structure

```
demo/
├── public/
│   ├── index.html                    # Main HTML file
│   ├── tailwind-output.css           # Generated CSS (after build)
│   └── assets/
│       └── images/                   # Image assets
├── assets/
│   └── css/
│       ├── input.css                 # Tailwind CSS directives
│       ├── global.css                # Global styles and utilities
│       └── fonts.css                 # Google Fonts imports
├── tailwind.config.js                # Tailwind configuration
├── postcss.config.js                 # PostCSS configuration
├── package.json                      # Dependencies and scripts
└── README.md                        # This file
```

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd demo
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

## Usage

### Development

```bash
# Start development server with CSS watching
npm run dev

# Start local server
npm run start
# or
npm run serve
```

### Production

```bash
# Build for production (minified CSS)
npm run build

# Clean build artifacts
npm run clean
```

### Additional Scripts

```bash
# Linting (placeholder for future setup)
npm run lint

# Formatting (placeholder for future setup)
npm run format
```

## Development Workflow

1. **Development Mode**: Run `npm run dev` to automatically rebuild CSS when files change
2. **Local Preview**: Run `npm run start` to view the website at `http://localhost:3000`
3. **Production Build**: Run `npm run build` for minified CSS output

## Custom Features

### Responsive Breakpoints

- `2xl`: max-width 1980px
- `xl`: max-width 1680px
- `lg`: max-width 1440px
- `md`: max-width 1024px
- `sm`: max-width 769px
- `xs`: max-width 480px
- `xxs`: max-width 379px

### Design System

**Typography**

- **Inter Tight** - Primary font family
- **Archivo** - Modern sans-serif
- **Inter** - System font fallback

**Color Palette**

- Primary: `#8b6f55` (Brown)
- Primary Dark: `#775d47`
- Background: `#f9f6f1` (Light cream)
- Gradient: `#cba98e` to `#a8846d`

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Set folder to `/public`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `public`
4. Deploy!

### Vercel

1. Connect your GitHub repository to Vercel
2. Set build command: `npm run build`
3. Set output directory: `public`
4. Deploy!

## Technologies Used

- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS processing
- **Autoprefixer** - Vendor prefix automation
- **Google Fonts** - Web font service

## Code Quality

This project follows modern frontend best practices:

- ✅ Semantic HTML structure
- ✅ Tailwind CSS with @apply directives
- ✅ Responsive design patterns
- ✅ Clean, maintainable code
- ✅ Optimized build process
- ✅ Standard npm script naming
- ✅ Simplified project structure

## License

MIT License - feel free to use this project for your own purposes.
