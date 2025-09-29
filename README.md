# TikTok Content Posting API Demo - Legal Pages

This repository contains the Terms of Service and Privacy Policy pages for the TikTok Content Posting API Demo application.

## 🌐 Live Pages

- **Terms of Service**: https://your-domain.com/terms-of-service.html
- **Privacy Policy**: https://your-domain.com/privacy-policy.html

## 🚀 Setup Instructions

### 1. GitHub Pages Configuration
1. Go to your repository Settings
2. Scroll to "Pages" section
3. Set Source to "Deploy from a branch"
4. Select "main" branch and "/ (root)" folder
5. Click Save

### 2. Custom Domain Setup (For HTTPS)
1. Purchase a domain from a registrar (GoDaddy, Namecheap, etc.)
2. Add a `CNAME` file to your repository root with your domain
3. Configure DNS records at your domain registrar:
   ```
   Type: CNAME
   Name: @ (or www)
   Value: yourusername.github.io
   ```
4. In GitHub Pages settings, add your custom domain
5. Enable "Enforce HTTPS" (available after DNS propagation)

### 3. Alternative: Cloudflare Pages (Recommended for HTTPS)
1. Sign up for Cloudflare Pages (free)
2. Connect your GitHub repository
3. Deploy with these settings:
   - Build command: (leave empty)
   - Output directory: /
4. Add your custom domain in Cloudflare
5. HTTPS is automatically enabled with Cloudflare SSL

## 📁 File Structure
```
/
├── index.html              # Optional landing page
├── terms-of-service.html   # Terms of Service
├── privacy-policy.html     # Privacy Policy
├── CNAME                   # Custom domain configuration
├── _config.yml            # Jekyll configuration
└── styles/
    ├── terms-of-service.css
    └── privacy-policy.css
```

## 🔒 HTTPS Implementation

### Option 1: GitHub Pages + Custom Domain
- **Free SSL**: Automatic with custom domain
- **Setup Time**: 24-48 hours for DNS propagation
- **Requirements**: Custom domain purchase

### Option 2: Cloudflare Pages
- **Free SSL**: Immediate
- **Setup Time**: 5-10 minutes
- **Requirements**: Free Cloudflare account

### Option 3: Netlify
- **Free SSL**: Immediate
- **Setup Time**: 5-10 minutes
- **Requirements**: Free Netlify account

## 🛠 Development

To run locally:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server -p 8000
```

Then visit: http://localhost:8000

## 📋 Checklist

- [ ] Repository created on GitHub
- [ ] Files uploaded to repository
- [ ] GitHub Pages enabled
- [ ] Custom domain configured (if desired)
- [ ] DNS records updated
- [ ] HTTPS enforced
- [ ] Links tested

## 🔗 Useful Links

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Custom Domain Setup](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [Cloudflare Pages](https://pages.cloudflare.com/)
- [Netlify](https://www.netlify.com/)

---

**Note**: Replace `your-domain.com` and `yourusername` with your actual domain and GitHub username.