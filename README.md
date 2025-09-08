# Modern Portfolio Website

A modern, interactive personal portfolio website built with HTML5, CSS3, vanilla JavaScript, Tailwind CSS, and GSAP animations.

## Features

- **Modern Design**: Dark mode theme with neon glowing colors and glassmorphism effects
- **Interactive Elements**: Smooth scrolling, hover animations, and tilt effects
- **Responsive**: Fully responsive design for all devices (desktop, tablet, mobile)
- **Animations**: GSAP-powered animations for scroll reveals and interactive elements
- **Well-Organized Code**: Clean, commented code for easy customization

## Sections

1. **Hero Section**: Animated name with gradient text and tagline
2. **About Section**: Bio with animated fade-in and profile picture
3. **Projects Section**: Grid layout with hover tilt effect and project cards
4. **Skills Section**: Animated progress bars showing technical skills
5. **Contact Section**: Contact form and social media links

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [GSAP](https://greensock.com/gsap/) for animations

## How to Customize

### Basic Information

1. Open `index.html` and update:
   - Your name and tagline in the Hero section
   - About Me content
   - Project details
   - Skills and their percentages
   - Contact information

### Styling

1. Colors and theme:
   - Edit the color variables in `css/style.css` and `tailwind.config.js`
   - Modify the glassmorphism effects in the CSS file

### Projects

To add a new project:

1. Copy an existing project card in the Projects section
2. Update the image, title, description, and tags
3. Update the links to your GitHub repository and live demo

### Skills

To add or modify skills:

1. Copy an existing skill item in the Skills section
2. Update the SVG icon, title, and progress percentage

## Local Development

1. Clone this repository
2. Open `index.html` in your browser
3. For Tailwind CSS development:
   - Install Node.js and npm
   - Run `npm install`
   - Run `npx tailwindcss -i ./css/style.css -o ./css/output.css --watch`

## License

MIT License