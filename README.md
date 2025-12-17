# Magellan Metrics Private Limited - Professional Website

## 🌐 Website Overview
Premium, enterprise-grade website for Magellan Metrics Private Limited, a leading remote recruitment services provider specializing in customer service, sales, and IT talent for local and international companies.

## ✨ Key Features

### Design & Visuals
- **Professional Images** - High-quality stock images from Unsplash integrated throughout
- **Modern UI/UX** - Clean, sophisticated interface with premium animations
- **Glass Morphism Effects** - Contemporary frosted glass design elements
- **Gradient Accents** - Beautiful color transitions and modern styling
- **Image Galleries** - Professional photo grid in About section
- **Background Images** - Stunning hero and contact section backgrounds

### Technical Features
- **Fully Responsive** - Optimized for all devices (mobile, tablet, desktop)
- **Smooth Animations** - Fade-in, slide, and counter animations
- **Parallax Effects** - Dynamic scrolling effects on hero section
- **Interactive Elements** - Hover effects, transitions, and micro-interactions
- **Counter Animations** - Animated statistics and numbers
- **Font Awesome Icons** - Professional iconography throughout
- **Google Fonts** - Poppins font family for modern typography

### Sections
1. **Hero Section** - Full-screen with background image, stats, and CTAs
2. **Trust Badges** - Credibility indicators and quality assurance
3. **Services** - 3 service cards with images and detailed features
   - Customer Service Professionals
   - Sales & Business Development
   - IT & Technical Talent
4. **About Us** - Image grid with company story and features
5. **Why Choose Us** - 4 key advantages with professional styling
6. **Contact** - Full-width image background with glass-effect form
7. **Footer** - Comprehensive footer with quick links

## 📁 Project Structure
```
Website/
├── index.html          # Homepage
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Premium CSS with modern effects
├── script.js           # Enhanced JavaScript with animations
└── README.md          # This file
```

## 🎨 Design Highlights

### Color Scheme
- **Primary**: #1a56db (Professional Blue)
- **Secondary**: #10b981 (Success Green)
- **Accent**: #f59e0b (Amber Gold)
- **Dark**: #0f172a (Deep Navy)

### Professional Images Used
All images are high-quality from Unsplash:
- Hero: Remote team collaboration
- Services: Customer service, sales, IT professionals
- About: Team collaboration, professionals, remote work
- Contact: Sri Lanka landscape

### Modern Effects
- Glass morphism (frosted glass) design
- Gradient overlays on images
- Smooth fade and slide animations
- Interactive hover states
- Counter animations for statistics
- Parallax scrolling
- Backdrop blur effects

## 🏢 Company Information

**Magellan Metrics Private Limited**
- **Company ID**: PV00346753
- **Director**: Pallege Gayan Nanayakkara
- **Location**: No 192/10, Paramount Towers, Level 04, 09th Level, Nawala, 10250, Sri Lanka
- **Website**: www.magellanmetrics.com
- **Email**: info@magellanmetrics.com

**Services Offered**:
- Customer Service Recruitment
- Sales & Business Development Talent
- IT & Technical Professionals
- Remote Staffing Solutions

## 🚀 Deployment Options

### Option 1: Netlify (Recommended - Free & Easy)

