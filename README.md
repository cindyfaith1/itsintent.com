# Intelligent Entertainment Website

A modern, professional website for Intelligent Entertainment (IE LLC) built with HTML, CSS, and JavaScript.

## Site Structure

- **index.html** - Home/About page with team bios
- **video-gallery.html** - Video gallery page (Vimeo embeds)
- **film-projects.html** - Film & TV projects showcase
- **photo-gallery.html** - Photo gallery
- **services.html** - Services page
- **contact.html** - Contact form and information
- **styles.css** - Main stylesheet
- **gallery.css** - Gallery-specific styles

## Features

- Responsive design (mobile, tablet, desktop)
- Vimeo video integration (embedded)
- Clean, professional layout
- Navigation dropdown menu
- Team member profiles
- Contact form
- Photo and video galleries

## How to Deploy to Netlify

### Option 1: Direct Netlify Deploy (Recommended)

1. **Push to GitHub:**
   - Create a GitHub repository
   - Push all files to your repo
   - Make sure `netlify.toml` is included

2. **Connect to Netlify:**
   - Go to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Select GitHub and authorize
   - Select your repository
   - Click "Deploy site"

3. **Custom Domain:**
   - In Netlify, go to Site Settings > Domain management
   - Add your custom domain (e.g., itsintent.com)
   - Follow DNS configuration instructions

### Option 2: Drag & Drop Deploy

1. Go to [netlify.com](https://netlify.com)
2. Click "Deploy sites" 
3. Drag and drop the entire project folder
4. Your site will be live immediately

## Important: Replace Placeholder Content

Before deploying, you'll need to update:

1. **Vimeo Video IDs:**
   - Replace `VIDEO_ID_1`, `VIDEO_ID_2`, etc. in `video-gallery.html` and `index.html` with your actual Vimeo video IDs
   - Example: `https://player.vimeo.com/video/123456789`

2. **Team Photos:**
   - Add actual team member photos to an `images/` folder
   - Update image paths in `index.html`

3. **Project Images:**
   - Update placeholder images in `film-projects.html` and `photo-gallery.html`

4. **Contact Email:**
   - Update email address in `contact.html` with your actual email

5. **Company Information:**
   - Update address and contact details in `contact.html`

## File Structure

```
project/
├── index.html
├── video-gallery.html
├── film-projects.html
├── photo-gallery.html
├── services.html
├── contact.html
├── styles.css
├── gallery.css
├── netlify.toml
├── images/          (create this folder and add your images)
└── README.md
```

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --black: #000;
    --white: #fff;
    --gray-light: #f5f5f5;
    --gray-dark: #333;
    --text-primary: #000;
    --text-secondary: #666;
}
```

### Typography
Modify font sizes and weights in the respective CSS files.

### Navigation
Update links in the nav menus within each HTML file.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Notes

- Videos are hosted on Vimeo (not stored locally)
- Images should be optimized before uploading
- CSS is minimal for fast loading
- Responsive images reduce bandwidth on mobile

## Contact Form

The contact form in `contact.html` is a placeholder. To make it functional:

1. **Option A: Netlify Forms**
   - Add `netlify` attribute to the form
   - Netlify will automatically handle submissions

2. **Option B: FormSubmit.co**
   - Change form action to: `https://formsubmit.co/your-email@example.com`

3. **Option C: Custom Backend**
   - Set up a backend service (Zapier, Make, etc.)
   - Point form action to your service endpoint

## Support & Maintenance

- Regularly update content and images
- Monitor analytics in Netlify dashboard
- Test across different devices
- Keep videos and images optimized

---

Built with HTML5, CSS3, and responsive design principles.
