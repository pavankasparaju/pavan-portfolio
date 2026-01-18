# Kasparaju Pavan - Developer Portfolio

A premium dark-themed personal developer portfolio website featuring glassmorphism UI, neon glow accents, animated cards, and smooth scrolling navigation.

## 🎨 Design Features

- **Dark Theme**: Midnight Blue color palette with Neon Cyan and Ice Blue accents
- **Glassmorphism UI**: Modern glass blur effect with glowing borders
- **Smooth Animations**: Fade-up reveal on scroll, hover effects, and transitions
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices
- **Premium UI/UX**: Recruiter-grade professional design

## 🛠️ Tech Stack

- **HTML5**: Semantic markup structure
- **CSS3**: Custom glassmorphism styles with animations
- **JavaScript**: Vanilla JS with Intersection Observer API
- **Fonts**: Inter font family from Google Fonts

## 📁 Project Structure

```
pavan portfolio/
├── index.html              # Main HTML file
├── style.css              # Stylesheet with glassmorphism effects
├── script.js              # JavaScript for animations and interactions
├── README.md              # Project documentation
└── assets/
    ├── images/
    │   └── profile.jpg    # Profile photo (replace with your image)
    └── resume/
        └── Pavan_Resume.pdf  # Resume PDF (replace with your resume)
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. **Clone or download this repository**
   ```bash
   git clone <repository-url>
   cd "pavan portfolio"
   ```

2. **Add your assets**
   - Replace `assets/images/profile.jpg` with your actual profile photo
   - Replace `assets/resume/Pavan_Resume.pdf` with your actual resume PDF

3. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     
     # Using VS Code Live Server extension
     # Right-click index.html -> Open with Live Server
     ```

4. **Access the website**
   - If using a server: `http://localhost:8000`
   - Or double-click `index.html` to open directly

## 📝 Customization

### Updating Personal Information

Edit the following sections in `index.html`:

1. **Hero Section** (lines ~45-50): Update name, title, and intro
2. **About Section** (lines ~100-120): Update education and career information
3. **Skills Section** (lines ~130-200): Update skills lists
4. **Projects Section** (lines ~210-280): Update project details and links
5. **Certifications Section** (lines ~290-310): Update certifications
6. **Contact Section** (lines ~320-380): Update contact information and links

### Customizing Colors

Edit CSS variables in `style.css` (lines ~15-30):

```css
:root {
    --midnight-blue: #0a0e27;
    --neon-cyan: #00d9ff;
    --ice-blue: #4da6ff;
    /* ... more variables */
}
```

### Adding Projects

To add a new project card, copy the project card structure in `index.html` and update:

- Project title
- Status badge
- Description
- Tech stack tags
- GitHub and Live Demo links

## 🎯 Features

### Navigation
- Sticky navbar with smooth scroll navigation
- Active link highlighting based on scroll position
- Mobile-responsive hamburger menu

### Sections
1. **Hero**: Profile photo with glow ring, intro text, and CTA buttons
2. **About**: Education and career information cards
3. **Skills**: Grid layout with categorized skill cards
4. **Projects**: Project showcase with tech stack and links
5. **Certifications**: Certification cards with check icons
6. **Contact**: Contact form and information cards
7. **Footer**: Social links and copyright

### Animations
- Fade-up reveal on scroll (Intersection Observer)
- Card hover glow effects
- Button ripple effects
- Floating profile image animation
- Background gradient pulse

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Troubleshooting

### Images not loading
- Ensure `assets/images/profile.jpg` exists and is a valid image file
- Check file paths are correct (case-sensitive on some systems)

### Resume download not working
- Verify `assets/resume/Pavan_Resume.pdf` exists
- Check file path in the download link

### Animations not working
- Ensure JavaScript is enabled in your browser
- Check browser console for any errors
- Verify `script.js` is loaded correctly

## 📄 License

This portfolio template is open source and available for personal use.

## 👨‍💻 Author

**Kasparaju Pavan**
- Backend Engineer | Web Developer
- Building scalable backend systems and AI-powered applications

## 🙏 Acknowledgments

- Design inspiration from modern tech startup landing pages
- Glassmorphism UI trends
- Smooth scrolling and animation techniques

---

**Note**: Remember to replace placeholder assets with your actual profile image and resume PDF before deploying!
