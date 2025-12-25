# 🍹 Mocktail Webapp

A modern, interactive web application showcasing a collection of premium mocktails and cocktails. Built with React and enhanced with smooth GSAP animations, this single-page application provides an immersive experience for exploring cocktail recipes and information.

## 🌐 Live Demo

**[View Live Application](https://shantanu-gsap-cocktails-pi-indol.vercel.app/)**

## ✨ Features

- **Animated Hero Section**: Stunning hero section with video background and text animations using GSAP SplitText
- **Interactive Cocktail Menu**: Browse through a curated collection of cocktails with smooth transitions and animations
- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Smooth Scrolling Animations**: GSAP ScrollTrigger animations that enhance the user experience as you scroll
- **Interactive Slider**: Navigate through cocktails using tabs or arrow buttons with smooth GSAP transitions
- **About Section**: Learn about the cocktail crafting process and features
- **Art Section**: Showcase of cocktail artistry and presentation
- **Contact Section**: Store information, opening hours, and social media links

## 🛠️ Tech Stack

- **React 19.2.0** - Modern React with latest features
- **Vite 7.2.4** - Fast build tool and development server
- **GSAP 3.14.2** - Professional-grade animation library
  - ScrollTrigger - Scroll-based animations
  - SplitText - Text animation effects
- **Tailwind CSS 4.1.18** - Utility-first CSS framework
- **React Responsive** - Media query hooks for responsive design

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Mocktail_webapp
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 🚀 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check for code issues

## 📁 Project Structure

```
Mocktail_webapp/
├── public/
│   ├── images/          # Image assets
│   ├── videos/          # Video assets
│   └── fonts/           # Custom fonts
├── src/
│   ├── components/
│   │   ├── Navbar.jsx   # Navigation component
│   │   ├── Hero.jsx     # Hero section with video
│   │   ├── Cocktails.jsx # Cocktails showcase
│   │   ├── About.jsx    # About section
│   │   ├── Art.jsx      # Art section
│   │   ├── Menu.jsx     # Interactive menu slider
│   │   └── Contact.jsx  # Contact information
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles
├── constants/
│   └── index.js         # Data constants (cocktails, nav links, etc.)
└── package.json         # Project dependencies
```

## 🎨 Key Components

### Hero Section
- Animated title with character-by-character reveal
- Video background with scroll-triggered playback
- Parallax leaf decorations
- Responsive subtitle animations

### Menu Component
- Interactive cocktail slider with smooth transitions
- Tab navigation for quick cocktail selection
- Arrow navigation for sequential browsing
- GSAP-powered animations for content reveals

### Responsive Design
- Mobile-first approach
- Breakpoint-based animations
- Optimized video playback for different screen sizes

## 🎬 Animation Features

- **ScrollTrigger Animations**: Elements animate as you scroll through the page
- **SplitText Effects**: Text reveals character by character or line by line
- **Smooth Transitions**: All interactions use GSAP's easing functions for professional animations
- **Video Scrubbing**: Hero video scrubs based on scroll position

## 🌍 Deployment

This project is deployed on **Vercel**. The deployment is automatically triggered on pushes to the main branch.

To deploy manually:
1. Build the project: `npm run build`
2. Deploy the `dist` folder to your hosting provider

## 📝 License

This project is private and proprietary.

## 👨‍💻 Author

**Shantanu**

## 🙏 Acknowledgments

- GSAP for the powerful animation library
- Vercel for seamless deployment
- All the cocktail enthusiasts who inspired this project

---

**Note**: This is a showcase web application. All cocktail recipes and information are for demonstration purposes.
