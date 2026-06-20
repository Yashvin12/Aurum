# Aurum Studio — 3D Web Experience

> Premium, cinematic web experience powered by AI-first development workflows with scroll-driven 3D animations and full-stack architecture.

## 📋 Project Overview

This is a showcase website for **Aurum Studio**, an AI-powered web development studio. The project features:

- **Scroll-Driven Animations**: Smooth, frame-by-frame 3D product animation sequences triggered by scroll events
- **Premium Design**: Elegant dark theme with serif and sans-serif typography
- **Full SEO Optimization**: Meta tags, Open Graph, Twitter Cards, and sitemap integration
- **Responsive Layout**: Mobile-first design using CSS Grid and Flexbox
- **3D Product Showcase**: Interactive 3D headphone product presentation

## 📁 Project Structure

```
3D_Website/
├── index.html                    # Main website file
├── robots.txt                    # SEO robots configuration
├── sitemap.xml                   # XML sitemap for search engines
├── README.md                     # This file
├── frames/                       # Animation frame sequence (191 PNG frames)
│   ├── frame-0001.png
│   ├── frame-0002.png
│   └── ... (frame-0191.png)
├── Assembly video.mp4            # Product assembly animation video
├── headphone_main.mp4            # Main headphone product video
├── hero product shot.png         # Hero section image
└── exploded shot.png             # Exploded view product image
```

## 🎨 Key Features

### 1. **3D Animation Frames**
- 191 sequential PNG frames (`frames/frame-0001.png` to `frame-0191.png`)
- Enables smooth scroll-driven 3D product visualization
- Pre-loaded for optimal paint performance

### 2. **Media Assets**
- High-quality product videos (MP4 format)
- Professional product photography (PNG)
- Optimized for web delivery

### 3. **SEO & Meta Tags**
- Canonical URL for search engines
- Open Graph metadata for social sharing
- Twitter Card support
- Responsive meta viewport settings
- Custom favicon with branding

### 4. **Typography**
- **Serif Font**: Cormorant Garamond (elegant headings)
- **Sans-serif Font**: Jost (modern body text)
- Multiple weights for visual hierarchy

### 5. **Color Scheme**
- **Primary Background**: #0a0a0a (deep black)
- **Secondary Background**: #0e0e0e (subtle elevation)
- **Accent Color**: #b5651d (gold)
- **Overlay**: rgba(255,255,255,0.025) (subtle glass effect)

## 🚀 Quick Start

### 1. **View Locally**
Simply open `index.html` in a modern web browser:
```bash
# Using Python (if available)
python -m http.server 8000

# Or using Node.js http-server
npx http-server

# Or just open in browser
open index.html
```

### 2. **Deploy**
The site is production-ready for deployment to:
- Vercel
- Netlify
- GitHub Pages
- Any static hosting service

### 3. **Integration**
The HTML file includes:
- **Supabase Integration** (CDN link included)
- Modular CSS structure
- JavaScript-ready event listeners for scroll interactions

## 📊 Animation System

The scroll-driven animation works by:
1. Tracking user scroll position
2. Mapping scroll progress (0-1) to frame sequence (1-191)
3. Dynamically loading and displaying corresponding PNG frame
4. Creating illusion of smooth 3D rotation/motion

## 🔧 Technologies Used

- **HTML5**: Semantic markup with full SEO support
- **CSS3**: Modern styling with CSS Grid, custom properties, and responsive design
- **JavaScript**: Scroll event handling and frame sequencing
- **SVG**: Inline favicon for branding
- **PNG/MP4**: Media assets for product showcase

## 📱 Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for desktop, tablet, and mobile
- Preload optimization for faster first paint

## 🔐 SEO Configuration

- **robots.txt**: Configured for search engine crawling
- **sitemap.xml**: Structured site map for indexing
- **Canonical URL**: https://aurum.studio/
- **Social Meta Tags**: Optimized for sharing

## 📝 Files Description

| File | Purpose |
|------|---------|
| `index.html` | Main website with embedded styles and scripts |
| `frames/*` | 191 animation frames for scroll-driven 3D effect |
| `*.mp4` | Product demonstration videos |
| `*.png` | Hero and product imagery |
| `robots.txt` | Search engine crawler directives |
| `sitemap.xml` | XML site structure for SEO |

## 🎯 Development Notes

- All styles are embedded in the HTML file for single-file deployment
- Frame images should be pre-generated from 3D renders or screen captures
- Scroll detection should be optimized with requestAnimationFrame
- Consider lazy-loading frames beyond initial viewport

## 🚀 Next Steps

1. **Customize Typography**: Update font families in CSS
2. **Adjust Colors**: Modify CSS variables in `:root`
3. **Add Interactivity**: Enhance scroll behavior with GSAP or Three.js
4. **Optimize Performance**: Compress PNG frames and videos
5. **Deploy**: Push to hosting platform (Vercel, Netlify, etc.)

## 📄 License

© 2026 Aurum Studio. All rights reserved.

---

**Last Updated**: June 20, 2026
