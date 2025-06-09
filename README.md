# Compatto Furnishing

A modern, responsive website for Compatto Furnishing - Greece's premier furniture solutions provider.

## Features

- 🎨 Modern, responsive design with Tailwind CSS
- 📱 Mobile-first approach with custom breakpoints
- 🚀 Fast loading with optimized CSS
- 🎯 Clean, professional UI for the furnishing industry
- 🔤 Google Fonts integration (Inter, Archivo, Poppins, Montserrat, etc.)
- 🎨 Custom color palette and design system

## Project Structure

```
demo/
├── public/
│   └── index.html                    # Main HTML file
├── src/
│   └── assets/
│       └── css/
│           ├── input.css             # Tailwind CSS directives
│           ├── global.css            # Global styles and CSS variables
│           ├── fonts.css             # Google Fonts imports
│           └── tailwind-output.css   # Generated CSS (after build)
├── tailwind.config.js                # Tailwind configuration with custom theme
├── postcss.config.js                 # PostCSS configuration
├── package.json                      # Dependencies and scripts
└── README.md                        # This file
```

## Setup Instructions

1. **Install Dependencies**

   ```bash
   npm install
   ```

2. **Build CSS**

   ```bash
   # Development (with watch mode)
   npm run dev

   # Production build
   npm run build
   ```

3. **Serve the Website**
   ```bash
   npm run serve
   ```
   This will start a local server at `http://localhost:3000`

## Development

- **Watch Mode**: Run `npm run dev` to automatically rebuild CSS when files change
- **Production Build**: Run `npm run build` for minified CSS
- **Local Server**: Run `npm run serve` to view the website locally

## Custom Features

### Responsive Breakpoints

- `2xl`: max-width 1980px
- `xl`: max-width 1680px
- `lg`: max-width 1440px
- `md`: max-width 1024px
- `sm`: max-width 769px
- `xs`: max-width 480px
- `xxs`: max-width 379px

### Available Fonts (Google Fonts)

- **Inter** - Primary font family
- **Archivo** - Modern sans-serif
- **Poppins** - Clean and geometric
- **Montserrat** - Professional and readable
- **Open Sans** - Friendly and approachable
- **Roboto** - Google's system font

### Color Palette

- Primary: `#8b6f55` (Brown)
- Primary Dark: `#775d47`
- Background: `#f9f6f1` (Light cream)
- Gradient: `#cba98e` to `#a8846d`

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main` or `master`)
4. Set folder to `/docs` or `/public`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `public`
4. Deploy!

## Technologies Used

- **Tailwind CSS** - Utility-first CSS framework
- **PostCSS** - CSS processing
- **Autoprefixer** - Vendor prefix automation
- **Google Fonts** - Web font service for typography

## License

MIT License - feel free to use this project for your own purposes.
