# Sapna Kumari - Portfolio Website

A modern, responsive portfolio website for Sapna Kumari, an aspiring Marketing & Sales Professional.

## Features

- **Fully Responsive** - Works on all devices (desktop, tablet, mobile)
- **Modern UI/UX** - Clean and professional design with smooth animations
- **Sections**
  - Hero section with call-to-action buttons
  - About section with personal information
  - Education timeline
  - Work experience
  - Skills with progress bars
  - Services offered
  - Portfolio/Projects gallery
  - Testimonials
  - Contact form
  - Footer with social links

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Poppins & Playfair Display)

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- (Optional) A local web server for development

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sapna-portfolio.git
   cd sapna-portfolio
   ```

2. Open `index.html` in your web browser.

## Customization

### Changing Profile Information

Edit the `index.html` file to update:
- Personal information in the About section
- Education details
- Work experience
- Skills and proficiency levels
- Portfolio projects
- Contact information

### Changing Colors and Styling

Edit the CSS variables in the `:root` selector at the top of the `css/styles.css` file to change the color scheme:

```css
:root {
    --primary-color: #8A4FFF;
    --secondary-color: #FF6B9C;
    --accent-color: #4FC3F7;
    --text-dark: #333333;
    --text-light: #666666;
    --light-bg: #F9F7FE;
    --white: #FFFFFF;
    /* ... other variables ... */
}
```

### Adding Portfolio Items

To add a new portfolio item, copy and paste the following HTML structure inside the `.portfolio-grid` div:

```html
<div class="portfolio-item" data-category="design">
    <div class="portfolio-img">
        <img src="assets/portfolio/your-image.jpg" alt="Project Title">
        <div class="portfolio-overlay">
            <div class="portfolio-links">
                <a href="#" class="portfolio-link" title="View Project">
                    <i class="fas fa-link"></i>
                </a>
                <a href="assets/portfolio/your-image.jpg" class="portfolio-preview" data-lightbox="portfolio" title="Project Title">
                    <i class="fas fa-search"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="portfolio-info">
        <h3>Project Title</h3>
        <p>Project Category</p>
        <span class="portfolio-tag">Tag</span>
    </div>
</div>
```

## Adding Your Own Images

1. Place your profile picture in the `assets` folder as `profile-pic.jpg`
2. Add portfolio project images to the `assets/portfolio` folder
3. Update the image paths in the HTML file accordingly

## Browser Support

This website is built to work on all modern browsers including:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For any questions or feedback, please contact [Your Email].

---

*This portfolio template was created with ❤️ by [Your Name].*