1. **Sign up for Netlify**
   - Go to [netlify.com](https://www.netlify.com)
   - Sign up with GitHub, GitLab, or email

2. **Deploy via Drag & Drop**
   - Log in to Netlify Dashboard
   - Click "Add new site" → "Deploy manually"
   - Drag the entire `Website` folder to the upload area
   - Wait for deployment (usually 30 seconds)
   - Your site will be live at: `https://random-name.netlify.app`

3. **Custom Domain (Optional)**
   - In Site Settings → Domain management
   - Add your custom domain (e.g., qovix.ae)
   - Follow DNS configuration instructions

4. **Update Site**
   - Make changes to your files
   - Drag & drop again to deploy updates
   - Or connect to GitHub for automatic deployments

### Option 2: Vercel (Fast & Free)

1. **Sign up for Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Sign up with GitHub, GitLab, or email

2. **Deploy**
   - Click "Add New Project"
   - Select "Import" or drag & drop your folder
   - Vercel will automatically deploy
   - Live at: `https://your-project.vercel.app`

3. **Custom Domain**
   - Go to Project Settings → Domains
   - Add your custom domain
   - Configure DNS records as instructed

### Option 3: GitHub Pages (Free)

1. **Create GitHub Account**
   - Sign up at [github.com](https://github.com)

2. **Create Repository**
   - Click "New Repository"
   - Name it: `magellan-metrics-website`
   - Make it public

3. **Upload Files**
   - Upload `index.html`, `services.html`, `about.html`, `contact.html`, `styles.css`, `script.js`
   - Or use GitHub Desktop/Git commands

4. **Enable GitHub Pages**
   - Go to Repository Settings
   - Scroll to "Pages" section
   - Source: Select "main" branch
   - Save and wait 2-3 minutes
   - Live at: `https://yourusername.github.io/magellan-metrics-website`

### Option 4: Traditional Web Hosting

For hosting providers like GoDaddy, Bluehost, HostGator, etc.:

1. **Purchase Hosting & Domain**
   - Choose a hosting plan
   - Register domain (e.g., qovix.ae)

2. **Access cPanel/File Manager**
   - Log in to your hosting control panel
   - Navigate to File Manager
   - Go to `public_html` directory

3. **Upload Files**
   - Upload all HTML files (`index.html`, `services.html`, `about.html`, `contact.html`), `styles.css`, `script.js`
   - Ensure `index.html` is in the root of `public_html`

4. **Test**
   - Visit your domain (e.g., magellanmetrics.com)
   - Website should be live

## 📧 Contact Form Setup

The contact form currently shows a success message locally. To make it functional:

### Option A: FormSubmit (Free, No Backend)
1. Replace form action in contact forms:
```html
<form id="contactForm" action="https://formsubmit.co/info@magellanmetrics.com" method="POST">
```

### Option B: Formspree (Free Tier Available)
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form
3. Add the endpoint to your form

### Option C: Custom Backend
Uncomment the fetch API code in `script.js` and set up your own backend API.

## 🎨 Customization

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;  /* Main blue color */
    --secondary-color: #1e40af; /* Darker blue */
    --accent-color: #3b82f6;    /* Light blue */
}
```

### Update Contact Information
Edit the contact details in HTML files:
- Email (search for `info@magellanmetrics.com`)
- Company address in Nawala, Sri Lanka

### Add Logo
1. Save your logo as `logo.png` in the Website folder
2. Update the logo section in HTML files:
```html
<div class="logo">
    <img src="logo.png" alt="Magellan Metrics Logo" height="50">
</div>
```

### Add Company Images
Replace the Unsplash placeholder images with actual company photos for a more personalized touch.

## 🔧 Testing Before Deployment

### Test Locally
1. Open `index.html` in a web browser
2. Test all navigation links (Home, Services, About, Contact)
3. Test the contact form
4. Check mobile responsiveness (use browser dev tools)
5. Test on different browsers (Chrome, Firefox, Safari, Edge)

### Check Responsiveness
- Desktop: 1920x1080, 1366x768
- Tablet: 768x1024
- Mobile: 375x667, 414x896

## 📱 Mobile Optimization
The website is fully responsive and includes:
- Mobile-friendly navigation menu
- Touch-optimized buttons
- Responsive grid layouts
- Optimized images and fonts

## 🔒 Security Considerations
- No sensitive data stored
- Form validation included
- HTTPS recommended (free with Netlify/Vercel)

## 📈 SEO Tips
1. Add Google Analytics
2. Submit sitemap to Google Search Console
3. Optimize meta descriptions
4. Add alt text to images (when you add them)
5. Enable HTTPS

## 🌟 Performance
- Minimal dependencies (no frameworks)
- Optimized CSS and JavaScript
- Fast loading times
- Smooth animations

## 💡 Next Steps
1. ✅ Deploy website to hosting platform
2. Set up custom domain (magellanmetrics.com)
3. Configure contact form with real email (info@magellanmetrics.com)
4. Add company logo and team photos
5. Set up Google Analytics
6. Add SSL certificate (usually automatic)
7. Test all functionality on live site
8. Share with stakeholders

## 📞 Support
For issues or questions about the website:
- Check browser console for errors (F12)
- Ensure all files are uploaded correctly
- Verify file paths are correct
- Test on different browsers

## 📝 License
© 2025 Magellan Metrics Private Limited. All rights reserved.

---

**Deployment Checklist:**
- [ ] Choose hosting platform
- [ ] Upload all files (HTML, CSS, JS)
- [ ] Configure custom domain (optional)
- [ ] Set up contact form with info@magellanmetrics.com
- [ ] Add company logo
- [ ] Test all pages and links (Home, Services, About, Contact)
- [ ] Enable HTTPS
- [ ] Set up analytics
- [ ] Launch! 🚀