# Vishwajeet S. R. K. - Personal Portfolio Website

A modern, interactive, and fully responsive personal portfolio website showcasing the professional journey, skills, and projects of Vishwajeet S. R. K., a data-driven professional and full-stack web development enthusiast from Bengaluru.

## 🌟 Overview

This portfolio website features a sleek, professional design with engaging animations, smooth scrolling, and interactive elements that highlight expertise in:
- Data Analytics & Management
- AI-Driven Automation
- Full-Stack Web Development
- Creative Multimedia & Design

## ✨ Features

### Design & User Experience
- **Modern, Minimalistic Layout**: Clean design with professional aesthetics
- **Dark/Light Mode Toggle**: User preference-based theme switching with localStorage persistence
- **Smooth Scrolling**: Seamless navigation between sections
- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Interactive Animations**: Scroll-triggered animations and hover effects
- **Particle.js Background**: Animated particle system in the hero section

### Portfolio Sections

1. **Hero Section**
   - Full-screen introduction with animated particle background
   - Professional tagline and call-to-action buttons
   - Social media links (LinkedIn, GitHub, Email)
   - Animated scroll indicator

2. **About Me**
   - Professional summary with key highlights
   - Interactive statistics (records processed, years of experience, skills)
   - Contact information display
   - Professional avatar placeholder

3. **Skills**
   - Categorized skill display (5 categories)
   - Interactive progress bars with animation on scroll
   - Icon-based visual representation
   - Categories include:
     - Web Development & Programming
     - Data & Analytics
     - AI & Automation
     - Creative & Multimedia
     - Soft Skills

4. **Experience**
   - Interactive timeline layout
   - 5 professional positions with detailed achievements
   - Hover effects on timeline items
   - Technology tags for each role
   - Visual timeline with gradient connector

5. **Projects**
   - 6 featured projects in card layout
   - Hover overlays with project links
   - Technology stack badges
   - Impact metrics for each project
   - Links to live demos and GitHub repositories

6. **Education & Certifications**
   - Split grid layout for education and certifications
   - Animated cards with icons
   - Detailed descriptions of degrees and certificates
   - Institution and duration information

7. **Contact**
   - Interactive contact form with validation
   - Contact information cards
   - Social media links
   - Form success message animation
   - Direct links for phone, email, and LinkedIn

8. **Footer**
   - Quick navigation links
   - Social media connections
   - Copyright information
   - Professional branding

### Interactive Features

- **Smooth Scroll Navigation**: Click any navigation link for smooth scrolling
- **Active Nav Link Indicator**: Highlights current section in navigation
- **Skill Bar Animations**: Progress bars animate when scrolled into view
- **Form Validation**: Real-time validation for contact form
- **Mobile Menu**: Hamburger menu for mobile devices
- **Scroll-to-Top Button**: Appears after scrolling down
- **Counter Animations**: Statistics animate when visible
- **Theme Persistence**: Remembers user's theme preference

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Interactive functionality and animations

### Libraries & Frameworks
- **Font Awesome 6.4.0**: Icon library
- **Google Fonts**: Poppins & Inter font families
- **Chart.js**: Data visualization capability
- **Particles.js 2.0.0**: Animated particle background

### Design Principles
- **Mobile-First Approach**: Responsive design starting from mobile
- **Accessibility**: ARIA labels and semantic HTML
- **Performance Optimization**: Lazy loading, debouncing, and throttling
- **Cross-Browser Compatibility**: Works on all modern browsers

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file with all sections
├── css/
│   └── style.css          # Complete styling with animations and themes
├── js/
│   └── main.js            # JavaScript functionality and interactions
└── README.md              # Project documentation
```

## 🎨 Color Palette

### Light Mode
- Primary: `#1e40af` (Dark Blue)
- Secondary: `#10b981` (Vibrant Green)
- Accent: `#f59e0b` (Gold)
- Background: `#ffffff` (White)
- Text: `#1f2937` (Dark Gray)

