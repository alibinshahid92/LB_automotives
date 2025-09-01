# LB Automotives Website

A modern, responsive website for LB Automotives - a professional car recovery service based in East London.

## Features

- **Modern Design**: Clean blue and white professional automotive theme
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: CSS transitions and JavaScript animations for enhanced UX
- **Floating WhatsApp Button**: Easy contact via WhatsApp (bottom right corner)
- **Mobile Navigation**: Hamburger menu for small screens
- **Contact Form**: Functional contact form with validation
- **Professional Imagery**: High-quality automotive-themed images

## Sections

1. **Hero Section**: Eye-catching banner with call-to-action
2. **About Us**: Company introduction and mission statement
3. **Services**: 24/7 recovery, roadside assistance, vehicle transport
4. **Fleet**: Showcase of the Sprinter 514 dual wheel beaver tail truck
5. **Contact**: Contact form and business information
6. **Footer**: Additional links and contact details

## Setup Instructions

### Local Development
1. Clone or download the project files
2. Open `index.html` in a web browser
3. The website will load with all styles and functionality

### GitHub Pages Deployment
1. Create a new GitHub repository
2. Upload all files from the `LB_automotives` folder to the repository
3. Go to repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save" - your site will be published at `https://[username].github.io/[repository-name]`

### Customization

#### WhatsApp Number
Edit the WhatsApp link in `index.html`:
```html
<a href="https://wa.me/447123456789" class="whatsapp-float" target="_blank">
```
Replace `447123456789` with your actual WhatsApp number in international format (without spaces).

#### Contact Information
Update contact details in the Contact section and footer of `index.html`:
- Phone number
- Email address
- Service area details

#### Business Information
Modify the content in various sections to reflect your specific:
- Business hours
- Service descriptions
- Company information

## File Structure

```
LB_automotives/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript
- Font Awesome Icons
- Google Fonts (Roboto)
- Unsplash images (professional automotive photography)

## Customization Notes

- The website uses blue (#1e3a8a, #3b82f6) and white color scheme
- Yellow accent color (#fbbf24) for calls-to-action
- Responsive breakpoints at 768px and 480px
- All images are from Unsplash and can be replaced with your own photos

## License

This project is for LB Automotives business use. All rights reserved.

## Support

For technical support or customization questions, please contact your web developer.
