# ❤️ Romantic Surprise Website

A personalized interactive website gift for your special someone.

## ✨ Features

- 🎵 Music player with romantic songs
- 📸 Photo gallery with memories
- 💌 Personalized love letters and wishes
- 📅 Timeline of special moments
- 🎨 Beautiful glassmorphism design
- 📱 Fully responsive (desktop, tablet, mobile)

## 🚀 Quick Start

### Development

1. Install dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Open your browser at `http://localhost:3000`

### Production Build

```bash
npm run build
```

The optimized production build will be in the `dist/` folder.

## 📦 Deployment

### Deploy to Vercel (Recommended)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com)
3. Import your repository
4. Vercel will automatically detect the Vite configuration
5. Deploy!

The `vercel.json` file is already configured for optimal deployment.

### Deploy to Netlify

1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Import your repository
4. Netlify will use the `netlify.toml` configuration
5. Deploy!

### Deploy to Other Platforms

The built files in `dist/` can be deployed to any static hosting service:
- GitHub Pages
- AWS S3 + CloudFront
- Firebase Hosting
- Any VPS with Nginx

## 🎵 How to Add Your Music

1. Find your audio file (MP3 format recommended)
2. Place it in the `public/` folder
3. Update the music paths in `src/components/MusicZone.jsx`

## 📸 How to Add Your Photos

1. Place images in the `public/` folder
2. Open `src/components/GalleryZone.jsx`
3. Update the `photos` array with your image paths

## 💌 Customizing Content

- **Love Letter**: Edit `src/components/LoveZone.jsx`
- **Timeline**: Edit `src/components/TimelineZone.jsx`
- **Wishes**: Edit the wish components in `src/components/`
- **Colors & Styling**: Edit `src/design-system/design-tokens.css`

## 🛠️ Tech Stack

- **React 18** - UI Framework
- **Vite** - Build Tool
- **Framer Motion** - Animations
- **GSAP** - Advanced Animations
- **Lucide React** - Icons
- **Canvas Confetti** - Special Effects

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier

## 🎨 Design System

The project uses a comprehensive design system with CSS variables:
- Colors, typography, spacing, shadows
- Responsive breakpoints
- Accessibility features
- Component styles

All design tokens are in `src/design-system/design-tokens.css`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Security

- No sensitive data stored
- All content is client-side
- HTTPS recommended for production

## 📄 License

Private project - Personal use only

---

Made with ❤️ for someone special
