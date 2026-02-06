# IntelliToggle Homepage

A pixel-perfect recreation of the IntelliToggle homepage design built with **Nuxt 3**, **Vue 3**, and **TailwindCSS**.

## 🚀 Live Demo

[Add your deployed URL here]

## 📋 Features

- ✅ Fully responsive design (Desktop + Mobile)
- ✅ Interactive mobile menu toggle
- ✅ Smooth hover animations and transitions
- ✅ Component-based architecture
- ✅ Semantic HTML and accessibility considerations
- ✅ Optimized for performance
- ✅ Built with Nuxt 3 auto-imports

## 🛠️ Tech Stack

- **Nuxt 3** - Vue.js framework
- **Vue 3** - Progressive JavaScript framework
- **TailwindCSS** - Utility-first CSS framework
- **Vite** - Next generation frontend tooling

## 📦 Installation

```bash
# Install dependencies
npm install

# Development server (runs on http://localhost:3000)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📁 Project Structure

```
intellitoggle-homepage/
├── components/
│   ├── Header.vue              # Navigation header with mobile menu
│   ├── HeroSection.vue         # Hero section with CTA
│   ├── LogoShowcase.vue        # Trusted by companies section
│   ├── WhatIsSection.vue       # What is IntelliToggle
│   ├── OpenFeatureSection.vue  # OpenFeature integration
│   ├── ControlPowerSection.vue # Three feature cards
│   ├── ComparisonTable.vue     # Feature comparison table
│   ├── DartCodeAISection.vue   # Enterprise features grid
│   ├── PricingSection.vue      # Pricing plans
│   ├── TestimonialsSection.vue # Customer testimonials
│   ├── CTASection.vue          # Final call-to-action
│   └── Footer.vue              # Site footer
├── pages/
│   └── index.vue               # Main homepage
├── app.vue                     # Root component
├── nuxt.config.ts              # Nuxt configuration
├── tailwind.config.js          # Tailwind configuration
└── package.json                # Dependencies
```

## 🎨 Design Fidelity

This implementation closely matches the Figma design with:

- **Colors**: Custom purple theme (#4A3F8F) with orange accents (#FFA726)
- **Typography**: Inter font family
- **Spacing**: Consistent padding and margins matching design specs
- **Components**: All sections from the original design
- **Responsive**: Mobile-first approach with breakpoints

## 🔧 Interactive Elements

1. **Mobile Menu Toggle** (Header component)
   - Hamburger icon that transforms to X
   - Smooth slide-down animation
   - Accessible with proper ARIA labels

## 📝 Development Notes

### Tradeoffs & Shortcuts

1. **Logo Placeholders**: Used text placeholders for company logos instead of actual images
2. **Dashboard Mock**: Created simplified dashboard mockups with CSS instead of exact screenshots
3. **Icons**: Used Heroicons (Tailwind's icon set) instead of custom SVG exports
4. **Testimonial Avatars**: Used simple letter avatars instead of photos

### With More Time, I Would:

1. **Assets**: Export and integrate actual logos, screenshots, and images from Figma
2. **Animations**: Add more sophisticated scroll-triggered animations using libraries like GSAP or Framer Motion
3. **Accessibility**: Conduct full accessibility audit and add skip links, focus management
4. **Performance**: Implement image optimization with Nuxt Image module
5. **Testing**: Add component tests with Vitest
6. **Dark Mode**: Implement full dark mode toggle (foundation is there)
7. **Forms**: Add actual form validation and submission for newsletter/CTAs
8. **SEO**: Add comprehensive meta tags and structured data
9. **Analytics**: Integrate analytics tracking
10. **CMS**: Connect to a headless CMS for easy content updates

## 🎯 Pixelay Comparison

See the `/pixelay` folder for:
- Desktop overlay comparison
- Mobile overlay comparison  
- Detailed notes on differences

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

This is a technical assignment project. For the actual IntelliToggle project, please contact the team.

## 📄 License

This is a demonstration project created for technical assessment purposes.

---

Built with ❤️ using Nuxt 3 + Vue 3 + Tailwind CSS
