# Asfar Personal Portfolio - HTML Template

A modern, animated portfolio website built with HTML5, CSS3, and vanilla JavaScript. Features smooth section transitions, interactive project showcase, and responsive design.

## 🚀 Live Demo

**[View Live Portfolio](https://appleiOSdevelopers.github.io/Asfar-personal-portfolio-html-template/)**

## ✨ Features

- **Smooth Animations** - GSAP-powered section transitions and scroll interactions
- **Interactive Project Modal** - Click projects to see detailed information
- **Custom Cursor** - Animated cursor with hover effects
- **Responsive Design** - Fully mobile-friendly layout
- **Dark Theme** - Modern dark mode with gradient accents
- **Contact Form** - Functional contact form with validation
- **Multi-section Navigation** - Easy navigation between 6 main sections:
  - Home/Hero
  - About
  - Work/Portfolio
  - Skills/Stats
  - Services
  - Contact

## 📁 Project Structure

```
.
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Main stylesheet
│   ├── bootstrap.min.css  # Bootstrap framework
│   └── all.min.css        # Font Awesome icons
├── js/
│   ├── main.js            # Core JavaScript functionality
│   ├── jquery-3.7.1.min.js
│   ├── bootstrap.bundle.min.js
│   └── gsap.min.js        # Animation library
├── img/
│   ├── me.jpg             # Profile image
│   └── portfolio/         # Project images
├── font/                  # Bootstrap Icons
└── webfonts/              # Font Awesome fonts
```

## 🎨 Customization

### Update Your Info

1. **Name & Title** - Edit in `index.html` (line 6, 34, 56)
2. **Profile Image** - Replace `img/me.jpg` with your photo
3. **About Section** - Update about text and skills (lines 87-100)
4. **Projects** - Modify project cards (lines 113-213)
5. **Services** - Update service descriptions (lines 268-297)
6. **Contact Email** - Change `hello@alexreeves.dev` to your email (line 308)
7. **Social Links** - Update social media URLs (lines 318-322)

### Color Theme

Edit CSS variables in `css/style.css` (`:root` section):

```css
--bg-deep:    #020409;      /* Deep background */
--accent:     #6c63ff;      /* Primary accent (purple) */
--accent2:    #00d4ff;      /* Secondary accent (cyan) */
--accent3:    #ff6b9d;      /* Tertiary accent (pink) */
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (jQuery)** - Interactive features
- **GSAP** - Advanced animations
- **Bootstrap 5** - Responsive framework
- **Font Awesome** - Icon library

## 📱 Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚙️ Setup & Deployment

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/appleiOSdevelopers/Asfar-personal-portfolio-html-template.git
cd Asfar-personal-portfolio-html-template
```

2. Open in browser:
- Simply open `index.html` in your browser, or
- Use a local server: `python -m http.server 8000`

### Deploy to GitHub Pages

The site is automatically deployed when you push to the `main` branch. View it at:
```
https://appleiOSdevelopers.github.io/Asfar-personal-portfolio-html-template/
```

### Deploy to Other Platforms

**Netlify:**
- Connect your GitHub repo to Netlify
- Set build command to: (leave empty - static site)
- Set publish directory to: `/` (root)

**Vercel:**
- Import project from GitHub
- Deploy (no build configuration needed)

## 🎯 Sections Breakdown

### 1. Home (Section 0)
- Hero text with glitch effect
- Call-to-action buttons
- Animated scroll indicator

### 2. About (Section 1)
- Profile image with decorative frame
- Biography and skills
- Experience badge

### 3. Portfolio (Section 2)
- 6 project cards in 3x2 grid
- Hover overlay with project details
- Click to view full project modal

### 4. Stats (Section 3)
- Animated counters
- Skill progress bars
- Professional metrics

### 5. Services (Section 4)
- 6 service offerings
- Icon + description layout
- Hover animations

### 6. Contact (Section 5)
- Email address (clickable)
- Contact form with validation
- Social media links

## 🔧 Features & Interactions

### Navigation
- **Dot Navigation** - Right sidebar with section indicators
- **Scroll Wheel** - Scroll to navigate sections
- **Touch Gestures** - Swipe up/down on mobile
- **Keyboard** - Arrow keys & Page Up/Down

### Cursor
- Custom animated cursor
- Scales up on hover over interactive elements
- Color changes based on interaction

### Form Handling
- Email validation
- Required field checking
- Submit feedback message
- Clears on successful submission

### Animations
- GSAP timeline animations
- Parallax orb effects
- Smooth section transitions
- Staggered element reveals

## 📝 Content Updates

### Adding a New Project

Edit `index.html` section 2 (lines 107-216). Duplicate a project card and update:

```html
<div class="project-card" 
  data-title="Your Project Title"
  data-img="img/portfolio/your-image.jpg"
  data-tags="Tag1,Tag2,Tag3"
  data-desc="Your project description here"
  data-role="Your role"
  data-year="2025"
  data-stack="Tech1 · Tech2 · Tech3"
  data-live="https://your-live-site.com"
  data-github="https://github.com/your-repo">
```

### Updating Stats

Edit counters in section 3 (lines 224-239):
```html
<div class="stat-num counter" data-target="YOUR_NUMBER">0</div>
```

## 🐛 Troubleshooting

**Images not showing:**
- Ensure images are in correct paths
- Check file names match exactly (case-sensitive)

**GitHub Pages showing blank:**
- Ensure repo is public
- Check branch is set to `main`
- Clear browser cache and hard refresh (Ctrl+Shift+R)

**Animations not working:**
- Verify GSAP is loading (check browser console)
- Check for JavaScript errors (F12 → Console)

**Mobile issues:**
- Test in mobile browser dev tools
- Ensure viewport meta tag is present (it is)

## 📄 License

This template is free to use and modify for personal or commercial projects.

## 👨‍💻 Author

Created by **Asfar Hussain Siddiqui** - iOS Developer

---

**Need help?** Check the comments in the source files or review the structure above.
