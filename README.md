# Complete Window Cleaning Website

A professional Jekyll-based single page website for Complete Window Cleaning, designed to be hosted on GitHub Pages.

## Features

- **Responsive Design**: Mobile-first approach that looks great on all devices
- **SEO Optimised**: Schema markup, meta tags, and fast loading times
- **Modern UI**: Clean, professional design with smooth animations
- **Contact Form**: Integrated contact form for quote requests
- **Gallery Section**: Showcase before/after photos and work examples
- **Local Business Focus**: Optimised for local search and customer conversion

## Setup Instructions

### 1. GitHub Pages Setup
Since this is already in your `quirkules.github.io` repository:

1. **Enable GitHub Pages**:
   - Go to your repository settings on GitHub
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save settings

2. **Your site will be live at**: `https://quirkules.github.io`

### 2. Customise Business Information

Edit `_config.yml` to update:
- Business phone number (currently: 0412 345 678)
- Email address (currently: info@completewindowcleaning.com.au)
- Service areas and hours
- Social media links

### 3. Set Up Contact Form

1. **Sign up for Formspree** (free tier available): https://formspree.io/
2. Create a new form and get your form endpoint
3. In `index.html`, find this line:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
4. Replace `YOUR_FORM_ID` with your actual Formspree form ID

### 4. Add Professional Photos

Place your photos in `/assets/images/`:
- `hero-bg.jpg` - Main banner background (1920x1080px recommended)
- `about-image.jpg` - About section photo (800x600px recommended)
- In `/assets/images/gallery/`:
  - `before-after-1.jpg`
  - `commercial-1.jpg`
  - `pressure-wash-1.jpg`
  - `gutter-clean-1.jpg`

### 5. Optional: Google Analytics

1. Create a Google Analytics property
2. In `_config.yml`, update:
   ```yaml
   google_analytics: "G-XXXXXXXXXX"
   ```

## File Structure

```
quirkules.github.io/
├── _config.yml              # Site configuration and business details
├── _layouts/default.html    # Main page template
├── index.html              # Homepage content
├── assets/
│   ├── css/style.scss      # Main stylesheet
│   ├── js/main.js          # JavaScript functionality
│   └── images/             # Business photos
├── Gemfile                 # Jekyll dependencies
└── README.md              # This file
```

## Content Sections

The single page includes:
- **Hero Section**: Eye-catching banner with call-to-action
- **About Section**: Business story and credentials
- **Services Section**: Service descriptions and pricing
- **Gallery Section**: Before/after photos and work examples
- **Testimonials Section**: Customer reviews
- **Contact Section**: Contact form and business information

## Local Development (Optional)

To test the site locally before publishing:

1. **Install Ruby and Jekyll** (if not already installed)
2. **Run these commands in the repository folder**:
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
3. **View at**: http://localhost:4000

## Next Steps

1. **Update business details** in `_config.yml`
2. **Set up Formspree** for the contact form
3. **Add professional photos** to the images folder
4. **Test the site** on mobile devices
5. **Commit and push changes** to GitHub
6. **Check your live site** at https://quirkules.github.io

## Important Notes

- The site is fully responsive and mobile-optimised
- All contact information is placeholder data - update with real details
- The gallery images are referenced but you'll need to add actual photos
- Form submissions won't work until you set up Formspree
- The site includes Australian spelling and formatting

Your professional window cleaning website will be live as soon as you push these changes to GitHub!