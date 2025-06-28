# Crave & Cook - Recipe Website

A beautiful and responsive recipe website built with HTML, CSS, and JavaScript.

## Features

- 🍳 Interactive recipe collection
- 📱 Responsive design
- 🔍 Recipe search and filtering
- 📖 Blog section
- 📞 Contact form
- 🎨 Modern UI with smooth animations

## Deployment to Vercel

### Prerequisites

1. **GitHub Account**: Make sure your project is on GitHub
2. **Vercel Account**: Sign up at [vercel.com](https://vercel.com)

### Step-by-Step Deployment

#### Method 1: Deploy via Vercel Dashboard (Recommended)

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

2. **Deploy on Vercel**:
   - Go to [vercel.com](https://vercel.com) and sign in
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect it's a static site
   - Click "Deploy"

#### Method 2: Deploy via Vercel CLI

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Deploy**:
   ```bash
   cd "food recipe"
   vercel
   ```

3. **Follow the prompts**:
   - Login to your Vercel account
   - Choose to link to existing project or create new
   - Confirm deployment settings

### Project Structure

```
food recipe/
├── index.html          # Main homepage
├── recipe.html         # Recipe page
├── blog.html           # Blog page
├── contact.html        # Contact page
├── style.css           # Main stylesheet
├── recipes.json        # Recipe data
├── images/             # Image assets
├── blog-posts/         # Blog post HTML files
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

### Custom Domain (Optional)

1. Go to your Vercel project dashboard
2. Navigate to "Settings" → "Domains"
3. Add your custom domain
4. Follow the DNS configuration instructions

### Environment Variables

This project doesn't require any environment variables as it's a static website.

### Build Settings

- **Framework Preset**: Other
- **Build Command**: Not required (static site)
- **Output Directory**: Not required (static site)
- **Install Command**: Not required (static site)

## Local Development

To run the project locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   ```

## Support

If you encounter any issues during deployment, check:
- [Vercel Documentation](https://vercel.com/docs)
- [Vercel Community](https://github.com/vercel/vercel/discussions)

## License

This project is open source and available under the [MIT License](LICENSE). 