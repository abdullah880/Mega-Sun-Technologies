# Mega Sun Technologies - Solar Energy Website

A comprehensive, modern website for a solar energy company built with HTML, Tailwind CSS, and vanilla JavaScript. This multi-page website showcases solar solutions for residential and commercial customers with an emphasis on trust, transparency, and local expertise.

## 🌟 Features

### Core Pages
- **Home (index.html)** - Landing page with hero section, trust signals, and clear CTAs
- **Solutions (solutions.html)** - Residential solar solutions with system comparisons
- **Commercial (commercial.html)** - Commercial solar offerings with ROI calculator
- **How It Works (how-it-works.html)** - Educational content explaining solar technology
- **Our Projects (our-projects.html)** - Portfolio with filterable project gallery and case studies
- **Why Choose Us (why-choose-us.html)** - Trust-building content highlighting local advantages
- **FAQs (FAQs.html)** - Comprehensive FAQ section with search functionality
- **Contact (contact.html)** - Multi-step contact form for site surveys

### Key Features
- **Responsive Design** - Mobile-first approach with full tablet and desktop optimization
- **Interactive Elements** - Dynamic forms, calculators, modals, and animations
- **ROI Calculator** - Interactive tool for estimating solar savings
- **Project Filter** - Filter projects by residential, commercial, or agricultural
- **FAQ Search** - Real-time search through frequently asked questions
- **Multi-Step Forms** - Progressive form completion with validation
- **Smooth Animations** - Fade-in, slide-in, and scroll-triggered animations
- **Modern UI/UX** - Clean, professional design with consistent branding

## 🎨 Design System

### Color Palette
```css
primary: #0B3C5D (Deep Blue)
secondary: #F4B400 (Golden Yellow)
accent: #2E7D32 (Green)
background: #F7F9FC (Light Blue-Gray)
surface: #FFFFFF (White)
textPrimary: #1F2933 (Dark Gray)
textSecondary: #4B5563 (Medium Gray)
border: #E5E7EB (Light Gray)
```

### Typography
- **Font Family**: Poppins (weights: 300, 400, 500, 600, 700)
- **Headings**: Bold, primary color
- **Body Text**: Regular, secondary text color
- **CTAs**: Bold, high contrast

### UI Components
- **Sticky Navigation** - Frosted glass effect with blur backdrop
- **Cards** - Elevated surfaces with hover effects
- **Buttons** - Primary (secondary color), Secondary (primary color), Ghost variants
- **Forms** - Clean inputs with focus states and validation
- **Icons** - Font Awesome 6.4.0 for consistent iconography

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS 3.x** - Utility-first CSS framework (CDN)
- **Vanilla JavaScript** - No frameworks, pure ES6+
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts** - Poppins font family

## 📁 Project Structure

```
/
├── index.html              # Home page
├── solutions.html          # Residential solutions
├── commercial.html         # Commercial solutions
├── how-it-works.html      # Educational content
├── our-projects.html      # Project portfolio
├── why-choose-us.html     # Trust & credibility
├── FAQs.html              # FAQ section
├── contact.html           # Contact form
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required
- No dependencies to install

### Installation

1. **Clone or download** the repository:
```bash
git clone https://github.com/yourusername/mega-sun-technologies.git
```

2. **Navigate** to the project directory:
```bash
cd mega-sun-technologies
```

3. **Open** any HTML file in your browser:
   - Double-click any `.html` file, or
   - Use a local server (recommended):

**Using Python:**
```bash
python -m http.server 8000
```
Then visit: `http://localhost:8000`

**Using Node.js:**
```bash
npx http-server
```

**Using VS Code:**
- Install "Live Server" extension
- Right-click any HTML file → "Open with Live Server"

## 📱 Responsive Breakpoints

```css
Mobile: < 768px
Tablet: 768px - 1024px
Desktop: > 1024px
```

All pages are fully responsive with:
- Mobile-first design approach
- Collapsible navigation menu
- Stacked layouts on mobile
- Grid layouts on desktop

## 🎯 Key Interactions

### Navigation
- **Desktop**: Horizontal menu with hover effects
- **Mobile**: Hamburger menu with slide-down animation
- **Sticky**: Remains visible on scroll with blur effect

### Forms
- **Real-time validation** - Input validation on blur
- **Multi-step progression** - Visual indicators for form steps
- **Success messages** - Confirmation after submission
- **Error handling** - Clear error messages

### Calculators
- **ROI Calculator** (commercial.html) - Interactive savings estimator
- **Range sliders** - Smooth, animated updates
- **Dynamic results** - Real-time calculation updates

### Project Gallery
- **Filter by category** - Residential, Commercial, Agricultural
- **Modal details** - Click to view full project information
- **Smooth transitions** - Fade animations

### FAQ Section
- **Accordion UI** - Click to expand/collapse answers
- **Search functionality** - Real-time filtering
- **Highlight matches** - Search terms highlighted in results

## 🔧 Customization

### Changing Colors
Update the Tailwind config in each HTML file's `<script>` tag:

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: "#YourColor",
        secondary: "#YourColor",
        // ... etc
      }
    }
  }
}
```

### Adding New Pages
1. Copy an existing HTML file as a template
2. Update the navigation links in the header
3. Update the footer links
4. Add page-specific content and styles

### Modifying Forms
Forms use standard HTML5 validation. To customize:
1. Update `<form>` elements with new fields
2. Add validation attributes (`required`, `type`, `pattern`)
3. Update JavaScript handlers in `<script>` tags

## 📊 Performance Optimization

- **CDN Resources** - Tailwind and Font Awesome loaded from CDN
- **Lazy Loading** - Animations trigger on scroll into view
- **Minimal JavaScript** - No heavy frameworks
- **Optimized Images** - Gradient backgrounds instead of images
- **CSS Animations** - Hardware-accelerated transforms

## 🔐 Security Features

- **Form Validation** - Client-side input sanitization
- **No External Dependencies** - All code is local
- **Safe Links** - External links open in new tabs
- **HTTPS Ready** - No mixed content issues

## ♿ Accessibility

- **Semantic HTML** - Proper heading hierarchy
- **ARIA Labels** - Screen reader support
- **Keyboard Navigation** - Full keyboard accessibility
- **Focus Indicators** - Visible focus states
- **Color Contrast** - WCAG AA compliant

## 🌐 Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Future Enhancements

Potential additions:
- [ ] Backend integration for form submissions
- [ ] CMS integration for content management
- [ ] Blog section for solar energy articles
- [ ] Customer portal for system monitoring
- [ ] Live chat integration
- [ ] Multi-language support
- [ ] Advanced analytics integration
- [ ] Solar panel visualizer tool

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Credits

- **Design & Development**: [Your Name/Company]
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Poppins)
- **CSS Framework**: Tailwind CSS

## 📞 Support

For questions or support:
- Email: info@megasuntechnologies.com
- Phone: (555) 123-SOLAR
- Website: megasuntechnologies.com

## 🐛 Known Issues

- None currently reported

## 📋 Changelog

### Version 1.0.0 (Initial Release)
- Complete website with 8 pages
- Responsive design for all devices
- Interactive calculators and forms
- Project portfolio with filtering
- FAQ section with search
- Contact forms with multi-step progression

---

**Built with ☀️ by Mega Sun Technologies**
