# Portfolio Customization Guide - Anmagandla Snehil

## ✅ What's Been Updated

### Personal Information
- ✅ Name: Anmagandla Snehil
- ✅ Email: snehil.a030@nmims.edu.in
- ✅ Phone: +91 9502605942
- ✅ Date of Birth: 01-08-2004
- ✅ University: NMIMS Mumbai
- ✅ CGPA: 3.11/4.00

### Education Section (NEW!)
- ✅ B.Tech Computer Science - Data Science (2022-2026)
- ✅ HSC from Rishi Junior College (90.7%)
- ✅ SSC from Brilliant Grammar High School (9.8 CGPA)
- ✅ Internship at DataElegance Solution LLP

### Projects Section
- ✅ Sleep Apnea Disorder Detection (Deep Learning)
- ✅ Wild-Guard: AI-Powered Wildlife Detection System
- ✅ Geo-Alert: Location-Based Alarm Application
- ✅ Warehouse Management System
- ✅ YouTube Engagement Predictor (IBM Z Datathon)
- ✅ Award-Winning Web Projects

### Skills Section
- ✅ Frontend: HTML, CSS, JavaScript, React.js, Next.js
- ✅ AI/ML: Python, Deep Learning, CNN, LSTM, Data Analysis
- ✅ Backend & Database: Node.js, MongoDB, MySQL, AWS
- ✅ Mobile & Tools: Java, Android SDK, Git, Firebase
- ✅ Soft Skills: Leadership, Research, Collaboration

### Achievements Section (NEW!)
- ✅ Secretary - Impulse Sports Committee (2024)
- ✅ IBM Z Datathon Participant
- ✅ Runner-up - CodeIT Webathon (3rd Position)
- ✅ Runner-up - CSI Project Expo (3rd Position)
- ✅ IEEE ICEI 2025 Publication at IIT Dharwad
- ✅ ACM Summer School on IoT (2025)

### Advanced Features Included
- ✅ Dark/Light mode toggle with localStorage
- ✅ Animated gradient background
- ✅ Smooth scrolling & navigation
- ✅ Typing animation effect
- ✅ Animated statistics counters
- ✅ Skill progress bars with animations
- ✅ Project filtering system
- ✅ Timeline for education/experience
- ✅ Achievement cards with hover effects
- ✅ Contact form with validation
- ✅ Scroll to top button
- ✅ Responsive design for all devices
- ✅ Custom cursor effect
- ✅ Parallax scrolling
- ✅ Easter egg (Konami code)

## 📝 Still Need to Update

### Social Media Links
Update your actual social media links in `index.html`:

**Line ~75-88 (Hero Section):**
```html
<a href="https://github.com/YOUR_USERNAME" target="_blank">
<a href="https://linkedin.com/in/YOUR_USERNAME" target="_blank">
```

**Line ~510-525 (Footer Section):**
```html
<a href="https://github.com/YOUR_USERNAME" target="_blank">
<a href="https://linkedin.com/in/YOUR_USERNAME" target="_blank">
```

### Project Links
Add GitHub repository links and live demo links for your projects:

**Lines ~260-410 (Projects Section):**
```html
<!-- For each project, update these -->
<a href="YOUR_LIVE_DEMO_URL" class="project-link">
<a href="YOUR_GITHUB_REPO_URL" class="project-link">
```

### Images

#### Profile Picture
Replace the placeholder icon at **Line ~88**:
```html
<!-- Current -->
<div class="image-placeholder">
    <i class="fas fa-user"></i>
</div>

<!-- Replace with -->
<img src="images/profile.jpg" alt="Anmagandla Snehil" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
```

#### Project Images
Replace project placeholder icons with actual images:
```html
<!-- Current -->
<div class="project-placeholder">
    <i class="fas fa-heartbeat"></i>
</div>

<!-- Replace with -->
<img src="images/project-name.jpg" alt="Project Name" style="width: 100%; height: 100%; object-fit: cover;">
```

**Recommended Image Sizes:**
- Profile Image: 400x400px (square)
- Project Images: 600x400px (landscape)

## 🎨 Customization Options

### 1. Change Color Scheme
Edit `style.css` (Lines 5-30):
```css
/* Current Purple & Pink */
--primary-color: #6366f1;
--secondary-color: #ec4899;
--accent-color: #14b8a6;

/* Try Blue & Teal */
--primary-color: #3b82f6;
--secondary-color: #06b6d4;
--accent-color: #8b5cf6;

/* Or Orange & Red */
--primary-color: #f97316;
--secondary-color: #ef4444;
--accent-color: #eab308;
```

