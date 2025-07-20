# Studio Anjou - Static Website

A clean, minimal static website for Studio Anjou featuring a "coming soon" page with social sharing functionality.

## Structure

```
studioanjou/
├── index.html              # Main HTML file
├── assets/
│   ├── images/             # All image assets
│   │   ├── studio-logo.png
│   │   ├── morris-dancer.jpg
│   │   ├── favicon-32x32.png
│   │   ├── favicon-192x192.png
│   │   └── apple-touch-icon.png
│   ├── fonts/              # Font files
│   │   ├── SourceSerif4Variable-Roman.ttf.woff2
│   │   └── SourceSerif4Variable-Italic.ttf.woff2
│   └── css/                # Stylesheets
│       └── main.css
└── README.md
```

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Local Assets**: All images, fonts, and CSS are hosted locally
- **Clean Code**: Minimal HTML structure with optimized CSS
- **SEO Optimized**: Includes proper meta tags and Open Graph data
- **Fast Loading**: Optimized for static hosting
- **Social Sharing**: Built-in social media sharing buttons

## Local Development

To run the site locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

This static site can be deployed to any static hosting service:

- **Netlify**: Drag and drop the folder or connect to Git
- **Vercel**: Connect your Git repository
- **GitHub Pages**: Push to a repository and enable Pages
- **AWS S3**: Upload files to an S3 bucket with static website hosting
- **Cloudflare Pages**: Connect your Git repository

## Live Site

The live site can be found at: https://studioanjou.com/