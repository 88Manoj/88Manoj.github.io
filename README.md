# 🚀 Manoj Aasare - Cybersecurity Portfolio Website

A stunning 3D cybersecurity-themed portfolio website with interactive animations and modern design.

## ✨ Features

- **3D Interactive Elements**: Hover effects, card rotations, and depth animations
- **Cyberpunk Aesthetic**: Neon colors, glitch effects, and matrix rain background
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered animations and parallax effects
- **Custom Cursor**: Interactive glow effect that follows your mouse
- **Professional Sections**:
  - Hero section with glitch text effect
  - Skills showcase with 3D cards
  - Experience timeline
  - Certifications with rotating badges
  - Contact section

## 📁 Files Included

- `index.html` - Main portfolio website (single-file, no dependencies needed!)
- `manoj_aasare_resume.pdf` - Professional resume for download

## 🌐 FREE Hosting Options

### Option 1: GitHub Pages (Recommended) ⭐

**Best for**: Version control, free HTTPS, custom domain support

1. **Create a GitHub Account**: Go to [github.com](https://github.com) and sign up

2. **Create a New Repository**:
   - Click the "+" icon → "New repository"
   - Name it: `your-username.github.io` (replace with your GitHub username)
   - Make it Public
   - Click "Create repository"

3. **Upload Files**:
   - Click "uploading an existing file"
   - Drag and drop both `index.html` and `manoj_aasare_resume.pdf`
   - Commit changes

4. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Click Save

5. **Access Your Site**:
   - Your site will be live at: `https://your-username.github.io`
   - Wait 2-3 minutes for deployment

**Custom Domain (Optional)**:
- Buy a domain from Namecheap, GoDaddy, etc.
- In Settings → Pages → Custom domain, add your domain
- Update DNS settings at your domain registrar

---

### Option 2: Netlify

**Best for**: Drag-and-drop deployment, automatic HTTPS

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up (free account)
3. Click "Add new site" → "Deploy manually"
4. Drag and drop your files
5. Your site is live instantly at: `random-name.netlify.app`
6. You can change the subdomain in Site settings

**Custom Domain**: Available in free tier

---

### Option 3: Vercel

**Best for**: Fast deployment, great performance

1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub (recommended)
3. Click "Add New" → "Project"
4. Import your GitHub repository OR upload files
5. Deploy
6. Live at: `your-project.vercel.app`

---

### Option 4: Cloudflare Pages

**Best for**: Speed, CDN, unlimited bandwidth

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Sign up (free)
3. Create a project
4. Connect GitHub or upload via direct upload
5. Deploy
6. Live at: `your-project.pages.dev`

---

### Option 5: Render

**Best for**: Simple deployment

1. Go to [render.com](https://render.com)
2. Sign up
3. New → Static Site
4. Connect repository or deploy manually
5. Your site will be at: `your-site.onrender.com`

---

### Option 6: InfinityFree (Traditional Hosting)

**Best for**: FTP access, multiple projects

1. Go to [infinityfree.net](https://infinityfree.net)
2. Create account
3. Create hosting account
4. Use File Manager or FTP to upload files
5. Access via provided subdomain or custom domain

---

## 🎨 Customization Guide

### Change Colors

Find this section in the HTML (around line 13):

```css
:root {
    --primary: #00ff88;      /* Main neon green */
    --secondary: #00d4ff;    /* Cyan blue */
    --accent: #ff006e;       /* Pink accent */
    --dark: #0a0e27;         /* Dark background */
    --darker: #050714;       /* Darker shade */
    --text: #e0e0e0;         /* Text color */
}
```

### Update Content

- **Personal Info**: Search for "Manoj Aasare" and replace with your name
- **Contact Details**: Update email, phone, and LinkedIn links
- **Skills**: Modify the skill cards in the `#skills` section
- **Experience**: Update timeline items in the `#experience` section
- **Certifications**: Add/remove cert badges in `#certifications` section

### Add More Sections

Copy any existing section and modify:

```html
<section id="new-section" class="section">
    <h2 class="section-title">Your Section Title</h2>
    <!-- Your content here -->
</section>
```

---

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Hamburger menu for mobile navigation
- Stacked layouts on smaller screens
- Touch-optimized interactions
- Optimized font sizes

---

## 🚀 Quick Start (Local Testing)

1. Download both files to a folder
2. Double-click `index.html`
3. Opens in your default browser
4. No server needed - it's a static site!

---

## 🔧 Advanced Tips

### Adding Analytics

Add before `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-TRACKING-ID');
</script>
```

### SEO Optimization

The site includes:
- Semantic HTML5
- Meta descriptions (add in `<head>`)
- Proper heading hierarchy
- Fast loading (single file)

Add these meta tags:

```html
<meta name="description" content="Manoj Aasare - Cybersecurity Professional specializing in VAPT, Penetration Testing, and Ethical Hacking">
<meta name="keywords" content="cybersecurity, penetration testing, VAPT, ethical hacking, web security">
<meta property="og:title" content="Manoj Aasare - Cybersecurity Professional">
<meta property="og:description" content="Ethical Hacker & VAPT Specialist">
```

---

## 🎯 Recommended: GitHub Pages Setup

**Step-by-step for beginners:**

1. **Install Git** (optional but recommended):
   - Download from [git-scm.com](https://git-scm.com)
   - Install with default settings

2. **Create GitHub Account**:
   - Go to [github.com/signup](https://github.com/signup)
   - Use your email

3. **Create Repository**:
   ```
   Repository name: manojaasare.github.io
   (or your-username.github.io)
   Public repository
   Initialize with README: No
   ```

4. **Upload Files**:
   - Click "uploading an existing file"
   - Drag `index.html` and `manoj_aasare_resume.pdf`
   - Write commit message: "Initial commit"
   - Click "Commit changes"

5. **Enable Pages**:
   - Settings → Pages
   - Source: main branch
   - Save

6. **Wait 2-3 minutes** and visit: `https://manojaasare.github.io`

---

## 🆘 Troubleshooting

**Site not loading after deployment?**
- Wait 5 minutes for DNS propagation
- Clear browser cache (Ctrl+Shift+Delete)
- Check if files are in root directory

**Resume download not working?**
- Make sure `manoj_aasare_resume.pdf` is in the same folder as `index.html`
- Check file name matches exactly (case-sensitive)

**Mobile menu not working?**
- Make sure JavaScript is enabled
- Check browser console for errors (F12)

**Colors look different?**
- Some monitors show colors differently
- Adjust CSS variables for your preference

---

## 📞 Support

For issues or questions:
- Email: manojaasare88@gmail.com
- Create an issue on GitHub
- Check browser console for errors (F12 key)

---

## 📄 License

Free to use and modify for personal use. Attribution appreciated but not required.

---

## 🌟 Features Breakdown

### Animations
- ✅ Glitch text effect on hero
- ✅ Typing animation on tagline
- ✅ Matrix rain background
- ✅ Scroll-triggered fade-ins
- ✅ 3D card hover effects
- ✅ Pulsing timeline dots
- ✅ Rotating certification badges
- ✅ Custom cursor glow

### Interactivity
- ✅ Smooth scroll navigation
- ✅ Parallax background
- ✅ Hover effects on cards
- ✅ Mobile-responsive menu
- ✅ Click-to-download resume

### Performance
- ✅ Single HTML file (fast loading)
- ✅ No external dependencies
- ✅ Optimized animations
- ✅ Mobile-optimized

---

**🎉 Your portfolio is ready to impress! Deploy it and share your cybersecurity expertise with the world!**
