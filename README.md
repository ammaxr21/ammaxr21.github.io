# Portfolio Website

A minimalistic portfolio website with a warm color theme, built with pure HTML, CSS, and JavaScript.

## Features

- **Landing Page**: Circular profile image with introduction
- **Projects Page**: 2-column grid showcasing projects
- **Research Page**: Grid layout for research work and findings
- **CV Page**: Professional CV with company/institution logos
- **Blog**: Blog listing page with individual blog post pages
- **Responsive Design**: Works on mobile, tablet, and desktop
- **Smooth Navigation**: Clean transitions between pages

## Color Palette

The website uses a warm, minimalistic color scheme:
- `#edede9` - Lightest cream (backgrounds)
- `#d6ccc2` - Light taupe (secondary backgrounds)
- `#f5ebe0` - Soft beige (cards, tiles)
- `#e3d5ca` - Medium beige (borders, accents)
- `#d5bdaf` - Warm tan (text, headings, hover states)

## Project Structure

```
portfolio2/
├── index.html              # Landing page
├── projects.html           # Projects grid
├── research.html           # Research grid
├── cv.html                 # CV with logos
├── blog.html               # Blog listing
├── blog/
│   ├── post1.html         # Sample blog post 1
│   ├── post2.html         # Sample blog post 2
│   └── post3.html         # Sample blog post 3
├── css/
│   └── style.css          # All styles
├── js/
│   └── main.js            # Smooth transitions
└── assets/
    └── images/            # Your images go here
```

## Setup Instructions

1. **Add Your Images**: Place your images in the `assets/images/` folder:
   - `profile.jpg` - Your profile photo for the landing page
   - `project1.jpg`, `project2.jpg`, etc. - Project images
   - `research1.jpg`, `research2.jpg`, etc. - Research images
   - `company1.png`, `company2.png`, etc. - Company/institution logos
   - `university1.png`, `university2.png`, etc. - University logos

2. **Customize Content**: Edit the HTML files to add your personal information:
   - Update your name, tagline, and introduction in `index.html`
   - Add your projects in `projects.html`
   - Add your research work in `research.html`
   - Update your education and experience in `cv.html`
   - Write your blog posts or remove the sample ones

3. **Update Social Links**: In each HTML file's footer, replace the placeholder links with your actual social media profiles:
   - GitHub: `https://github.com/yourusername`
   - LinkedIn: `https://linkedin.com/in/yourusername`
   - Twitter: `https://twitter.com/yourusername`
   - Email: `your.email@example.com`

## Local Testing

To view the website locally:

1. Open `index.html` in your web browser
2. Or use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000
   ```

## GitHub Pages Deployment

1. **Create a GitHub repository** (e.g., `yourusername.github.io`)

2. **Initialize git and push your code**:
   ```bash
   cd portfolio2
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "main" branch as source
   - Click "Save"

4. Your site will be live at `https://yourusername.github.io`

## Customization Tips

- **Colors**: All colors are defined as CSS variables in `style.css` (lines 16-23). Change them to customize the theme.
- **Fonts**: The site uses Inter from Google Fonts. You can change this in the `<head>` section of each HTML file.
- **Layout**: Adjust spacing by modifying the CSS variables for spacing (lines 25-30 in `style.css`).
- **Add More Pages**: Create new HTML files following the same structure as existing pages.

## Browser Compatibility

The website works on all modern browsers:
- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

Feel free to use this template for your own portfolio!