### Dark Mode
- Primary: `#3b82f6` (Bright Blue)
- Secondary: `#10b981` (Vibrant Green)
- Accent: `#fbbf24` (Gold)
- Background: `#111827` (Dark)
- Text: `#f9fafb` (Light Gray)

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required - runs as a static website

### Installation

1. **Clone or Download**: Get the project files
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **View Portfolio**: Navigate through sections using the menu or scroll

### Deployment

This is a static website and can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 320px - 767px

## ⚙️ Customization

### Update Personal Information

1. **Contact Details**: Edit the contact section in `index.html`
2. **Skills**: Modify skill items and progress percentages
3. **Projects**: Update project cards with your own projects
4. **Experience**: Add or remove timeline items
5. **Social Links**: Update href attributes with your URLs

### Theme Customization

Edit CSS variables in `css/style.css`:
```css
:root {
    --primary-color: #1e40af;
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* Modify other variables */
}
```

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📊 Performance Features

- **Intersection Observer API**: Efficient scroll animations
- **Debouncing & Throttling**: Optimized scroll event handling
- **CSS Transitions**: Hardware-accelerated animations
- **Lazy Loading**: Images loaded on demand
- **Local Storage**: Theme preference caching

## 🔧 JavaScript Functions

### Core Functions
- `initializeTheme()`: Dark/light mode toggle
- `initializeNavigation()`: Active link tracking
- `initializeParticles()`: Particle background setup
- `initializeScrollAnimations()`: Scroll-triggered animations
- `initializeSkillBars()`: Skill progress animations
- `initializeContactForm()`: Form validation and submission
- `initializeSmoothScroll()`: Smooth scrolling behavior
- `initializeMobileMenu()`: Mobile navigation menu

### Utility Functions
- `debounce()`: Performance optimization
- `throttle()`: Event handler optimization
- `animateCounter()`: Number counter animations
- `typeWriter()`: Text typing effect

## 📈 Features Implemented

✅ Responsive design for all devices  
✅ Dark/light mode with persistence  
✅ Smooth scrolling navigation  
✅ Animated skill progress bars  
✅ Interactive timeline for experience  
✅ Project showcase with hover effects  
✅ Contact form with validation  
✅ Particle.js animated background  
✅ Mobile-friendly hamburger menu  
✅ Scroll-to-top button  
✅ Active navigation highlighting  
✅ Counter animations for statistics  
✅ Cross-browser compatibility  

## 🎯 Future Enhancements

- [ ] Add blog section for articles
- [ ] Integrate with backend for contact form submissions
- [ ] Add testimonials section
- [ ] Implement project filtering system
- [ ] Add more animation effects
- [ ] Create downloadable CV/Resume feature
- [ ] Add language switcher (English/Hindi)
- [ ] Implement analytics tracking
- [ ] Add loading animations/preloader
- [ ] Create case study pages for projects

## 📞 Contact Information

- **Name**: Vishwajeet S. R. K.
- **Location**: Bengaluru, Karnataka, India
- **Phone**: +91 8595202922
- **Email**: vishwajeetsrk@gmail.com
- **LinkedIn**: [linkedin.com/in/vishwajeetsrk](https://www.linkedin.com/in/vishwajeetsrk)

## 🎓 Professional Focus

**Open to opportunities in:**
- Data Management
- AI-Driven Automation
- Full-Stack Development
- Technology Innovation

## 📄 License

This project is open for personal and educational use. Feel free to use it as a template for your own portfolio.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Particles.js for animated background
- Chart.js for data visualization capabilities

## 📝 Notes

- All project links are placeholder examples - update with actual URLs
- GitHub profile link should be updated with actual username
- Contact form currently shows success message locally - integrate with backend for actual email functionality
- Replace placeholder icons with actual project screenshots when available

---

**Built with ❤️ by Vishwajeet S. R. K.**

*Last Updated: December 2024*