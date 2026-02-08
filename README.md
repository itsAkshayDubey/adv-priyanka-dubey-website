# Adv. Priyanka Dubey - Professional Law Website

A modern, professional static website for Adv. Priyanka Dubey's legal practice in Chhatrapati Sambhajinagar (Aurangabad), Maharashtra.

## Directory Structure

```
website/
├── index.html                 # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css        # All styles
│   ├── js/
│   │   └── script.js         # All JavaScript
│   └── images/
│       └── legal-image.jpg   # Legal profession image
└── README.md                  # This file
```

## Features

✅ **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
✅ **Modern & Professional** - Clean, sophisticated design suitable for legal professionals
✅ **SEO Optimized** - Proper meta tags and semantic HTML structure
✅ **Fast Loading** - Optimized code with minimal dependencies
✅ **Contact Integration** - Direct WhatsApp, Email, Phone, and LinkedIn links
✅ **Interactive Elements** - Smooth scrolling, animations, and hover effects
✅ **Legal Disclaimers** - Compliant with Bar Council of India rules
✅ **Mobile Menu** - Touch-friendly navigation for mobile users
✅ **Dynamic Copyright** - Auto-updates year based on IST timezone

## Quick Start

1. **Download the entire `website` folder**
2. **Open `index.html`** in any web browser to view the website
3. **Customize the content** as needed (see instructions below)
4. **Deploy** to any web hosting service

## Customization Guide

### Updating Contact Information

Open `index.html` and find the contact section. Update:

- **Phone Number**: Search for `+919272104678` and replace
- **Email**: Search for `adv.dubeypriyanka@gmail.com` and replace
- **Address**: Update the address in the contact section
- **WhatsApp Link**: Update the WhatsApp number in both floating button and contact section
- **LinkedIn**: Search for the LinkedIn URL and update

### Adding Your Photo

Replace the placeholder images:

1. **Hero Photo**: Replace `assets/images/profile-photo.jpg` with your professional photo (800x1000px recommended, 4:5 ratio)
2. **Avatar**: Use the same photo - it will be automatically cropped to circular

Update the HTML:
```html
<!-- For hero section (around line 77) -->
<img src="assets/images/profile-photo.jpg" alt="Adv. Priyanka Dubey" class="profile-img">

<!-- For navigation avatar (around line 26) -->
<img src="assets/images/profile-photo.jpg" alt="Adv. Priyanka Dubey" class="nav-avatar">
```

### Changing Colors

Open `assets/css/styles.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: #164e63;  /* Main brand color */
    --accent-color: #d4af37;   /* Gold accent color */
    /* Modify other colors as needed */
}
```

### Adding Practice Areas

In `index.html`, find the Practice Areas section and add new cards following this pattern:

```html
<div class="practice-card">
    <div class="practice-number">08</div>
    <h3 class="practice-title">Your Practice Area</h3>
    <p class="practice-description">Description of this practice area.</p>
</div>
```

### Updating Experience

In the About section and hero stats, update:
- "2+ Years of Practice" 
- "50+ Cases Handled"
- "100+ Satisfied Clients"

## Deployment Options

### Option 1: GitHub Pages (Free)

1. Create a GitHub account at https://github.com
2. Create a new repository
3. Upload the entire `website` folder contents to the repository
4. Go to Settings → Pages
5. Select the main branch and save
6. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Create an account at https://netlify.com
2. Drag and drop the `website` folder
3. Your site will be deployed instantly
4. Free custom domain support available

### Option 3: Vercel (Free)

1. Create an account at https://vercel.com
2. Import your project from GitHub or upload the `website` folder
3. Deploy with one click
4. Free SSL certificate included

### Option 4: Traditional Web Hosting

1. Purchase hosting from services like:
   - Hostinger (India-specific)
   - Bluehost
   - GoDaddy
   - BigRock (India)
2. Upload the entire `website` folder via FTP or cPanel File Manager
3. Point your domain to the hosting

**Important**: Upload the entire folder structure. The website needs all files in their respective directories to work properly.

## Custom Domain Setup

After deploying, you can connect a custom domain like:
- `www.priyankadubey.com`
- `www.advocatepriyankadubey.in`
- `www.advpriyankadubey.co.in`

Most hosting providers offer domain registration and setup assistance.

## Court Jurisdictions Covered

