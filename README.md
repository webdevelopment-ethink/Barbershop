# Andrew Costas Barbershop Website

A modern, responsive single-page website for Andrew Costas Barbershop featuring call-only booking.

## Features

- **Mobile-first responsive design** with charcoal/white/warm earthy color scheme
- **Call-only booking** - no online forms, just click-to-call functionality
- **Sticky header** with prominent call button
- **Services & pricing** clearly displayed
- **Opening hours** in an easy-to-read format
- **Product showcase** featuring available grooming products
- **SEO optimized** with meta tags, Open Graph, and LocalBusiness schema
- **Accessibility features** including skip links, ARIA labels, and keyboard navigation
- **Fast performance** with lazy loading images and minimal JavaScript

## Structure

```
/
├── index.html          # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css  # All styles (no inline CSS)
│   └── js/
│       └── main.js     # Mobile navigation and UX enhancements
├── products.JPG        # Product showcase image
└── README.md          # This file
```

## Deployment

This is a static website that can be deployed to any web hosting service:

### GitHub Pages
1. Push to a GitHub repository
2. Enable GitHub Pages in Settings > Pages
3. Select source branch and folder

### Netlify
1. Drag and drop the project folder to Netlify
2. Site will be live immediately

### Vercel
1. Import the project to Vercel
2. Deploy with default settings

### Traditional Hosting
Simply upload all files to your web server's public directory.

## Local Development

To run locally:
```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx http-server

# Then open http://localhost:8000
```

## Contact Information

- **Business**: Andrew Costas Barbershop
- **Address**: 172 Cavendish Rd, Coorparoo QLD 4151
- **Phone**: (07) 3394 2007
- **Booking**: Phone only - no online bookings

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers on iOS and Android

## Performance

The site is optimized for fast loading with:
- Minimal CSS and JavaScript
- Lazy loading images
- No external dependencies except Google Fonts
- Efficient caching headers (configure on your server)
