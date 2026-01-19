# ReFaz Website - Deployment Guide

## ✅ What's Included

Your complete ReFaz website with Blockchain na Escola (BnE) integrated as a subfolder.

### Main Website Files (Root Directory):
- `index.html` - Homepage with hero card design
- `about.html` - About page with founders
- `Media.html` - Media and articles
- `Contact.html` - Contact information  
- `projects.html` - Projects showcase (includes BnE link)
- `refaz.css` - Main stylesheet (green/purple/yellow branding)
- `README.md` - Basic readme

### BnE Subfolder (`/bne/`):
- `index.html` - BnE homepage with stats
- `about.html` - Mission and history
- `impact.html` - Impact metrics and success stories
- `partners.html` - Partnership ecosystem (44+ partners)
- `projects.html` - Key initiatives (EduLatam, workshops, events)
- `publications.html` - Articles and media coverage
- `contact.html` - Contact information
- `bne-styles.css` - BnE-specific styles

## 🎯 Website Structure

```
refaz-website/
├── index.html
├── about.html
├── Media.html
├── Contact.html
├── projects.html
├── refaz.css
├── README.md
└── bne/
    ├── index.html
    ├── about.html
    ├── impact.html
    ├── partners.html
    ├── projects.html
    ├── publications.html
    ├── contact.html
    └── bne-styles.css
```

## 🚀 Deployment Steps

### Option 1: GitHub Pages (Recommended)

1. **Upload to GitHub:**
   - Go to your repository: https://github.com/ReFaz0x/refaz0x
   - Click "Add file" → "Upload files"
   - Drag ALL files maintaining the folder structure
   - Commit changes

2. **Enable GitHub Pages:**
   - Go to Settings → Pages
   - Source: Deploy from branch
   - Branch: main (or master)
   - Folder: / (root)
   - Click "Save"

3. **Access Your Site:**
   - Your site will be live at: `https://refaz0x.github.io/refaz0x/`
   - Wait 2-5 minutes for deployment

### Option 2: Vercel

1. Connect your GitHub repository to Vercel
2. Deploy with default settings
3. Your site will be live instantly

### Option 3: Custom Domain

1. Deploy using GitHub Pages or Vercel
2. Add custom domain in settings
3. Update DNS records

## 📋 Pre-Deployment Checklist

- [ ] All files uploaded to repository
- [ ] Folder structure preserved (bne/ subfolder intact)
- [ ] Both CSS files included (refaz.css and bne/bne-styles.css)
- [ ] All links working locally
- [ ] GitHub Pages enabled
- [ ] Deployment completed (wait 2-5 minutes)

## 🧪 Testing After Deployment

Visit these pages to verify everything works:

**Main Site:**
- Homepage: `https://refaz0x.github.io/refaz0x/`
- About: `https://refaz0x.github.io/refaz0x/about.html`
- Projects: `https://refaz0x.github.io/refaz0x/projects.html`
- Contact: `https://refaz0x.github.io/refaz0x/Contact.html`

**BnE Section:**
- BnE Home: `https://refaz0x.github.io/refaz0x/bne/index.html`
- Impact: `https://refaz0x.github.io/refaz0x/bne/impact.html`
- Partners: `https://refaz0x.github.io/refaz0x/bne/partners.html`

## 🎨 Design Features

**Main Site:**
- Green/purple/yellow color scheme
- Conic gradient brand badge
- Hero card design
- Sticky header navigation

**BnE Section:**
- Blue gradient hero section
- Stats dashboard
- Partner cards
- Timeline design
- Breadcrumb navigation

## 📝 Key Changes from Previous Version

✅ **Preserved:** Current repository structure with simpler design
✅ **Added:** Complete BnE section with 7 pages
✅ **Integrated:** BnE link in main navigation
✅ **Maintained:** Clean, minimalist aesthetic

## 🔧 Troubleshooting

**Issue: Pages not loading**
- Check folder structure is correct
- Verify all files uploaded
- Wait 5 minutes after deployment
- Clear browser cache

**Issue: CSS not loading**
- Confirm refaz.css is in root directory
- Confirm bne-styles.css is in bne/ folder
- Check file paths in HTML

**Issue: BnE pages show 404**
- Verify bne/ folder exists
- Check all BnE files are in bne/ subfolder
- Ensure folder name is lowercase "bne"

## 📞 Need Help?

- Check GitHub Pages deployment status in repository Settings
- Verify all files are in correct locations
- Test locally by opening index.html in browser

## 🎉 You're All Set!

Your website is ready to deploy. Just upload everything to GitHub and enable Pages!

---

© 2025 ReFaz - Marcelo Silva & Verber Souza
