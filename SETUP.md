# Portfolio Setup Guide

## 🎉 Your Static Portfolio is Ready!

Your portfolio is now styled like a professional static website with a sidebar navigation, similar to the example you shared!

## ✅ What's Already Done:

- ✓ Profile image (`profile.png`) added
- ✓ Resume (`resume.pdf`) added
- ✓ Clean sidebar navigation layout
- ✓ Professional sections: About, Experience, Projects, Certifications
- ✓ Fully responsive design
- ✓ Smooth animations and hover effects

## 📝 Step 1: Customize Your Content

Edit `index.html` to add your information:

### About Section:
- Update your degree and field of study
- Add your bio/description
- Update contact information (city, phone, email)
- Update social media links (LinkedIn, GitHub, email)

### Experience Section:

**Education:**
- Add your degrees with dates
- University names
- Descriptions of your education

**Work Experience:**
- Job titles and dates
- Company names
- Key responsibilities and achievements (bullet points)

### Projects Section:
- Project titles
- Technologies used (shown in colored text)
- Project descriptions
- GitHub repo and live demo links
- Add project images to `assets/` folder (optional but recommended)

### Certifications Section:
- List all your certifications
- Update certification provider names
- Add certification icons if you have them

## 🖼️ Step 2: Add Images (Optional)

For better visual appeal, add these to the `assets/` folder:

```bash
assets/
├── project1.png      # Screenshot or image of project 1
├── project2.png      # Screenshot or image of project 2
├── project3.png      # Screenshot or image of project 3
├── project4.png      # Screenshot or image of project 4
└── cert-icon.png     # Generic certification icon (80x80px)
```

If you don't have project images, you can either:
- Remove the `<img>` tags from project cards, or
- Use placeholder images from services like https://placehold.co/800x450

## 🎨 Step 3: Customize Colors (Optional)

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #149ddd;      /* Change this to your preferred color */
    --text-dark: #172b4d;
    --text-light: #45505b;
    --bg-light: #f5f8fd;
}
```

## 🚀 Step 4: Enable GitHub Pages

1. Commit and push your changes:
```bash
git add .
git commit -m "Add professional static portfolio"
git push origin main
```

2. Go to: https://github.com/RahulPrakash96/rahul-prakash/settings/pages

3. Under "Source", select **main** branch and **/ (root)** folder

4. Click **Save**

5. Wait a few minutes for deployment

## 🌐 Your Portfolio URL:

**https://rahulprakash96.github.io/rahul-prakash/**

## 💡 Tips:

1. **Mobile Responsive**: The sidebar converts to a horizontal menu on mobile devices

2. **Smooth Scrolling**: Clicking navigation links smoothly scrolls to sections

3. **Active Link Highlighting**: As you scroll, the nav link for the current section highlights

4. **Animations**: Cards fade in as you scroll down the page

5. **Download Resume**: The button in the About section lets visitors download your PDF resume

## 🔧 Troubleshooting:

**If social media icons don't appear:** The Font Awesome CDN is included, but check your internet connection.

**If images don't load:** Make sure image filenames match exactly (case-sensitive) and are in the `assets/` folder.

**If portfolio doesn't display on GitHub Pages:** Check that `index.html` is in the root folder and GitHub Pages is enabled.

Enjoy your professional portfolio! 🎊

