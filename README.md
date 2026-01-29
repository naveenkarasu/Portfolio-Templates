# Portfolio Templates

A collection of modern, interactive portfolio website templates built with Three.js, TypeScript, and Vite. Each template features unique 3D backgrounds and is fully customizable for developers, designers, and professionals.

## Templates Included

### 1. Cosmic Portfolio (`my-portfolio/`)
A stunning portfolio with an immersive 3D Milky Way galaxy background.

**Features:**
- Interactive galaxy panorama that responds to mouse movement and scroll
- Warm amber/gold color theme with glassmorphism effects
- Animated 3D navbar logo
- Professional loading screen
- Responsive design

### 2. Particle Portfolio (`Portfolio -2/`)
A sleek portfolio with an interactive 3D particle background.

**Features:**
- Dynamic particle system with geometric shapes
- Modern dark theme with gradient accents
- Smooth scroll animations
- Clean, minimal design
- Responsive layout

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **Vite** | Fast build tool and dev server |
| **TypeScript** | Type-safe JavaScript |
| **Three.js** | 3D graphics and animations |
| **CSS3** | Custom properties, flexbox, grid, glassmorphism |

## Quick Start

1. Choose a template and navigate to its directory:
   ```bash
   cd my-portfolio
   # or
   cd "Portfolio -2"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Customize your content in `src/content/profile.ts`

5. Build for production:
   ```bash
   npm run build
   ```

## Customization

Each template uses a content-driven architecture. Simply edit the `src/content/profile.ts` file to update:
- Personal information (name, headline, location)
- Contact details and social links
- Skills and expertise
- Work experience
- Projects
- Education and certifications

See individual template READMEs for detailed customization guides.

## Deployment

Both templates include GitHub Actions workflows for automatic deployment to GitHub Pages. Push to `main` and your portfolio deploys automatically.

## License

MIT License - use these templates freely for your personal portfolio