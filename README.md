# English Bus - Professional English Learning Website

A modern, responsive website for English Bus (English Mithra), Kerala's best online English learning platform.

## 🚀 Deployment to Vercel

This website is configured for easy deployment to Vercel with PHP support.

### Prerequisites

1. **Vercel Account**: Sign up at [vercel.com](https://vercel.com)
2. **Git Repository**: Your code should be in a Git repository (GitHub, GitLab, or Bitbucket)

### Deployment Steps

#### Option 1: Deploy via Vercel CLI

1. **Install Vercel CLI**:
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy from your project directory**:
   ```bash
   cd /Users/mirsalsaidu/Webberbuff/english-bus
   vercel
   ```

4. **Follow the prompts**:
   - Link to existing project or create new
   - Confirm project settings
   - Deploy!

#### Option 2: Deploy via Vercel Dashboard

1. **Go to [vercel.com/dashboard](https://vercel.com/dashboard)**
2. **Click "New Project"**
3. **Import your Git repository**
4. **Configure project settings**:
   - Framework Preset: Other
   - Root Directory: `./`
   - Build Command: (leave empty)
   - Output Directory: (leave empty)
5. **Click "Deploy"**

### Configuration Files

The project includes these Vercel configuration files:

- **`vercel.json`**: Configures PHP runtime and routing
- **`package.json`**: Project metadata and scripts
- **`.gitignore`**: Excludes unnecessary files from deployment

### Features

- ✅ **PHP Support**: Configured for Vercel's PHP runtime
- ✅ **Responsive Design**: Works on all devices
- ✅ **Modern UI**: Clean, professional design
- ✅ **Fast Loading**: Optimized assets and code
- ✅ **SEO Ready**: Proper meta tags and structure

### Custom Domain (Optional)

After deployment, you can add a custom domain:

1. Go to your project dashboard on Vercel
2. Click "Domains" tab
3. Add your custom domain
4. Update DNS settings as instructed

### Environment Variables (If Needed)

If you need environment variables:

1. Go to project settings on Vercel
2. Add variables in "Environment Variables" section
3. Redeploy your project

### Support

For deployment issues:
- Check [Vercel Documentation](https://vercel.com/docs)
- Review [PHP Runtime Documentation](https://vercel.com/docs/runtimes#official-runtimes/php)

## 🎨 Website Features

### Design
- Modern, clean layout
- Logo-based color scheme
- Professional typography
- Smooth animations

### Sections
- Hero with call-to-action
- Courses showcase
- Features highlights
- Student testimonials
- Video gallery
- Contact information

### Technical
- PHP backend ready
- Responsive CSS
- Interactive JavaScript
- Optimized images
- Fast loading

## 📱 Mobile Responsive

The website is fully responsive and works perfectly on:
- Desktop computers
- Tablets
- Mobile phones
- All screen sizes

## 🔧 Local Development

To run locally:

```bash
# Using PHP built-in server
php -S localhost:3000

# Or using Node.js (if you have it installed)
npm run dev
```

Visit `http://localhost:3000` to view the website.

## 📄 License

This project is licensed under the MIT License.