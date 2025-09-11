# Safe Skills - Website

A professional website for Safe Skills, a consulting and training company specializing in strategy, security, performance, crisis management, and strategic intelligence.

## 🏢 About Safe Skills

Safe Skills is a consulting firm that operates on two complementary fronts:
- **Training**: Practical programs, conferences, and immersive exercises to strengthen resilience, competitiveness, and performance
- **Strategic Consulting**: Strategic analysis, due diligence, risk studies, and comprehensive security approach

## 🚀 Features

- **Responsive Design**: Mobile-first approach with Bootstrap 5
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Multi-language Support**: French content with proper internationalization
- **Contact Form**: PHP-powered contact form with email validation
- **Interactive Elements**: 
  - Swiper carousels for client logos
  - AOS (Animate On Scroll) animations
  - Bootstrap modals for team member details
  - Smooth scrolling navigation
- **SEO Optimized**: Semantic HTML structure and meta tags
- **Performance**: Optimized images (WebP format) and minified assets

## 📁 Project Structure

```
safe-skills/
├── assets/
│   ├── css/
│   │   └── main.css              # Main stylesheet with custom CSS variables
│   ├── img/                      # All images and media files
│   │   ├── blog/                 # Blog post images
│   │   ├── clients/              # Client logos
│   │   ├── person/               # Team member photos
│   │   ├── steps/                # Service domain images
│   │   ├── SafeSkillsLogo.png    # Company logo
│   │   └── safe-hero.webp        # Hero section image
│   ├── js/
│   │   └── main.js               # Main JavaScript functionality
│   └── vendor/                   # Third-party libraries
│       ├── bootstrap/            # Bootstrap 5 framework
│       ├── aos/                  # Animate On Scroll library
│       ├── swiper/               # Touch slider library
│       ├── glightbox/            # Lightbox for images
│       └── php-email-form/       # Contact form handler
├── forms/
│   ├── contact.php               # Contact form processor
│   └── newsletter.php            # Newsletter subscription handler
├── pages/                        # Additional pages
│   ├── 404.html                  # Error page
│   ├── blog.html                 # Blog listing page
│   ├── blog-details.html         # Individual blog post
│   ├── service-details.html      # Service detail page
│   └── portfolio-details.html    # Portfolio item detail
├── index.html                    # Main homepage
└── README.md                     # This file
```

## 🎨 Design System

### Color Palette
- **Primary**: `#fc7c28` (Orange)
- **Secondary**: `#253355` (Dark Blue)
- **Accent**: `#2ec4b6` (Teal)
- **Background**: `#f7f7fa` (Light Gray)
- **Text Dark**: `#253355`
- **Text Light**: `#fff`

### Typography
- **Headings**: Jost (Google Fonts)
- **Body Text**: Open Sans (Google Fonts)
- **Navigation**: Poppins (Google Fonts)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Flexbox, Grid
- **Bootstrap 5**: Responsive framework
- **JavaScript (ES6+)**: Modern JavaScript features
- **PHP**: Server-side form processing
- **Libraries**:
  - AOS (Animate On Scroll)
  - Swiper.js (Touch slider)
  - GLightbox (Image lightbox)
  - Bootstrap Icons

## 📱 Sections

1. **Hero Section**: Company introduction with call-to-action
2. **Clients Section**: Client logos carousel
3. **About Section**: Company overview and mission
4. **Story Section**: Company history and founder background
5. **Values Section**: Core company values with interactive FAQ
6. **Services Section**: Two main service categories:
   - Professional Training
   - Strategic Consulting
7. **Domains Section**: Areas of intervention (Industry, Defense & Security, Energy, etc.)
8. **Call-to-Action**: WhatsApp contact integration
9. **Team Section**: Team member profiles with detailed modals
10. **Blog Section**: Latest articles and insights
11. **Contact Section**: Contact form and company information

## 🚀 Getting Started

### Prerequisites
- Web server (Apache/Nginx) with PHP support
- Modern web browser

### Installation

1. **Clone or download** the project files
2. **Upload** to your web server
3. **Configure** the contact form:
   - Edit `forms/contact.php`
   - Update the `$receiving_email_address` variable
   - Optionally configure SMTP settings
4. **Test** the contact form functionality
5. **Customize** content, images, and styling as needed

### Local Development

For local development, you can use:
- **XAMPP/WAMP/MAMP**: For PHP support
- **Live Server**: For static file serving
- **VS Code Live Server Extension**: Simple local development

## 📧 Contact Form Configuration

The contact form is configured to send emails to `contact@safeskills.ma`. To customize:

1. Edit `forms/contact.php`
2. Change the `$receiving_email_address` variable
3. For SMTP configuration, uncomment and modify the SMTP settings

## 🎯 Key Features

### Responsive Design
- Mobile-first approach
- Bootstrap 5 grid system
- Optimized for all device sizes

### Performance
- WebP image format for better compression
- Minified CSS and JavaScript
- Optimized loading with lazy loading

### Accessibility
- Semantic HTML structure
- Proper alt tags for images
- Keyboard navigation support
- ARIA labels where appropriate

### SEO
- Meta tags and descriptions
- Structured data markup
- Clean URL structure
- Fast loading times

## 🔧 Customization

### Colors
Edit the CSS custom properties in `assets/css/main.css`:
```css
:root {
  --primary: #fc7c28;
  --secondary: #253355;
  --accent: #2ec4b6;
  /* ... other colors */
}
```

### Content
- Update company information in `index.html`
- Replace images in `assets/img/`
- Modify team member details in the modals
- Update contact information

### Styling
- Main styles in `assets/css/main.css`
- Bootstrap customization through CSS variables
- Component-specific styles for unique elements

## 📞 Contact Information

- **Address**: 4 Rue Ouargha, Agdal 10080 Rabat, Maroc
- **Phone**: +212 661 227 722
- **Email**: contact@safeskills.ma
- **WhatsApp**: +212 645 994 904

## 👥 Team

- **Nizar Derdabi**: Founder - Former Royal Gendarmerie officer, expert in intelligence and judicial investigations
- **Abdellah Bouraki**: Security and Investigations Expert - Former Royal Gendarmerie cadre with expertise in security and specialized investigations

## 📄 License

This project is proprietary to Safe Skills. All rights reserved.

## 🏗️ Development

**Designed by**: [EAF microservice](https://fouadeaf.github.io/EAF-microservice/)

---

*For technical support or customization requests, please contact the development team.*
