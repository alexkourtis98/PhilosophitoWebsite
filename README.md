# Philosophito - Business Ethics Study Aid

> A comprehensive, free educational web application for students studying Business Ethics. Features interactive quizzes, searchable dictionary, and detailed explanations of moral theories and ethical issues.

[![Live Site](https://img.shields.io/badge/Live-philosophito.com-blue)](https://philosophito.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/username/PhilosophitoWebsite/pulls)

![Screenshot](./img/1.png)

## Overview

Philosophito is a static web application designed to help college students master Business Ethics concepts. Built with simplicity and performance in mind, it provides an intuitive interface for learning moral theories, exploring ethical issues, and testing knowledge through interactive quizzes.

**Live Demo:** [philosophito.com](https://philosophito.com)

## Features

### Educational Content
- **Moral Theories** - In-depth guides on Utilitarianism, Kantianism, and Virtue Ethics
- **Moral Issues** - Coverage of whistleblowing, CSR, affirmative action, discrimination, and more
- **Dictionary** - Searchable glossary of 100+ Business Ethics terms with source citations
- **Food for Thought** - Additional resources and case studies

### Interactive Learning
- **Quizzes** - Topic-based multiple-choice questions with instant feedback
- **Search & Filter** - Real-time keyword filtering across all content
- **Randomization** - Questions and answers shuffle for varied practice

### Modern Web Features
- **Progressive Web App (PWA)** - Installable on mobile and desktop
- **Responsive Design** - Optimized for all screen sizes
- **Fast Performance** - Production React builds, lazy loading, resource hints
- **SEO Optimized** - Rich meta tags, Open Graph, Twitter Cards, structured data
- **Accessibility** - Semantic HTML, ARIA labels, keyboard navigation

## Tech Stack

### Frontend
- **HTML5, CSS3, JavaScript (ES6+)**
- **React 18** (Production builds for performance)
- **Bootstrap 4** - UI framework
- **Tailwind CSS** - Utility-first styling
- **Babel Standalone** - JSX transformation

### Data
- **JSON** - Structured content storage
- **Client-side rendering** - No backend required

### Deployment
- **GitHub Pages** - Static hosting with custom domain
- **HTTPS** - Secure by default

## Project Structure

```
PhilosophitoWebsite/
├── index.html                 # Landing page
├── contact.html               # Contact information
├── privacy.html               # Privacy policy
├── manifest.json              # PWA manifest
├── robots.txt                 # Search engine directives
├── sitemap.xml                # SEO sitemap
├── _headers                   # Security headers
├── html/
│   ├── about.html            # About page
│   ├── quiz.html             # Interactive quiz
│   ├── dictionary.html       # Searchable glossary
│   ├── moraltheories.html    # Theories overview
│   ├── moralissues.html      # Ethical issues
│   ├── foodforthought.html   # Additional resources
│   └── theories/
│       ├── utilitarianism.html
│       └── kantianism.html
├── css/
│   ├── style.css             # Main styles
│   └── [font files]          # Lora typeface
├── img/                      # Images and icons
├── json/                     # Content data files
├── libs/                     # React & Babel (production builds)
├── main.css                  # Landing page styles
├── cookie.css & cookie.js    # Cookie consent
└── bootstrap4.min.*          # Bootstrap framework
```

## Performance Optimizations

### Implemented
- Production React builds (~2.7MB saved vs. development)
- Lazy loading for images
- Resource hints (preconnect, dns-prefetch)
- Font optimization with `font-display: swap`
- Minified CSS and JS
- Content Security Policy (CSP)
- Security headers (X-Frame-Options, X-Content-Type-Options, etc.)
- Caching strategies via _headers file

### SEO Enhancements
- Comprehensive meta tags (description, keywords, Open Graph, Twitter Cards)
- JSON-LD structured data (Website, Quiz, Article schemas)
- XML sitemap with all 11 pages
- robots.txt for crawler directives
- Canonical URLs on all pages
- Descriptive alt texts for images

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for development)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/PhilosophitoWebsite.git
   cd PhilosophitoWebsite
   ```

2. **Serve locally**

   Using Python:
   ```bash
   python -m http.server 8000
   ```

   Using Node.js:
   ```bash
   npx http-server
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### Deployment

The site is designed for static hosting (GitHub Pages, Netlify, Vercel, etc.):

1. Push to GitHub
2. Enable GitHub Pages in repository settings
3. Set custom domain (optional)
4. Configure _headers file for security

## Contributing

Contributions are welcome! Whether it's:
- Bug reports
- Feature requests
- Content improvements
- Code optimizations

Please feel free to open an issue or submit a pull request.

### Development Guidelines
- Maintain simple, static architecture
- Follow existing code style
- Test on multiple browsers
- Ensure mobile responsiveness
- Add alt texts to all images
- Update documentation

## Roadmap

- [ ] Add Virtue Ethics detailed page
- [ ] Implement service worker for offline support
- [ ] Generate proper PWA icons (192x192, 512x512)
- [ ] Add more quiz questions
- [ ] Implement user progress tracking (localStorage)
- [ ] Dark mode toggle
- [ ] Multiple language support

## Sources & Acknowledgments

Content is summarized from:
- Boatright, J. R., & Smith, J. (2016). *Ethics and the Conduct of Business* (8th Edition). Pearson.
- Wikipedia.org
- Various academic sources (cited in-app)

Tools & Frameworks:
- React, Bootstrap, Tailwind CSS
- Font Awesome, Google Fonts
- GitHub Pages

Supported by:
- [Cyber Club](https://dccyberclub.com)
- [SASS - Student Academic Support Services](https://www.acg.edu/undergraduate/academic-enrichment-programs/student-academic-support-services/)

## Privacy

**No data is collected** - neither in the Android app nor the website. Your privacy is our priority.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

**Alexandros Kourtis**
- Email: [alexandros.kourtis@acg.edu](mailto:alexandros.kourtis@acg.edu)
- Phone: +306989442438
- Website: [alexkourtis.me](https://alexkourtis.me)

## Showcase

Perfect for portfolios! This project demonstrates:
- Clean, maintainable code architecture
- Modern web performance techniques
- SEO best practices
- PWA implementation
- Responsive design
- Security hardening
- Educational content organization

---

Made with dedication by Alexandros Kourtis | [philosophito.com](https://philosophito.com)
