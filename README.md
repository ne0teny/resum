# Beknur Sailaukhan - Portfolio Website

Personal portfolio website built with React, TypeScript, and Vite.

## Features

- 🌐 Multi-language support (Russian/English)
- 🎨 Modern and responsive design
- ⚡ Fast and optimized with Vite
- 🎭 Smooth animations and transitions
- 📱 Mobile-friendly

## Tech Stack

- React 18
- TypeScript
- Vite
- SCSS
- Lucide React (icons)

## Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment to GitHub Pages

This project is configured to deploy automatically to GitHub Pages using GitHub Actions.

### Manual Setup

1. Go to your repository Settings → Pages
2. Under "Source", select "GitHub Actions"
3. Push changes to the `main` branch
4. The site will be automatically deployed to `https://yourusername.github.io/resum/`

### Manual Deployment

If you prefer to deploy manually:

```bash
# Build the project
npm run build

# The dist folder contains the built files
# Upload the contents of dist/ to your GitHub Pages branch
```

## Project Structure

```
├── public/          # Static assets
├── src/
│   ├── components/  # React components
│   ├── contexts/    # React contexts
│   └── translations.ts  # Language translations
└── dist/            # Build output (generated)
```

## License

© 2026 Beknur Sailaukhan
