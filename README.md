# Erasmus Mundus Portfolio Website

A modern, responsive portfolio website designed specifically for Erasmus Mundus scholars and researchers. Built with clean HTML, CSS, and JavaScript.

## 🌟 Features

- **Responsive Design**: Looks great on all devices
- **Modern Animations**: Smooth scrolling, hover effects, and scroll reveal animations
- **Professional Sections**: About, Education, Research, Experience, Skills, and Contact
- **CV Download**: Direct download functionality for your CV
- **Contact Form**: Functional contact form with validation
- **Social Media Integration**: Links to all your professional profiles
- **SEO Optimized**: Clean, semantic HTML structure

## 🚀 Quick Setup

### 1. Fork or Download
- Fork this repository or download the files
- Create a new repository named `your-username.github.io` for your main GitHub Pages site

### 2. File Structure
```
your-portfolio/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
├── assets/
│   ├── cv/
│   │   └── YourName_CV.pdf
│   └── images/
│       └── profile.jpg
└── README.md
```

### 3. Customize Your Content

#### Update Personal Information
Replace all placeholder text in `index.html`:
- `[Your Name]` → Your actual name
- `[Your Field]` → Your field of study
- `[Your Research Area]` → Your research specialization
- `[University 1]`, `[University 2]` → Your Erasmus Mundus universities
- All other bracketed placeholders with your information

#### Add Your Photos and CV
1. Add your profile photo to `assets/images/profile.jpg`
2. Add your CV PDF to `assets/cv/YourName_CV.pdf`
3. Update the CV filename in the download button (line 47 in index.html)

#### Update Contact Information
- Email address
- Phone number
- Location
- LinkedIn profile
- ORCID ID
- Social media links

### 4. GitHub Pages Setup

1. **Push to GitHub**: Upload all files to your repository
2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

Your site will be live at: `https://your-username.github.io`

## 🎨 Customization

### Colors
The website uses a purple gradient theme. To change colors, update these CSS variables in `styles.css`:
- Primary gradient: `#667eea` to `#764ba2`
- Accent color: `#ff6b6b` to `#ee5a24`
- Success color: `#28a745` to `#20c997`

### Sections
You can easily add, remove, or reorder sections by:
1. Adding/removing HTML sections in `index.html`
2. Adding corresponding navigation links
3. Updating the smooth scroll functionality in `script.js`

### Animations
The website includes several animations:
- Scroll reveal effects
- Hover animations
- Smooth scrolling
- Form validation feedback
- Mobile menu transitions

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- Mobile-friendly navigation menu
- Optimized layouts for tablets and phones
- Touch-friendly button sizes
- Readable typography on all screen sizes

## 🛠 Technical Features

### HTML5
- Semantic markup
- Accessibility features (aria-labels, proper heading structure)
- Meta tags for SEO
- Open Graph tags for social sharing

### CSS3
- CSS Grid and Flexbox for layouts
- CSS custom properties (variables)
- Advanced animations and transitions
- Mobile-first responsive design

### JavaScript
- ES6+ features
- Modular code organization
- Form validation
- Intersection Observer API for scroll effects
- Debounced scroll events for performance

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Success/error notifications
- Responsive design
- Accessible form labels

**Note**: The form currently shows a success message but doesn't send emails. To make it functional, you can:
- Use Formspree, Netlify Forms, or similar services
- Integrate with your preferred backend solution
- Use mailto: links as a simple alternative

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 SEO & Performance

- Optimized images
- Minified CSS and JavaScript (you can further minify for production)
- Semantic HTML structure
- Fast loading times
- Mobile-friendly design

## 🤝 Contributing

Feel free to submit issues and pull requests to improve this template!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎓 Perfect for Erasmus Mundus Scholars

This template is specifically designed for:
- Master's and PhD students
- International researchers
- Academic professionals
- Erasmus Mundus alumni and current students

---

**Made with ❤️ for the Erasmus Mundus community**

### 📞 Support

If you need help customizing your portfolio:
1. Check the code comments for guidance
2. Search existing GitHub issues
3. Create a new issue with your question

Good luck with your academic journey! 🎓✨