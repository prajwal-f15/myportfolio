# 🚀 Prajwal Fating - Full Stack Developer Portfolio

A modern, animated portfolio website showcasing projects, skills, and achievements with a sleek **orange/black/neon theme**.

## 🎨 Features

- **Dark Theme** - Pure black background with orange accent colors
- **Neon Accents** - Vibrant orange (#ff6b35), yellow (#ffd60a), cyan (#00d9ff), and green (#06ffa5) highlights
- **Smooth Animations** - Built with Framer Motion & GSAP
- **Responsive Design** - Fully mobile-friendly with Tailwind CSS
- **Next.js 14** - Modern React framework with App Router
- **SEO Optimized** - Meta tags and structured data
- **Admin Dashboard** - Protected admin login with authentication

## 📋 Sections

1. **Hero Section** - Eye-catching introduction with CTA buttons
2. **About** - Story, expertise, and tech stack showcase
3. **Skills** - Organized skill categories with visual indicators
4. **Projects** - Showcase of portfolio projects with live demos
5. **Achievements** - Certifications and accomplishments
6. **Blog** - Latest blog posts (optional)
7. **Contact** - Get in touch section
8. **Admin Dashboard** - Portfolio management (protected route)

## 🛠️ Tech Stack

- **Frontend Framework**: Next.js 14.2.35
- **UI Library**: React 18.2.0
- **Styling**: Tailwind CSS 3.3.0
- **Animations**: 
  - Framer Motion 10.10.0
  - GSAP 3.12.2
- **Icons**: Lucide React 0.263.1
- **CSS Processing**: PostCSS (CommonJS)

## 🎯 Color Scheme

| Color | Hex | Usage |
|-------|-----|-------|
| Orange | `#ff6b35` | Primary accent, gradients |
| Yellow | `#ffd60a` | Secondary highlight |
| Neon Green | `#06ffa5` | Accent highlights |
| Neon Cyan | `#00d9ff` | Accent highlights |
| Black | `#0a0a0a` | Primary background |
| Gray | `#f5f5f5` | Text |

## 📦 Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

## 🚀 Deployment

The project is optimized for deployment on Vercel:

```bash
npm run build
npm start
```

## 📁 Project Structure

```
frontend/
├── app/
│   ├── admin/          # Admin dashboard routes
│   ├── page.jsx        # Home page
│   ├── layout.jsx      # Root layout
│   └── globals.css     # Global styles
├── lib/
│   ├── components/     # React components
│   ├── context/        # Context providers
│   ├── hooks/          # Custom hooks
│   └── utils/          # Utility functions
├── public/             # Static assets
├── tailwind.config.js  # Tailwind configuration
├── postcss.config.js   # PostCSS configuration
├── next.config.js      # Next.js configuration
└── package.json        # Dependencies
```

## 🔐 Authentication

Admin routes are protected with authentication context. Configure your auth provider in `lib/context/AuthContext.js`.

## 📝 Customization

### Change Portfolio Content

Edit content in component files:
- **About Section**: `lib/components/AboutSection.jsx`
- **Projects**: `lib/components/ProjectsSection.jsx`
- **Skills**: `lib/components/SkillsSection.jsx`
- **Achievements**: `lib/components/AchievementsSection.jsx`

### Customize Colors

Update theme colors in:
- `tailwind.config.js` - Tailwind color definitions
- `app/globals.css` - CSS custom properties

## 🎬 Animations

Animations are configured with:
- **Framer Motion**: Scroll-triggered section animations
- **GSAP**: Advanced scroll effects and interactive animations
- **Tailwind CSS**: Hover states and transitions

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source. Feel free to fork and customize for your own portfolio.

## 🤝 Contributing

Improvements and suggestions are welcome! Feel free to open issues or pull requests.

---

**Built with ❤️ using Next.js, React, and Tailwind CSS**

Visit the live site: [Your Portfolio URL]
