# Freya Jiang - Academic Homepage

🌐 **Live Site:** https://jyhfreya.github.io/freya-jiang.github.io/

A modern, clean academic homepage inspired by Google Scholar's design aesthetic.

## 🚀 Quick Start

1. Open `index.html` in your web browser to preview the website
2. Customize the content as needed
3. Push to GitHub repository `freya-jiang.github.io`

## 📁 File Structure

```
freya-academic-homepage/
├── index.html      # Main HTML file (with SEO optimization)
├── style.css       # Stylesheet
├── avatar.png      # Profile photo
├── sitemap.xml     # Sitemap for search engines
├── robots.txt      # Search engine crawling rules
└── README.md       # This file
```

## 🖼️ Adding Your Photo

1. Add your photo to this folder (e.g., `photo.jpg`)
2. Open `index.html` and find this section:

```html
<div class="avatar">
    <div class="avatar-placeholder">
        <span>F</span>
    </div>
    <!-- Replace with: <img src="your-photo.jpg" alt="Freya Jiang"> -->
</div>
```

3. Replace it with:

```html
<div class="avatar">
    <img src="photo.jpg" alt="Freya Jiang">
</div>
```

## 🔗 Adding Social Links

Update the `href="#"` attributes in the social links section:

- **Google Scholar**: Replace with your Google Scholar profile URL
- **GitHub**: Replace with your GitHub profile URL  
- **LinkedIn**: Replace with your LinkedIn profile URL

## 🌐 Deploying to GitHub Pages

1. Create a new GitHub repository named `your-username.github.io`
2. Upload all files to the repository
3. Go to Settings → Pages → Source: Deploy from branch (main)
4. Your site will be live at `https://your-username.github.io`

## ✏️ Customization Tips

### Colors
Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #1a73e8;    /* Main accent color */
    --text-primary: #202124;      /* Main text color */
    --bg-primary: #ffffff;        /* Background color */
}
```

### Adding Publications
You can add a publications section by copying the project card structure:

```html
<div class="project-card">
    <div class="project-header">
        <h3 class="project-title">Paper Title</h3>
    </div>
    <p class="project-description">
        Authors. <em>Conference/Journal Name</em>, Year.
    </p>
</div>
```

## 📱 Features

- ✅ Responsive design (mobile-friendly)
- ✅ Clean, academic aesthetic
- ✅ Print-friendly styles
- ✅ No JavaScript dependencies
- ✅ Fast loading
- ✅ Easy to customize

## 📄 License

Feel free to use and modify this template for your own academic homepage.

---

**Last Updated:** February 2026

