# Hanut Singh - Personal Blog & Portfolio

A modern, responsive personal blog and portfolio website built entirely with GitHub Copilot and hosted on GitHub Pages.

## 🚀 Built with GitHub Copilot

This entire website showcases the power of AI-assisted development. Every component, from the HTML structure to the responsive CSS and interactive JavaScript, was created with the assistance of GitHub Copilot.

## ✨ Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Multiple Sections**:
  - Home/Hero section with call-to-action
  - About Me section
  - Skills & Technologies showcase
  - Experience timeline
  - Featured Projects
  - Blog with multiple posts
  - Contact section with social links
- **Blog System**: Individual blog post pages with navigation
- **Smooth Navigation**: Animated scroll behavior and active section highlighting
- **GitHub Pages Ready**: Configured for easy deployment

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- Vanilla JavaScript
- GitHub Pages

## 📦 Structure

```
.
├── index.html              # Main homepage
├── styles.css             # Global styles
├── script.js              # Interactive features
├── blog/                  # Blog posts directory
│   ├── welcome.html
│   └── copilot-experience.html
├── _config.yml           # GitHub Pages configuration
└── README.md             # This file
```

## 🚀 Deployment to GitHub Pages

### Enabling GitHub Pages

1. Go to your repository settings
2. Navigate to the "Pages" section in the left sidebar
3. Under "Source", select the branch you want to deploy (e.g., `main` or `copilot/build-personal-blog`)
4. Select the root folder `/` as the source
5. Click "Save"
6. Your site will be published at `https://hanut.github.io/hanut/`

### Custom Domain (Optional)

If you want to use a custom domain like `hanutsingh.in`:

1. Add a `CNAME` file in the root directory with your domain name
2. Configure your DNS settings to point to GitHub Pages
3. Enable "Enforce HTTPS" in the repository settings

## 🎨 Customization

### Updating Content

- **Personal Information**: Edit the text in `index.html`
- **Styling**: Modify colors and design in `styles.css` (CSS variables are defined at the top)
- **Blog Posts**: Add new HTML files in the `blog/` directory and link them from `index.html`

### Color Scheme

The color scheme can be easily customized by modifying the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    /* ... */
}
```

## 📝 Adding New Blog Posts

1. Create a new HTML file in the `blog/` directory
2. Copy the structure from existing blog posts (`welcome.html` or `copilot-experience.html`)
3. Update the content
4. Add a link to the new post in the blog section of `index.html`

## 🌟 Local Development

To test the site locally:

```bash
# Using Python 3
python3 -m http.server 8080

# Using Python 2
python -m SimpleHTTPServer 8080

# Using Node.js (if you have http-server installed)
npx http-server -p 8080
```

Then visit `http://localhost:8080` in your browser.

## 📧 Contact

- GitHub: [@hanut](https://github.com/hanut)
- LinkedIn: [linkedin.com/in/hanut](https://linkedin.com/in/hanut)

## 📄 License

This project is open source and available for personal use.

---

**Built with ❤️ and GitHub Copilot**
