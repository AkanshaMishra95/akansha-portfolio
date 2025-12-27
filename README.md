# Akansha Mishra - HVAC & Chillers Professional Portfolio

A modern, professional portfolio website showcasing expertise in HVAC systems and chiller technology. The design features a cool blue industrial theme representing refrigeration and cooling systems.

## 🎨 Features

- **Professional HVAC Theme**: Cool blue color palette (#0066CC, #00A3E0, #4FC3F7) representing the cooling industry
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and interactive elements
- **Modern Design**: Clean, professional layout with gradient effects
- **Interactive Sections**:
  - Hero section with animated cooling system visualization
  - About section with professional overview
  - Timeline-based experience section
  - Skills showcase organized by categories
  - Projects portfolio with HVAC-related work
  - Contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Scroll to Top**: Quick navigation button
- **Form Validation**: Client-side validation for contact form

## 📁 Project Structure

```
akansha-portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # Comprehensive styling with HVAC theme
├── script.js           # Interactive JavaScript functionality
├── README.md           # This file
│
├── latest_resume/
│   └── 1_Resume-Akansha Mishra.pdf
│
└── pictures/           # Place your profile picture here
```

## 🚀 Getting Started

1. **Update Personal Information**:
   - Open `index.html`
   - Replace placeholder contact information with your actual details:
     - Email address
     - Phone number
     - Location
     - Social media links (LinkedIn, GitHub, Twitter)

2. **Add Your Content**:
   - Update the "About Me" section with your professional summary
   - Add your actual work experience in the Experience section
   - Customize the skills lists to match your expertise
   - Update projects with your real work
   - Add statistics numbers (years of experience, projects completed, etc.)

3. **Add Your Profile Picture**:
   - Place your profile picture in the `pictures/` folder
   - Update the image placeholder in the About section:
     ```html
     <div class="about-image">
         <img src="pictures/your-photo.jpg" alt="Akansha Mishra">
     </div>
     ```

4. **Open the Website**:
   - Simply open `index.html` in your web browser
   - Or use a local server for better performance:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js http-server
     npx http-server
     ```

## 🎨 Customization

### Colors
The color scheme is defined in CSS variables in `styles.css`:
```css
:root {
    --primary-color: #0066CC;      /* Primary blue */
    --secondary-color: #00A3E0;    /* Light blue */
    --accent-color: #4FC3F7;       /* Accent cyan */
    --dark-blue: #003B5C;          /* Dark blue */
    --ice-blue: #E8F4F8;           /* Light background */
}
```

### Fonts
Currently using system fonts. To use custom fonts:
1. Add Google Fonts link in `<head>` of `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

2. Update CSS:
```css
body {
    font-family: 'Poppins', sans-serif;
}
```

## 📱 Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: Below 768px

## 🔧 Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Animations)
- JavaScript (ES6+)
- Font Awesome 6.4.0 (Icons)

## 🌟 Key Sections

1. **Hero Section**: Eye-catching introduction with animated cooling system
2. **About**: Professional summary and statistics
3. **Experience**: Timeline of professional work history
4. **Skills**: Categorized technical expertise
5. **Projects**: Showcase of HVAC and chiller projects
6. **Contact**: Form and contact information

## 💡 Tips for Best Results

1. **High-Quality Images**: Use professional photos (minimum 1920x1080 for backgrounds)
2. **Consistent Content**: Keep descriptions concise and professional
3. **SEO**: Update the `<title>` and add meta descriptions
4. **Performance**: Compress images before adding them
5. **Testing**: Test on multiple devices and browsers

## 📝 To-Do (Customize Your Portfolio)

- [ ] Add your profile picture
- [ ] Update contact information (email, phone, location)
- [ ] Fill in work experience details
- [ ] Add real project descriptions
- [ ] Update social media links
- [ ] Add certifications and education
- [ ] Include actual statistics (years of experience, project counts)
- [ ] Consider adding a blog section
- [ ] Set up form backend (using services like Formspree, EmailJS, or custom backend)

## 🔐 Form Backend Setup (Optional)

To make the contact form functional, you can use:

### Option 1: Formspree
1. Sign up at [Formspree.io](https://formspree.io)
2. Get your form endpoint
3. Update the form action in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: EmailJS
1. Sign up at [EmailJS.com](https://www.emailjs.com)
2. Add EmailJS script to `index.html`
3. Update the form submission handler in `script.js`

## 🚀 Deployment

### GitHub Pages
1. Create a GitHub repository
2. Push your code
3. Go to Settings > Pages
4. Select branch to deploy
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop your folder to [Netlify](https://www.netlify.com)
2. Or connect your GitHub repository
3. Automatic deployment on every commit

## 📄 License

Feel free to use this template for your personal portfolio.

## 📧 Support

For questions or issues, please contact through the portfolio contact form.

---

**Made with ❄️ for HVAC Professionals**
