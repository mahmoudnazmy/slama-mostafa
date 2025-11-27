# Salma Mostafa - Portfolio Website

A modern, responsive portfolio website for UI/UX Designer Salma Mostafa, built with Vue.js 3 and Tailwind CSS.

## 🚀 Features

- ✨ Modern and clean design with dark mode support
- 📱 Fully responsive on all devices
- 🎨 Beautiful gradient animations
- ⚡ Fast and optimized with Vite
- 🎯 SEO-friendly
- 💼 Project showcase with modal details
- 📧 Contact section with social links

## 🛠️ Tech Stack

- **Vue.js 3** - Progressive JavaScript Framework
- **Composition API** - Modern Vue.js approach
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Next generation build tool
- **TypeIt.js** - Typing animation library
- **Lucide Icons** - Beautiful icon set
- **GSAP** - Professional animation library

## 📊 Project Stats

- **Total Lines of Code:** 2,255
- **Components:** 10
- **Sections:** Hero, About, Projects, Contact

## 🏗️ Development

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🌐 Deployment to GitHub Pages

This project is configured for automatic deployment to GitHub Pages.

### Setup Instructions

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/slama-mostafa.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Under "Build and deployment":
     - Source: Select "GitHub Actions"
   - The workflow will automatically deploy on every push to main

3. **Access your site:**
   - Your site will be available at: `https://YOUR_USERNAME.github.io/slama-mostafa/`

### Manual Deployment

If you prefer manual deployment:

```bash
# Build the project
npm run build

# Deploy to GitHub Pages (using gh-pages package)
npm install -g gh-pages
gh-pages -d dist
```

## 📁 Project Structure

```
salma-portfolio/
├── public/              # Static assets
│   └── 404.html        # GitHub Pages fallback
├── src/
│   ├── assets/         # Images, styles
│   ├── components/     # Vue components
│   │   ├── layout/    # Layout components (Nav, Footer)
│   │   ├── sections/  # Page sections
│   │   └── ui/        # UI components
│   ├── composables/    # Vue composables
│   ├── data/          # Static data (projects, skills)
│   ├── router/        # Vue Router config
│   ├── views/         # Page views
│   ├── App.vue        # Root component
│   └── main.js        # Entry point
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Actions workflow
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

## 👨‍💻 Developer

**Mahmoud-Na**
- GitHub: [@mahmoudnazmy](https://github.com/mahmoudnazmy)
- Facebook: [Mahmoud](https://www.facebook.com/11mahmoud12)

## 🎨 Designer

**Salma Mostafa**
- LinkedIn: [Salma Mostafa](https://www.linkedin.com/in/salma-mostafa-347259305)
- Behance: [salmamostafamadany](https://www.behance.net/salmamostafamadany)
- Email: salmamostafamadany@gmail.com

## 📝 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- Icons by Lucide
- Fonts from Google Fonts

---

Made with 💙, Vue.js, and a lot of coffee ☕
