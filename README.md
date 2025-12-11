# Restaurant-Demo-1
# Flavor Haven - California Burger Joint Demo Website

A modern, responsive website template designed for California-style burger joints and casual dining restaurants. This demo showcases a vibrant, user-friendly design perfect for small restaurant businesses looking to establish their online presence.

##  Purpose

This is a **business demo template** for restaurant owners who want:
- A professional online presence without complex setup
- Mobile-friendly design that works on all devices
- Easy-to-update menu sections
- Clear contact information and location integration
- Modern California burger joint aesthetic

##  Features

- **Hero Section**: Eye-catching full-screen banner with call-to-action
- **Menu Favorites**: Highlighted popular items with images and pricing
- **Complete Menu**: Organized by category (Burgers, Tacos & Mexican, Sides, Drinks)
- **Contact Integration**: Phone, social media, and direct call button
- **Location Map**: Embedded Google Maps for easy navigation
- **Customer Testimonials**: Social proof section
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Navigation**: Fixed navbar with scroll effects

## Setup Instructions

### Option 1: Simple Setup (No Installation Required)

1. **Download the files**
```bash
   git clone [your-repo-url]
   cd flavor-haven-demo
```

2. **Open in browser**
   - Simply double-click `index.html` or
   - Right-click → Open with → Your preferred browser

3. The website is ready to view.

 **Using VS Code**
   - Install "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

## Customization Guide

### Update Business Information

1. **Restaurant Name**: Search for "Flavor Haven" and replace throughout
2. **Phone Number**: Replace `(555) 123-4567` with your actual number
3. **Address**: Update `123 Main Street, California` in the location section
4. **Social Media**: Replace `@FlavorHavenCA` with your handles

### Update Menu Items

Find the menu sections in the HTML and update:
```html
<h4>Your Item Name - $XX.XX</h4>
<p>Your item description</p>
```

### Change Colors

The main colors are defined in the CSS:
- Primary Orange: `#FF6B35`
- Accent Gold: `#FFD700`
- Update these hex codes to match your brand

### Update Images

Replace image URLs with your own:
```html
<img src="your-image-path.jpg" alt="Description">
```

Or use your own image hosting service (Cloudinary, Imgur, etc.)

### Embed Your Location

1. Go to [Google Maps](https://www.google.com/maps)
2. Search for your business address
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the existing iframe in the Location section

## Browser Compatibility

-  Chrome/Edge (recommended)
- Firefox
-  Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom styling with flexbox and grid
- **JavaScript**: Vanilla JS for interactions
- **Tailwind CDN**: Utility classes (via CDN, no build required)
- **Google Maps Embed**: Location integration
- **Unsplash**: Demo images (replace with your own)

## File Structure
```
flavor-haven-demo/
│
├── index.html          # Main website file (everything in one file)
└── README.md          # This file
```

## Design Philosophy

This template follows modern web design principles:
- **Mobile-first**: Optimized for smartphones and tablets
- **Performance**: Single-file architecture for fast loading
- **Accessibility**: Semantic HTML and proper contrast ratios
- **User Experience**: Clear navigation and call-to-actions

## Business Use Cases

Perfect for:
- Burger restaurants
- Taco shops
- Casual dining establishments
- Food trucks wanting a web presence
- Pop-up restaurants
- Fast-casual eateries



## Updates

**Version 1.0** (December 2025)
- Initial release with complete restaurant website template
- Mobile-responsive design
- Full menu display with categories
- Integrated contact and location features
