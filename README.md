# Sheperd Thobejane - Developer Portfolio

A modern, responsive portfolio website showcasing skills, experience, and achievements.

## 🚀 Live Demo

Once deployed, your portfolio will be live at: `https://[your-username].github.io/[repository-name]`

## 🎨 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Elegant fade-in effects and scroll animations
- **Modern Aesthetics**: Clean, professional design with a tech-focused theme
- **Award Spotlight**: Prominent display of your R1 Million award-winning project
- **Easy Navigation**: Smooth scrolling to different sections
- **Contact Integration**: Direct links to email, phone, GitHub, and LinkedIn

## 📦 What's Included

- `index.html` - Single-page portfolio website (fully self-contained)
- `README.md` - This file with setup instructions

## 🌐 Hosting on GitHub Pages

### Option 1: Create a New Repository

1. **Create a new repository on GitHub**
   - Go to https://github.com/new
   - Name it something like `portfolio` or `my-portfolio`
   - Make it public
   - Don't initialize with README (we already have one)

2. **Upload your files**
   - Click "uploading an existing file"
   - Drag and drop both `index.html` and `README.md`
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click Save
   - Your site will be live at `https://[your-username].github.io/[repository-name]`

### Option 2: Use Command Line (if you have Git installed)

```bash
# Navigate to the folder with your files
cd path/to/your/portfolio/folder

# Initialize a git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Initial portfolio commit"

# Create a new repository on GitHub first, then:
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git branch -M main
git push -u origin main

# Then enable GitHub Pages in Settings → Pages
```

### Option 3: Use Your Username Repository

For a cleaner URL (`https://[your-username].github.io`):

1. Create a repository named exactly `[your-username].github.io`
   - For example: `Thobs-Tricks.github.io`
2. Upload the files
3. GitHub Pages will automatically activate
4. Your site will be at `https://[your-username].github.io`

## ✏️ Customization

### Update Your Information

The portfolio is already populated with your CV information, but you can easily update:

1. **Personal Details**: Open `index.html` and search for your name, email, phone number, etc.
2. **Colors**: Modify CSS variables in the `:root` section (lines 11-19)
3. **Fonts**: Change Google Fonts in the `<link>` tag (line 8)
4. **Content**: Update any section by finding the relevant HTML and modifying text

### Color Scheme

Current colors:
- Primary Accent: `#00d4aa` (Teal/Cyan)
- Secondary Accent: `#7c3aed` (Purple)
- Award Accent: `#f59e0b` (Amber/Gold)
- Background: Dark theme with `#0a0e14`

To change colors, modify these CSS variables:
```css
:root {
    --accent-primary: #00d4aa;    /* Change to your preferred color */
    --accent-secondary: #7c3aed;
    --accent-warm: #f59e0b;
}
```

## 🔧 Technical Details

- **Framework**: Pure HTML, CSS, and vanilla JavaScript
- **Fonts**: Crimson Pro (serif) and JetBrains Mono (monospace) from Google Fonts
- **Animations**: CSS animations with Intersection Observer API
- **Responsive**: Mobile-first approach with CSS Grid and Flexbox

## 📱 Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## 🎯 Sections Included

1. **Hero** - Introduction with call-to-action
2. **Award Spotlight** - Your R1M winning project
3. **About** - Professional profile
4. **Experience** - Work history timeline
5. **Skills** - Technical and soft skills
6. **Education** - Degrees and certifications
7. **Contact** - Get in touch section

## 📄 License

Feel free to use this template for your personal portfolio!

## 🤝 Need Help?

If you encounter issues:
1. Check GitHub Pages documentation: https://docs.github.com/en/pages
2. Ensure your repository is public
3. Wait a few minutes after enabling Pages for the site to build
4. Clear your browser cache if changes don't appear

---

**Built with passion by Sheperd Kgaume Thobejane** 🚀
