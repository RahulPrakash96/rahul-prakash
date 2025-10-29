# Rahul Prakash - Portfolio

Welcome to my personal portfolio website! 👋

A clean, professional static portfolio website with sidebar navigation, inspired by modern portfolio designs.

## 🌐 Live Site
Visit my portfolio at: [https://rahulprakash96.github.io/rahul-prakash/](https://rahulprakash96.github.io/rahul-prakash/)

## ✨ Features
- **Sidebar Navigation** - Fixed sidebar with smooth scrolling to sections
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Clean Layout** - Professional sections for About, Experience, Projects, and Certifications
- **Downloadable Resume** - Visitors can download your PDF resume
- **Smooth Animations** - Cards and sections animate as you scroll
- **Active Link Highlighting** - Navigation links highlight based on scroll position
- **Social Links** - Quick access to LinkedIn, GitHub, and email

## 📋 Sections

### About
- Profile image and bio
- Contact information
- Resume download button

### Experience
- **Education** - Your degrees and academic achievements
- **Work Experience** - Job history with responsibilities and achievements

### Projects
- Showcase your work with images, descriptions, and links
- Technology tags for each project
- Links to GitHub repos and live demos

### Certifications
- Display your professional certifications
- Visual certification cards

## 📁 Structure
```
rahul-prakash/
├── index.html              # Main HTML file
├── style.css              # All styling
├── script.js              # Interactive functionality
├── assets/                # Images and documents
│   ├── profile.png        ✓ Your profile photo
│   ├── resume.pdf         ✓ Your resume
│   ├── project1.png       (Add your project images)
│   ├── project2.png
│   ├── project3.png
│   ├── project4.png
│   ├── cert-icon.png      (Certification icon)
│   ├── README.md          (Assets instructions)
│   └── IMAGES.md          (How to add images)
├── README.md              # This file
└── SETUP.md              # Detailed setup instructions
```

## 🚀 Quick Start

1. **Customize Content**: Edit `index.html` to add your information
   - Update your bio and contact details
   - Add your education and work experience
   - List your projects with descriptions and links
   - Add your certifications

2. **Add Images** (Optional but recommended):
   - Add project screenshots to the `assets/` folder
   - See `assets/IMAGES.md` for placeholder image options

3. **Customize Colors**: Edit CSS variables in `style.css`
   ```css
   :root {
       --primary-color: #149ddd;  /* Change to your preferred color */
   }
   ```

4. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Update portfolio with my information"
   git push origin main
   ```

5. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Select `main` branch and `/ (root)` folder
   - Click Save

## 🛠️ Technologies Used
- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons (via CDN)

## 📱 Responsive Breakpoints
- **Desktop**: > 1024px (Full sidebar)
- **Tablet**: 768px - 1024px (Narrow sidebar)
- **Mobile**: < 768px (Horizontal navigation)

## 🎨 Customization

### Change Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #149ddd;
    --text-dark: #172b4d;
    --text-light: #45505b;
    --bg-light: #f5f8fd;
}
```

### Add More Sections
The structure makes it easy to add new sections - just follow the existing pattern in `index.html`.

## 📝 License
This project is open source and available under the MIT License.

## 📧 Contact
Feel free to reach out through the contact section on my portfolio!

---
Built with ❤️ by Rahul Prakash

**For detailed setup instructions, see [SETUP.md](SETUP.md)**
