# Portfolio Website - GitHub Pages Setup

This is your professional portfolio website built with HTML, CSS, and JavaScript. It showcases your Web3 and blockchain development projects.

## 📁 Files

- `index.html` - Main portfolio website
- `style.css` - Styling and responsive design
- `script.js` - Interactive features and animations

## 🚀 Deployment to GitHub Pages

### Step 1: Create a new GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **+** icon in the top right → **New repository**
3. Name the repository: **`shivamsharma218.github.io`** (replace with your GitHub username)
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Push Your Portfolio to GitHub

```bash
# Navigate to your portfolio folder
cd portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit your changes
git commit -m "Initial portfolio commit"

# Add the remote repository
git remote add origin https://github.com/shivamsharma218/shivamsharma218.github.io.git

# Push to GitHub (main or master branch)
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository settings on GitHub
2. Scroll down to **Pages** section
3. Under "Build and deployment", select:
   - **Source**: Deploy from a branch
   - **Branch**: main (or master)
   - **Folder**: / (root)
4. Click **Save**

### Step 4: Access Your Portfolio

Your portfolio will be live at:
```
https://shivamsharma218.github.io
```

*It may take a few minutes to deploy. Refresh the page after a couple of minutes.*

## 📝 Customization

### Update Your Information

Edit `index.html` to customize:

1. **Name & Title**: Change "Shivam Sharma" and "Web3 Developer" in the hero section
2. **About Section**: Update your bio in the About Me section
3. **Skills**: Add or remove skills in the Skills section
4. **Projects**: Add more projects or update project details
5. **Contact Links**: Update your GitHub, LinkedIn, Twitter, and email links

### Colors & Styling

The color scheme is defined in `style.css` under `:root`:

```css
--primary-color: #0066ff;
--secondary-color: #6366f1;
--dark-bg: #0f172a;
--accent-color: #00d9ff;
```

Feel free to modify these hex codes to match your preferred color scheme.

## 🎨 Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Dark theme optimized for readability
- ✅ Smooth scrolling navigation
- ✅ Project showcase with links
- ✅ Skills organized by category
- ✅ Contact section with social links
- ✅ Animated elements on scroll
- ✅ Fast loading and SEO-friendly

## 🔧 Adding More Projects

To add more projects to your portfolio:

1. Open `index.html`
2. Find the "Projects" section
3. Duplicate the project card and update:
   - Project title
   - Description
   - GitHub link
   - Technologies used (feature tags)
   - Project details

## 📱 Mobile Optimization

The portfolio is fully responsive and optimized for:
- Desktops (1200px+)
- Tablets (768px - 1199px)
- Mobile phones (320px - 767px)

## 🐛 Troubleshooting

### Portfolio not showing?
- Wait 2-3 minutes for GitHub Pages to deploy
- Check repository settings → Pages to confirm it's enabled
- Verify repository name is `username.github.io`

### Changes not reflecting?
- Clear browser cache (Ctrl+Shift+Del)
- Wait a few minutes for changes to propagate
- Check that you pushed to the correct branch

### Custom domain?
If you own a domain and want to use it:
1. Go to repository Settings → Pages
2. Under "Custom domain", enter your domain
3. Update DNS records as instructed by GitHub

## 📚 Future Enhancements

Consider adding:
- Blog/Articles section
- Resume/CV download
- Projects filter by technology
- Dark/Light mode toggle
- Comments or feedback form

## 📄 License

This portfolio is open source and available under the MIT License.

---

**Happy coding! 🚀 Keep building amazing projects and growing your portfolio!**