- **High Court** - Bombay High Court, Aurangabad Bench
- **District Court** - Civil & Criminal Matters
- **MAT** - Maharashtra Administrative Tribunal
- **DRT** - Debt Recovery Tribunal

## Practice Areas Included

1. Civil Litigation
2. Criminal Law
3. Family Law
4. Women's Rights
5. Administrative Law (MAT)
6. Debt Recovery (DRT)
7. Legal Consultation

## Adding a Contact Form Backend

The current form opens the user's email client. To collect submissions directly:

### Using Formspree (Free tier available)
1. Sign up at https://formspree.io
2. Get your form endpoint
3. Update the form in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
```

### Using EmailJS (Free tier available)
1. Sign up at https://emailjs.com
2. Follow their setup guide to integrate
3. Update the JavaScript in `assets/js/script.js`

## SEO Optimization Tips

1. **Submit to Google Search Console** - https://search.google.com/search-console
2. **Create a Google My Business listing** - Free local SEO
3. **Add structured data** for local business
4. **Regularly update content** to keep it fresh
5. **Get listed in legal directories**

## Browser Compatibility

The website works on:
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **Page Size**: ~150KB total (HTML + CSS + JS + Images)
- **Load Time**: <2 seconds on average connection
- **Optimized images**: Legal image optimized for web
- **Optimized for mobile** data usage

## File Descriptions

### index.html
Main HTML file containing all content and structure. This is the file browsers will load first.

### assets/css/styles.css
All styling including:
- Layout and positioning
- Colors and typography
- Responsive design breakpoints
- Animations and transitions

### assets/js/script.js
All interactive functionality:
- Mobile menu toggle
- Smooth scrolling
- Form handling
- Copyright year auto-update (IST)
- Scroll-to-top button
- Animation triggers

### assets/images/legal-image.jpg
Professional legal image showing scales of justice, gavel, and law books used in the About section.

## Maintenance

### Regular Updates Recommended:
- Update years of experience annually
- Update case and client statistics
- Add new practice areas as you expand
- Update contact information if changed
- Keep professional photos current

## Legal Compliance

The website includes:
- ✅ Bar Council of India compliant disclaimers
- ✅ No client solicitation language
- ✅ Informational purpose statement
- ✅ No misleading claims
- ✅ Professional presentation
- ✅ Proper MAT designation (Maharashtra Administrative Tribunal)

## Support & Customization

For additional customization or technical support:
- Hire a web developer on platforms like Upwork or Fiverr
- Contact local web design agencies in Aurangabad
- Use online tutorials for HTML/CSS modifications

## Additional Features You Can Add

1. **Blog Section** - Share legal insights and articles
2. **Case Studies** - Anonymized success stories (with permissions)
3. **Client Testimonials** - With proper permissions
4. **Legal Resources** - Downloadable PDFs, guides
5. **Appointment Booking** - Integration with Calendly or similar
6. **Multilingual Support** - Add Hindi/Marathi translations
7. **Live Chat** - Integrate Tawk.to or similar
8. **Google Maps** - Embed office location
9. **Social Media Links** - Add more platforms as needed
10. **Newsletter Signup** - Build email list with Mailchimp

## Important Notes

- Always maintain backups of your files
- Test all contact links before going live
- Regularly check all links are working
- Keep content professional and accurate
- Update privacy policy if collecting data
- Consider adding analytics (Google Analytics) to track visitors
- The copyright year updates automatically based on IST timezone

## Technical Details

- **HTML5** - Modern semantic markup
- **CSS3** - Custom properties, flexbox, grid
- **Vanilla JavaScript** - No framework dependencies
- **Google Fonts** - Cormorant Garamond & Urbanist
- **SVG Icons** - Scalable vector graphics for crisp display

## Troubleshooting

**Images not showing:**
- Ensure all files maintain the exact folder structure
- Check that image paths in HTML match the actual file locations
- Image paths are case-sensitive on some servers

**Styles not applying:**
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Check that styles.css path is correct in index.html
- Ensure no typos in file names

**Form not working:**
- Current form opens email client by default
- For advanced form handling, integrate with Formspree or EmailJS
- Test mailto links in different browsers

## License

This website template is created for Adv. Priyanka Dubey's personal use. Modification and customization for personal practice is permitted.

---

**Created with modern web technologies and attention to professional legal standards.**

For questions about the website, consult with a web developer or digital marketing professional.

**Last Updated**: February 2026
**Version**: 2.0
