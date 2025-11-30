# Anil Tech Systems - Enterprise IT Solutions Website

A professional, responsive, multi-page static website for Anil Tech Systems, an ISO-9001 certified enterprise B2B IT services company.

## Project Structure

```
├── index.html                     # Homepage
├── about.html                     # About Us page
├── contact.html                   # Contact page with Netlify form
├── services/
│   ├── system-integration.html    # System Integration service
│   ├── datacenter.html            # Datacentre Solutions service
│   ├── cloud.html                 # Cloud Solutions service
│   ├── digital-transformation.html # Digital Transformation service
│   ├── security-surveillance.html # Security & Surveillance service
│   └── training.html              # Enterprise Training service
├── css/
│   └── style.css                  # Main stylesheet
├── js/
│   └── main.js                    # JavaScript (dropdown, hamburger, scroll)
├── assets/                        # Images and media files
├── robots.txt                     # SEO robots file
├── sitemap.xml                    # XML sitemap for search engines
└── README.md                      # This file
```

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Accessible Navigation**: Keyboard-accessible dropdown menus with ARIA attributes
- **Mobile Menu**: Hamburger menu with accordion-style services submenu
- **SEO Optimized**: Unique titles, meta descriptions, JSON-LD schema on every page
- **Netlify Forms**: Contact form ready for Netlify form handling
- **WhatsApp Integration**: Floating WhatsApp button for quick contact
- **Smooth Animations**: Scroll reveal effects and hover interactions
- **No External Dependencies**: Pure vanilla HTML, CSS, and JavaScript

## Before You Deploy

### 1. Update Placeholder Content

Search for `TODO` comments in the files and update:

- **Logo**: Replace the logo placeholder in the header
- **WhatsApp Number**: Update `91XXXXXXXXXX` with your actual WhatsApp number
- **Contact Details**: Update address, phone, and email in footer and contact page
- **Case Study Metrics**: Add real numbers to case study cards
- **Client Logos**: Add actual client logo images
- **Images**: Add hero image and other visual assets

### 2. Update URLs

Replace `https://example.com` with your actual domain in:
- All HTML files (canonical URLs, Open Graph URLs)
- `sitemap.xml`
- `robots.txt`

### 3. Image Guidelines

- **Hero images**: 150-300 KB, JPG or WebP format
- **Thumbnails**: 40-80 KB
- **Logo**: SVG format recommended for best quality

---

## Netlify Deployment

### Method 1: Drag and Drop (Quickest)

1. Go to [Netlify](https://app.netlify.com/)
2. Sign up or log in to your account
3. Click on **"Add new site"** → **"Deploy manually"**
4. Drag and drop your project folder onto the deploy area
5. Wait for deployment to complete
6. Your site is live! Netlify will provide a random URL like `random-name.netlify.app`

### Method 2: GitHub → Netlify (Recommended for Updates)

#### Step 1: Upload to GitHub

1. Create a [GitHub account](https://github.com/) if you don't have one
2. Click the **"+"** icon → **"New repository"**
3. Name it (e.g., `anil-tech-website`)
4. Keep it **Public** (or Private if you prefer)
5. Click **"Create repository"**
6. Upload your files:
   - Click **"uploading an existing file"**
   - Drag all project files and folders
   - Click **"Commit changes"**

#### Step 2: Connect to Netlify

1. Go to [Netlify](https://app.netlify.com/)
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **"GitHub"**
4. Authorize Netlify to access your GitHub
5. Select your repository
6. Leave build settings empty (it's a static site)
7. Click **"Deploy site"**

#### Step 3: Custom Domain (Optional)

1. In Netlify, go to **Site settings** → **Domain management**
2. Click **"Add custom domain"**
3. Enter your domain name
4. Follow DNS configuration instructions

### Netlify Forms Setup

The contact form is already configured for Netlify. After deployment:

1. Submit a test form on your live site
2. Go to Netlify dashboard → **Forms**
3. You'll see the form submissions there
4. Set up email notifications in **Site settings** → **Forms** → **Form notifications**

**Important**: Netlify parses forms at build time. If the form isn't detected:
- Make sure `data-netlify="true"` is on the form
- Make sure the hidden `form-name` input exists
- Redeploy the site

---

## Future GitHub Integration

With your site connected to GitHub via Netlify:

1. **Automatic Deployments**: Any changes pushed to GitHub automatically deploy
2. **Version Control**: Track all changes to your website
3. **Collaboration**: Multiple team members can update the site
4. **Rollback**: Easily revert to previous versions if needed

### Making Updates

1. Edit files locally or on GitHub
2. Commit and push changes
3. Netlify automatically rebuilds and deploys

---

## Technology Stack

- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Custom properties, Flexbox, Grid, animations
- **JavaScript**: Vanilla JS, no frameworks or libraries
- **Netlify**: Hosting and form handling

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Performance Tips

1. Optimize images before uploading (use [TinyPNG](https://tinypng.com/) or [Squoosh](https://squoosh.app/))
2. Use WebP format for images where possible
3. Keep hero images under 300 KB
4. Use SVG for logos and icons

## License

Copyright © 2024 Anil Tech Systems. All rights reserved.

---

## Need Help?

For technical support or customization requests, contact Anil Tech Systems.
