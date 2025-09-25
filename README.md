# Konrad Bachusz Portfolio

A modern, responsive personal portfolio website showcasing my professional experience, projects, and skills in data engineering, machine learning, and software development.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Navigation**: Sticky navigation with active page indicators and mobile hamburger menu
- **Project Showcase**: Dedicated projects section highlighting key work and achievements
- **Contact Form**: Functional contact form using Formspree for easy communication
- **Social Media Integration**: Direct links to LinkedIn, GitHub, and Medium profiles

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS (CDN), Custom CSS
- **Typography**: Google Fonts (Inter)
- **Form Handling**: Formspree integration
- **Images**: Optimized background images and project screenshots

## 📁 Project Structure

```
konrad_bachusz_portfolio/
├── index.html          # Homepage with introduction and featured projects
├── about.html           # About page with professional background
├── projects.html        # Projects showcase page
├── cv.html             # CV/Resume page
├── contact.html        # Contact form page
├── contact-emailjs.html # Alternative contact page (EmailJS - unused)
├── images/             # Image assets
│   ├── profile.jpg
│   ├── project screenshots
│   ├── social media icons
│   └── background images
├── linkedin.md         # LinkedIn content reference
└── README.md          # This file
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/konrad_bachusz_portfolio.git
   cd konrad_bachusz_portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server for development:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx http-server
   ```

3. **View the website**
   - Navigate to `http://localhost:8000` if using a local server
   - Or open the HTML files directly in your browser

## 📧 Contact Form Setup

The contact form uses Formspree for handling form submissions. To set up:

1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form and get your form endpoint
3. Update the form action in `contact.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## 🎨 Customization

- **Colors**: Modify the color scheme in the CSS custom properties
- **Content**: Update the content in each HTML file to reflect your own information
- **Images**: Replace images in the `/images` directory with your own
- **Projects**: Update the projects section with your own work and achievements

## 📱 Pages Overview

- **Home**: Introduction, brief bio, and featured projects
- **About**: Detailed professional background and experience
- **Projects**: Complete portfolio of work and achievements
- **CV**: Professional resume and qualifications
- **Contact**: Contact form and social media links

## 🔧 Development

The website is built with vanilla HTML, CSS, and JavaScript for maximum compatibility and performance. No build process is required - simply edit the files and refresh your browser.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this repository and adapt it for your own portfolio. If you make improvements that could benefit others, pull requests are welcome!