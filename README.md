# Studio Anjou - Static Website

This is a static HTML version of the Studio Anjou WordPress website, converted for static hosting.

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
- **Clean Code**: Simplified HTML structure without WordPress dependencies
- **SEO Optimized**: Includes proper meta tags and Open Graph data
- **Fast Loading**: Optimized for static hosting

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

## Original Source

This was converted from a WordPress site using the Twenty Twenty-Two theme. The original site can be found at: https://studioanjou.com/

## License

The original WordPress theme (Twenty Twenty-Two) is licensed under the GNU GPL v2 or later. 

https://www.facebook.com/sharer/sharer.php?u=https://studioanjou.com/