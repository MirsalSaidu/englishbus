# 🚀 Vercel Deployment Guide for English Bus Website

## Quick Start

### Method 1: Vercel CLI (Recommended)

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Navigate to your project**:
   ```bash
   cd /Users/mirsalsaidu/Webberbuff/english-bus
   ```

3. **Login to Vercel**:
   ```bash
   vercel login
   ```

4. **Deploy**:
   ```bash
   vercel
   ```

5. **Follow the prompts**:
   - Set up and deploy? **Yes**
   - Which scope? **Your account**
   - Link to existing project? **No** (for first deployment)
   - What's your project's name? **english-bus-website**
   - In which directory is your code located? **./**

### Method 2: GitHub Integration

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - English Bus website"
   git branch -M main
   git remote add origin https://github.com/yourusername/english-bus-website.git
   git push -u origin main
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import from GitHub
   - Select your repository
   - Deploy!

## Configuration Files Created

### `vercel.json`
- Configures PHP runtime
- Sets up routing for single-page application
- Optimizes for Vercel's platform

### `package.json`
- Project metadata
- Scripts for development
- Dependencies (if needed later)

### `.gitignore`
- Excludes unnecessary files
- Optimizes deployment size

## Post-Deployment

### 1. Custom Domain (Optional)
- Go to your Vercel dashboard
- Click on your project
- Go to "Domains" tab
- Add your custom domain
- Update DNS settings

### 2. Environment Variables (If Needed)
- Project Settings → Environment Variables
- Add any required variables
- Redeploy

### 3. Performance Optimization
- Vercel automatically optimizes images
- Enables compression
- Provides CDN distribution

## Troubleshooting

### Common Issues

1. **Build Fails**:
   - Check `vercel.json` syntax
   - Ensure all files are committed
   - Review Vercel logs

2. **PHP Not Working**:
   - Verify `vercel.json` has PHP runtime
   - Check file extensions (.php)
   - Review function configuration

3. **Assets Not Loading**:
   - Check file paths (use relative paths)
   - Verify asset files are committed
   - Check browser console for errors

### Support Resources

- [Vercel Documentation](https://vercel.com/docs)
- [PHP Runtime Guide](https://vercel.com/docs/runtimes#official-runtimes/php)
- [Vercel Community](https://github.com/vercel/vercel/discussions)

## Website Features

✅ **Responsive Design** - Works on all devices  
✅ **Modern UI** - Clean, professional layout  
✅ **Fast Loading** - Optimized for performance  
✅ **SEO Ready** - Proper meta tags and structure  
✅ **Interactive Elements** - Smooth animations and effects  
✅ **Contact Integration** - WhatsApp and contact forms  
✅ **Professional Branding** - Logo-based color scheme  

## Next Steps

1. **Deploy to Vercel** using one of the methods above
2. **Test the live website** thoroughly
3. **Add custom domain** if desired
4. **Monitor performance** using Vercel analytics
5. **Update content** as needed

Your English Bus website is now ready for deployment! 🎉
