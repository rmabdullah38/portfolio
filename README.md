# John Doe - Professional Resume Website

A modern, responsive personal resume website built with HTML, CSS, and JavaScript. Features a beautiful green and gold design with smooth animations and interactive elements.

## 🌟 Features

### Design & Layout
- **Modern Green & Gold Theme**: Professional color scheme with green (#2d5a27, #4a7c59) and gold (#d4af37) accents
- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Smooth Animations**: CSS transitions and JavaScript animations for enhanced user experience
- **Professional Typography**: Clean, readable fonts using Google Fonts (Poppins)

### Pages
1. **Homepage** (`index.html`)
   - Hero section with introduction
   - Quick statistics overview
   - Featured skills preview
   - Call-to-action buttons

2. **About Page** (`about.html`)
   - Personal information and bio
   - Work experience timeline
   - Education and certifications
   - Professional background

3. **Skills Page** (`skills.html`)
   - Technical skills with progress bars
   - Frontend and backend technologies
   - Tools and technologies
   - Soft skills showcase

4. **Projects Page** (`projects.html`)
   - Featured projects with detailed descriptions
   - Project filtering by category
   - Technology tags and statistics
   - Interactive project cards

5. **Contact Page** (`contact.html`)
   - Contact form with validation
   - Multiple contact methods
   - FAQ section with accordion
   - Social media links

### Interactive Features
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Project Filtering**: Filter projects by category (Web, Mobile, E-commerce, API)
- **FAQ Accordion**: Expandable FAQ sections
- **Contact Form**: Form validation and submission handling
- **Smooth Scrolling**: Smooth navigation between sections
- **Skill Animations**: Animated progress bars for skills
- **Notification System**: Success/error notifications for form submissions

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software required - runs entirely in the browser

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Navigate through the different pages using the navigation menu

### File Structure
```
resume-website/
├── index.html          # Homepage
├── about.html          # About page
├── skills.html         # Skills page
├── projects.html       # Projects page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Customization

### Colors
The color scheme is defined using CSS custom properties in `styles.css`:
```css
:root {
    --primary-green: #2d5a27;
    --secondary-green: #4a7c59;
    --light-green: #7fb069;
    --gold: #d4af37;
    --light-gold: #f4e4a6;
    --dark-gold: #b8860b;
    --white: #ffffff;
    --light-gray: #f8f9fa;
    --dark-gray: #333333;
    --text-gray: #666666;
}
```

### Content
- Update personal information in each HTML file
- Replace placeholder images with actual photos
- Modify project details and descriptions
- Update contact information and social media links

### Adding New Projects
To add a new project, copy the project card structure in `projects.html`:
```html
<div class="project-card" data-category="web">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-icon-name"></i>
        </div>
        <div class="project-overlay">
            <div class="project-links">
                <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i></a>
                <a href="#" class="project-link"><i class="fab fa-github"></i></a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
    </div>
</div>
```

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

### Mobile Features
- Collapsible navigation menu
- Optimized layouts for small screens
- Touch-friendly interactive elements
- Readable typography on all devices

## 🔧 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons and visual elements
- **Google Fonts**: Typography (Poppins)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

For questions or support, please contact:
- Email: john.doe@email.com
- Phone: +1 (555) 123-4567

## 🚀 Deployment

To deploy this website:
1. Upload all files to your web hosting service
2. Ensure all files are in the same directory
3. Access via your domain name

### Recommended Hosting Options
- GitHub Pages (free)
- Netlify (free tier available)
- Vercel (free tier available)
- Traditional web hosting services

---

**Note**: This is a template using "John Doe" as placeholder content. Please replace all personal information, images, and content with your own before using as your resume website. 