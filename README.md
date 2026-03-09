# UNSW PPE Society Website

Welcome to the official website of the UNSW Politics, Philosophy, and Economics Society!

## 🌐 Website Structure

This is a modern, responsive website built with:
- **HTML5** - Structure
- **CSS3** - Styling with custom color scheme matching the PPE Society logo
- **Bootstrap 5** - Responsive framework
- **JavaScript** - Interactivity and animations
- **Font Awesome** - Icons

## 📁 Project Structure

```
PPE Society/
├── index.html          # Home page
├── about.html          # About us and executive team
├── events.html         # Events calendar
├── resources.html      # Study resources and reading lists
├── blog.html           # Blog posts and articles
├── contact.html        # Contact form and sign-up
├── css/
│   └── style.css      # Custom styles
├── js/
│   └── script.js      # JavaScript functionality
├── images/
│   └── logo.png       # Society logo (add your logo here)
└── README.md          # This file
```

## 🚀 Getting Started


#### Update Executive Team (about.html)
- Add/remove team member cards
- Replace placeholder names with actual executive members

#### Add Events (events.html)
- Update the event cards with actual dates, times, and locations
- Remove the "Coming Soon" placeholders

#### Integrate Google Forms (contact.html)
1. Create a Google Form for membership sign-ups
2. Click "Send" → Choose embed option (<>)
3. Copy the iframe code
4. Replace the placeholder form in contact.html with your iframe


### Your Website on Google

#### Add to Google Search Console
1. Go to [search.google.com/search-console](https://search.google.com/search-console)
2. Add your GitHub Pages URL
3. Verify ownership
4. Submit your sitemap (optional but recommended)

#### SEO Tips
- Share your website URL on social media
- Link it from your Facebook, Instagram, LinkedIn pages
- Add it to UNSW student organization directories
- Post it on Discord

## 🎨 Customization Guide

### Change Colors
Edit `css/style.css` and update these variables:
```css
:root {
    --primary-blue: #5B9DBD;     /* Main blue color */
    --secondary-green: #7FB69E;  /* Accent green */
    --gold-accent: #F4C430;      /* Gold accent */
}
```

### Update Content
- All text content is directly in the HTML files
- No database or backend required
- Simply edit the HTML files and save

### Add Blog Posts
Edit `blog.html` and duplicate the blog card structure:
```html
<div class="col-md-6 col-lg-4">
    <div class="card blog-card h-100">
        <!-- Your blog post content -->
    </div>
</div>
```

## 👥 For Multiple Editors



### Option 1: GitHub (Recommended)
- All team members create GitHub accounts
- You add them as collaborators to the repository
- They can edit files directly on GitHub.com (no coding knowledge needed!)
- Changes automatically deploy to the live site

### Option 2: Google Sites/WordPress
- If HTML editing is too technical, consider:
  - Google Sites (easiest for beginners)
  - WordPress.com (more features, still free)
  - Wix/Weebly (drag-and-drop)

## 📱 Social Media Integration

All your social media links are already integrated:
- Facebook: https://www.facebook.com/UNSWPPESoc
- Instagram: https://www.instagram.com/unswppesoc/
- LinkedIn: https://www.linkedin.com/company/unsw-politics-philosophy-and-economics-society
- Discord: https://discord.com/invite/vVJ84bCXz6

## 🔧 Troubleshooting

### Logo Not Showing
- Make sure `logo.png` is in the `images/` folder
- Check that the file name matches exactly (case-sensitive)

### Website Not Loading on GitHub Pages
- Wait 5-10 minutes after first deployment
- Check that your repository is public
- Ensure the main branch is selected in Pages settings

### Google Form Not Working
- Make sure you're using the embed code (iframe), not the link
- The form must be set to "Anyone with the link can respond"

## 📞 Need Help?

If you need technical assistance:
1. Check GitHub Pages documentation
2. Ask in your Discord server
3. Reach out to UNSW CSE Society for technical mentorship

## 📄 License

This website is for UNSW PPE Society. Feel free to customize and use it!
