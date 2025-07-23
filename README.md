# Holy Spirit Church Nadakhal Website

A modern, responsive website for Holy Spirit Church Nadakhal featuring the church's history, mass timings, gallery, and contact information.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Gallery**: Click on images to view them in full-screen modal
- **Contact Form**: Functional contact form with validation
- **Smooth Navigation**: Smooth scrolling and mobile-friendly navigation
- **Mass Timings**: Clear display of all church service timings
- **Church History**: Interactive timeline showing the church's history

## File Structure

```
holy spirit church Nadakhal/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── images/             # Image folder (add your church photos here)
└── README.md          # This file
```

## Customization Guide

### 1. Adding Church Images

Replace the placeholder images in the `images/` folder with actual photos of your church:

**Required Images:**

- `church-main.jpg` - Main church exterior (hero section)
- `church-interior.jpg` - Interior view (about section)
- `church-exterior.jpg` - Another exterior view (gallery)
- `altar.jpg` - Main altar (gallery)
- `stained-glass.jpg` - Stained glass windows (gallery)
- `christmas-mass.jpg` - Christmas mass or special service (gallery)
- `youth-group.jpg` - Youth ministry activities (gallery)
- `community-service.jpg` - Community service activities (gallery)

**Image Specifications:**

- Format: JPG, PNG, or WebP
- Recommended size: 1200x800 pixels for main images
- File size: Under 1MB for faster loading

### 2. Updating Church Information

#### Contact Details (in `index.html`)

Find the contact section and update:

```html
<div class="contact-item">
  <h3>Address</h3>
  <p>
    Holy Spirit Church<br />
    Nadakhal<br />
    [Your District], [Your State]<br />
    India
  </p>
</div>
```

Replace `[Your District]` and `[Your State]` with actual location details.

#### Phone and Email

```html
<div class="contact-item">
  <h3>Phone</h3>
  <p>+91 [Your Phone Number]</p>
</div>

<div class="contact-item">
  <h3>Email</h3>
  <p>holyspirit.nadakhal@gmail.com</p>
</div>
```

#### Parish Priest Name

```html
<div class="contact-item">
  <h3>Parish Priest</h3>
  <p>Rev. Fr. [Priest Name]</p>
</div>
```

### 3. Updating Mass Timings

Find the timings section in `index.html` and modify the schedule:

```html
<div class="timing-card">
  <h3>Sunday Mass</h3>
  <div class="time-slot">
    <span class="time">7:00 AM</span>
    <span class="language">English</span>
  </div>
  <!-- Add more time slots as needed -->
</div>
```

### 4. Customizing Church History

Update the timeline in the history section:

```html
<div class="timeline-item">
  <div class="timeline-year">1950s</div>
  <div class="timeline-content">
    <h3>Foundation Years</h3>
    <p>Your church's founding story...</p>
  </div>
</div>
```

### 5. Color Scheme Customization

To change the color scheme, modify these CSS variables in `styles.css`:

```css
/* Primary church color - currently blue */
#2c5aa0  /* Change this hex code to your preferred color */

/* Secondary color for hover effects */
#1e3f73  /* Darker shade of primary color */
```

Common church color schemes:

- **Traditional Blue**: `#2c5aa0` (current)
- **Burgundy**: `#8B0000`
- **Forest Green**: `#228B22`
- **Purple**: `#6A5ACD`

### 6. Adding New Sections

To add new sections (e.g., ministries, events), follow this pattern:

1. Add navigation link in the navbar
2. Create the section in HTML
3. Add corresponding styles in CSS
4. Update JavaScript for smooth scrolling

### 7. SEO Optimization

Update the page title and meta tags in `<head>`:

```html
<title>Holy Spirit Church Nadakhal - Catholic Parish</title>
<meta
  name="description"
  content="Holy Spirit Church Nadakhal - A Catholic parish serving the community with faith, hope, and love. Mass timings, events, and community services."
/>
<meta
  name="keywords"
  content="Holy Spirit Church, Nadakhal, Catholic, Parish, Mass, Church Services"
/>
```

## Technical Features

### Responsive Breakpoints

- Desktop: 1200px and above
- Tablet: 768px - 1199px
- Mobile: 767px and below

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

### Performance Features

- Optimized images
- Smooth scrolling
- Lazy loading animations
- Minimal JavaScript for fast loading

## Deployment Options

### 1. GitHub Pages (Free)

1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be available at `username.github.io/repository-name`

### 2. Netlify (Free)

1. Create account at netlify.com
2. Drag and drop your project folder
3. Get instant live URL

### 3. Traditional Web Hosting

1. Purchase hosting from providers like Hostinger, Bluehost, etc.
2. Upload files via FTP
3. Point your domain to the hosting

## Contact Form Setup

The contact form currently shows success messages but doesn't actually send emails. To make it functional:

### Option 1: Formspree (Recommended)

1. Sign up at formspree.io
2. Get your form endpoint
3. Update the form action in HTML:

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST"></form>
```

### Option 2: EmailJS

1. Sign up at emailjs.com
2. Follow their integration guide
3. Update the JavaScript contact form handler

## Maintenance Tips

1. **Regular Updates**: Update mass timings, events, and news regularly
2. **Image Optimization**: Compress images before uploading
3. **Content Review**: Review and update content quarterly
4. **Backup**: Keep regular backups of your website files
5. **Security**: If using a CMS, keep it updated

## Support

For technical support or customization help, you can:

1. Modify the code directly (HTML/CSS/JS knowledge required)
2. Hire a web developer for advanced customizations
3. Use online resources and tutorials for web development

## License

This website template is free to use and modify for religious and non-commercial purposes.

---

**God Bless!**

May this website serve your parish community well and help spread the message of faith, hope, and love.
