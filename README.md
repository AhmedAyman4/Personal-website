# Ahmed Ayman's Portfolio Website

A modern, responsive personal portfolio website for Ahmed Ayman, highlighting his skills, projects, and experience as a Data Scientist, ML Engineer, and Python Developer.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Dark/Light Mode**: Toggle between dark and light themes
- **Animated Sections**: Smooth scroll reveal animations
- **Dynamic Typing Effect**: Animated text showcasing professional titles
- **Interactive Navigation**: Smooth scrolling to different sections
- **Project Showcase**: Highlighted portfolio projects with GitHub links
- **Contact Form**: Integrated contact form for visitor inquiries
- **Social Media Links**: Easy access to professional social profiles
- **PDF Resume**: Downloadable CV option

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **JavaScript**: Interactivity and animations
- **ScrollReveal.js**: Scroll animations
- **Typed.js**: Text typing animation effect
- **Unicons**: Icon library

## Project Structure

```
ahmed-portfolio/
│
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   ├── js/
│   │   └── main.js        # JavaScript functionality
│   └── images/
│       ├── ME1.jpg        # Profile image
│       ├── 2.png          # Favicon
│       └── Ahmed Ayman Resume.pdf  # Downloadable CV
│
└── README.md              # Project documentation
```

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ahmed-portfolio.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ahmed-portfolio
   ```

3. Open `index.html` in your browser to view the website locally.

## Customization

### Personal Information

Update personal details in `index.html`:
- Name, profession, and bio in the featured box section
- Contact information in the contact section
- Social media links throughout the document

### Projects

Modify the projects section in `index.html` to showcase your own work:
```html
<div class="project-box" onclick="window.open('your-project-url', '_blank');">
  <i class="uil uil-icon-name"></i>
  <h3>Project Title</h3>
  <label>Technologies Used</label>
</div>
```

### Theme Colors

Customize the color scheme in `assets/css/style.css` by changing the CSS variables:
```css
:root {
  --body-color: rgb(250, 250, 250);
  --color-white: rgb(255, 255, 255);
  --text-color-second: rgb(68, 68, 68);
  --text-color-third: rgb(30, 159, 171);
  --first-color: rgb(110, 87, 224);
  --first-color-hover: rgb(40, 91, 212);
  --second-color: rgb(0, 201, 255);
  --third-color: rgb(192, 166, 49);
  --first-shadow-color: rgba(0, 0, 0, 0.1);
}
```

### Typing Effect

Change the typing effect text in `assets/js/main.js`:
```javascript
var typingEffect = new Typed(".typedText", {
  strings: ["Your", "Custom", "Titles"],
  loop: true,
  typeSpeed: 100,
  backSpeed: 80,
  backDelay: 2000,
});
```

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Deployment

To deploy the website:

1. Purchase a domain (optional)
2. Upload files to your web hosting service via FTP
3. Or deploy to GitHub Pages, Netlify, or Vercel for free hosting

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- [Unicons](https://iconscout.com/unicons) for icons
- [Typed.js](https://github.com/mattboldt/typed.js/) for typing animation
- [ScrollReveal](https://scrollrevealjs.org/) for scroll animations

## Contact

For any inquiries about this template, contact Ahmed Ayman:
- Email: ahmedalhofy42@gmail.com
- LinkedIn: [linkedin.com/in/ahmed-alhofy](https://www.linkedin.com/in/ahmed-alhofy/)
- GitHub: [github.com/AhmedAyman4](https://github.com/AhmedAyman4)
