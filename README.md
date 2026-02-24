# Portfolio Website

A modern, responsive portfolio website with advanced features and beautiful animations.

## ✨ Features

### 🎨 Design Features
- **Dark/Light Mode Toggle** - Seamless theme switching with localStorage persistence
- **Animated Background** - Floating gradient shapes for visual appeal
- **Smooth Animations** - CSS animations and transitions throughout
- **Responsive Design** - Works perfectly on all devices (mobile, tablet, desktop)
- **Custom Cursor Effect** - Interactive cursor with follower
- **Glassmorphism** - Modern frosted glass effect on navigation

### 🚀 Interactive Features
- **Smooth Scrolling** - Native smooth scroll to sections
- **Active Section Highlighting** - Navigation highlights current section
- **Typing Effect** - Animated role titles in hero section
- **Counter Animation** - Animated statistics with scroll trigger
- **Skill Progress Bars** - Animated skill bars with gradient colors
- **Project Filtering** - Filter projects by category (All, Web, Mobile, Design)
- **Scroll to Top Button** - Quick navigation back to top
- **Form Validation** - Contact form with validation and success notifications
- **Intersection Observer** - Scroll-triggered animations for performance
- **Parallax Effect** - Subtle parallax on hero section

### 🎯 Advanced Features
- **Lazy Loading** - Images load as they enter viewport
- **Performance Optimized** - Minimal reflows and repaints
- **Keyboard Navigation** - Full keyboard accessibility
- **Easter Egg** - Konami code surprise (↑↑↓↓←→←→BA)
- **Console Messages** - Developer-friendly console logs
- **Analytics Ready** - Event tracking structure included
- **PWA Ready** - Service worker registration prepared

### ♿ Accessibility
- **Focus States** - Clear focus indicators for keyboard navigation
- **ARIA Labels** - Proper accessibility labels
- **Semantic HTML** - Correct HTML5 semantic structure
- **Reduced Motion** - Respects prefers-reduced-motion setting

## 📁 File Structure

```
fortfolio/
├── index.html      # Main HTML structure
├── style.css       # All styles and animations
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🎨 Customization Guide

### 1. Personal Information

**In index.html**, replace:
- `Your Name` - Your actual name
- `YourName` - Your brand name
- `your.email@example.com` - Your email
- `+1 (234) 567-890` - Your phone number
- `Your City, Country` - Your location

### 2. Social Links

Update the `href` attributes in:
- GitHub: Line ~68
- LinkedIn: Line ~71
- Twitter: Line ~74
- CodePen: Line ~77

### 3. About Section

**Lines ~94-106**: Update your bio and description
**Lines ~111-115**: Update technologies you work with

### 4. Skills Section

**Lines ~125-196**: Customize:
- Skill names
- Skill percentages (data-progress attribute)
- Add/remove skill categories

### 5. Projects Section

**Lines ~208-337**: For each project:
- Update project title
- Update description
- Update tags/technologies
- Update project links (demo and GitHub)
- Change data-category for filtering

### 6. Contact Information

**Lines ~370-390**: Update:
- Email address
- Phone number
- Location

### 7. Colors & Branding

**In style.css** (Lines 5-30), customize CSS variables:

```css
--primary-color: #6366f1;       /* Main brand color */
--secondary-color: #ec4899;     /* Accent color */
--accent-color: #14b8a6;        /* Tertiary accent */
```

### 8. Typography

Change fonts by updating:
```css
--font-primary: 'Inter', sans-serif;
--font-mono: 'Fira Code', monospace;
```

To use custom fonts, add Google Fonts link in HTML `<head>`:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font&display=swap" rel="stylesheet">
```

### 9. Typing Effect Roles

**In script.js** (Lines 101-106), customize the roles:
```javascript
const roles = [
    'Your Role 1',
    'Your Role 2',
    'Your Role 3'
];
```

### 10. Statistics

**In index.html** (Lines ~120-145), update:
- `data-target` attribute for each stat
- Stat labels

## 🖼️ Adding Images

### Profile Image
Replace the placeholder at Line ~88:
```html
<div class="image-placeholder">
    <i class="fas fa-user"></i>
</div>
```

With:
```html
<img src="your-image.jpg" alt="Your Name">
```

### Project Images
Replace placeholders in project cards (Lines ~213, 231, 249, etc.):
```html
<div class="project-placeholder">
    <i class="fas fa-image"></i>
</div>
```

With:
```html
<img src="project-image.jpg" alt="Project Name">
```

## 🎨 Color Schemes

### Purple & Pink (Current)
```css
--primary-color: #6366f1;
--secondary-color: #ec4899;
```

### Blue & Green
```css
--primary-color: #3b82f6;
--secondary-color: #10b981;
```

### Orange & Red
```css
--primary-color: #f97316;
--secondary-color: #ef4444;
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 968px - 1199px
- **Mobile**: Below 968px
- **Small Mobile**: Below 640px

## 🚀 Deployment

### GitHub Pages
1. Create a GitHub repository
2. Push all files to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `username.github.io/repo-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository
3. Instant deployment with custom domain support

### Vercel
1. Import your GitHub repository
2. Automatic deployment on every push
3. Custom domain support

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 📦 Dependencies

- **Font Awesome 6.4.0** - Icons
- No other external dependencies!
- Pure HTML, CSS, and JavaScript

## 🎯 Performance Tips

1. **Optimize Images**: Use WebP format and compress images
2. **Enable Caching**: Configure server caching headers
3. **Minify Files**: Minify CSS and JS for production
4. **Use CDN**: Host Font Awesome on CDN for faster loading
5. **Lazy Load**: Images are already set up for lazy loading

## 📝 To-Do (Optional Enhancements)

- [ ] Add blog section
- [ ] Integrate with a CMS
- [ ] Add testimonials section
- [ ] Create a service worker for offline support
- [ ] Add more project details in modal popups
- [ ] Integrate with email service (EmailJS, FormSpree)
- [ ] Add animations with GSAP or Anime.js
- [ ] Create multiple page versions
- [ ] Add language switcher
- [ ] Integrate analytics (Google Analytics)

## 🐛 Troubleshooting

### Theme toggle not working?
- Check if JavaScript is enabled
- Check browser console for errors
- Clear localStorage and try again

### Animations not smooth?
- Reduce animation complexity
- Check `prefers-reduced-motion` setting
- Update browser to latest version

### Mobile menu not closing?
- Check JavaScript console
- Verify hamburger ID matches in HTML and JS
- Test on different mobile browsers

## 📄 License

Feel free to use this template for your personal or commercial projects. Attribution is appreciated but not required.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you create something cool, share it!

## 📞 Support

For issues or questions:
- Check the troubleshooting section
- Review the customization guide
- Check browser console for errors

---

**Built with ❤️ using HTML, CSS, and JavaScript**

Last Updated: February 2026