### 2. Update Typing Animation Roles
Edit `script.js` (Lines 101-107):
```javascript
const roles = [
    'AI/ML Engineer',           // Current roles
    'Full Stack Developer',
    'Data Science Enthusiast',
    'Research Scholar',
    'Android Developer'
];
```

### 3. Adjust Skills Percentages
Edit skill progress values in `index.html` (Lines ~200-300):
```html
<div class="skill-progress" data-progress="90"></div>
<!-- Change 90 to your desired percentage -->
```

### 4. Add More Achievements
Copy achievement card template in `index.html` (around Line ~175):
```html
<div class="achievement-card">
    <div class="achievement-icon">
        <i class="fas fa-trophy"></i>
    </div>
    <h4>Your Achievement Title</h4>
    <p>Description of your achievement</p>
</div>
```

## 🚀 Next Steps

### 1. Create Image Folder
```powershell
# Run in PowerShell
New-Item -Path "c:\Users\91630\Desktop\fortfolio\images" -ItemType Directory
```

### 2. Add Your Images
- Save your profile picture as `images/profile.jpg`
- Save project screenshots as `images/project1.jpg`, `images/project2.jpg`, etc.

### 3. Test Responsiveness
Open the portfolio and resize your browser to test:
- Desktop view (1200px+)
- Tablet view (768px-1199px)
- Mobile view (320px-767px)

### 4. Deploy Online
Choose one:
- **GitHub Pages**: Free hosting with custom domain support
- **Netlify**: Drag-and-drop deployment
- **Vercel**: One-click deployment

## 📱 Keyboard Shortcuts

- **T**: Toggle dark/light theme
- **Escape**: Close mobile menu
- **↑↑↓↓←→←→BA**: Easter egg surprise!

## 🔧 File Structure

```
fortfolio/
├── index.html                  # Main HTML file ✅ Updated
├── style.css                   # All styles ✅ Updated
├── script.js                   # Interactive features ✅ Updated
├── README.md                   # General documentation
├── CUSTOMIZATION_GUIDE.md      # This file
└── images/                     # Create this folder
    ├── profile.jpg            # Add your photo
    ├── project1.jpg           # Add project images
    ├── project2.jpg
    └── ...
```

## 📧 Contact Form Integration

The contact form currently shows a notification. To make it send actual emails:

### Option 1: FormSpree (Free & Easy)
1. Go to https://formspree.io/
2. Create account and get your form endpoint
3. Update form action in `index.html`:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option 2: EmailJS (More Control)
1. Sign up at https://www.emailjs.com/
2. Follow their integration guide
3. Update `script.js` contact form handler

## 🎯 Performance Tips

1. **Optimize Images**: Use WebP format and compress images
2. **Lazy Loading**: Already implemented for images
3. **Minify CSS/JS**: Use online tools before deployment
4. **Use CDN**: Font Awesome already on CDN

## 📊 Analytics

To track visitors, add Google Analytics:

1. Get tracking ID from Google Analytics
2. Add before `</head>` in `index.html`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR_TRACKING_ID');
</script>
```

## 🎨 Icon Resources

Using Font Awesome 6.4.0. Find more icons at:
- https://fontawesome.com/icons

Example usage:
```html
<i class="fas fa-icon-name"></i>     <!-- Solid -->
<i class="fab fa-icon-name"></i>     <!-- Brands -->
<i class="far fa-icon-name"></i>     <!-- Regular -->
```

## 📝 Resume Download

To add a downloadable resume button:

1. Save your resume as `resume.pdf` in the fortfolio folder
2. Add button in hero section:
```html
<a href="resume.pdf" download class="btn btn-primary">
    <span>Download Resume</span>
    <i class="fas fa-download"></i>
</a>
```

## 🌟 Got Questions?

All the advanced features are working:
- ✅ Theme toggle
- ✅ Smooth scroll
- ✅ Animations
- ✅ Filtering
- ✅ Timeline
- ✅ Responsive design
- ✅ Contact form
- ✅ And much more!

Just update your GitHub/LinkedIn links and add some images to make it 100% complete!

---

**Built with ❤️ for Anmagandla Snehil**
Last Updated: February 24, 2026
