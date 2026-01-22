# Ali Baygi - Portfolio Website

Modern, responsive portfolio website showcasing AI/ML engineering and data science expertise.

## 🌟 Features

- **Modern Design**: Clean, professional interface inspired by contemporary web design
- **Multi-page Navigation**: Separate pages for Home, About, Skills, Projects, and Contact
- **Dark Mode**: Automatic dark mode with manual toggle
- **Responsive**: Fully mobile-responsive design
- **Fast Loading**: Optimized with Tailwind CSS via CDN
- **Interactive**: Smooth animations and transitions
- **Contact Form**: Integrated Formspree contact form

## 📄 Pages

1. **Home** - Hero section with value proposition and featured projects
2. **About** - Professional background, expertise, and certifications
3. **Skills** - Comprehensive technical skills organized by category
4. **Projects** - Detailed showcase of 5 recent GitHub projects
5. **Contact** - Contact form and professional links

## 🛠️ Technologies

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Formspree (for contact form)

## 🚀 Deployment to GitHub Pages

### Option 1: Deploy to your existing repo (alibaygi.github.io)

1. Clone your existing repository:
   ```bash
   git clone https://github.com/alibaygi/alibaygi.github.io.git
   cd alibaygi.github.io
   ```

2. Copy all files from this portfolio folder to the repository

3. Commit and push:
   ```bash
   git add .
   git commit -m "Update portfolio with modern design"
   git push origin main
   ```

4. Your site will be live at: `https://alibaygi.github.io`

### Option 2: Create a new repository

1. Create a new repository named `alibaygi.github.io` on GitHub

2. Initialize and push:
   ```bash
   cd /path/to/this/portfolio
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/alibaygi/alibaygi.github.io.git
   git push -u origin main
   ```

3. Enable GitHub Pages in repository settings (Settings → Pages → Source: main branch)

## 📝 Configuration

### Contact Form Setup

1. Go to [Formspree.io](https://formspree.io)
2. Sign up for a free account
3. Create a new form
4. Copy your form ID
5. Update `contact.html` line 188:
   ```html
   <form id="contactForm" action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
   ```
   Replace `YOUR_FORMSPREE_ID` with your actual Formspree form ID

### Customization

- **Profile Links**: Update GitHub and LinkedIn URLs in all HTML files
- **Email**: Add your actual email in `contact.html` if desired
- **Projects**: Update project details in `projects.html` as needed
- **Images**: Add profile photo in `images/` folder and update references

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📊 Structure

```
alibaygi_portfolio/
├── index.html          # Home page
├── about.html          # About page
├── skills.html         # Skills page
├── projects.html       # Projects page
├── contact.html        # Contact page
├── css/
│   └── custom.css     # Custom styles
├── js/
│   └── main.js        # JavaScript functionality
├── images/            # Images folder (add your photos here)
└── README.md          # This file
```

## 🎨 Color Scheme

- Primary: Blue (#2563eb)
- Secondary: Indigo (#1e40af)
- Accent: Purple/Green gradients for sections
- Dark mode: Automatic with system preference detection

## 📈 Performance

- Lighthouse Score: 95+ (expected)
- Mobile-friendly
- Fast loading with CDN resources
- Optimized animations

## 🔧 Local Development

Simply open `index.html` in your browser or use a local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve

# VS Code Live Server extension
```

Then navigate to `http://localhost:8000`

## 📄 License

This portfolio is open source. Feel free to use it as a template for your own portfolio.

## 🤝 Contributing

Suggestions and improvements are welcome!

---

**Built with ❤️ by Ali Baygi**
