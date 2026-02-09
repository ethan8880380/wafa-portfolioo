# wafa-portfolio

Portfolio site built with Figma Make, hosted on Vercel.

## 🚀 Deploy to Vercel

### Option 1: Using Vercel CLI (Recommended)

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy:**
   ```bash
   vercel
   ```

4. **For production:**
   ```bash
   vercel --prod
   ```

### Option 2: Using GitHub Integration

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin main
   ```

2. **Import to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Vercel will auto-detect it's a static site
   - Click "Deploy"

### Option 3: Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Drag and drop your project folder
3. Vercel will deploy it automatically

## 📁 Project Structure

This is a static site exported from Figma Make:
- `index.html` - Main HTML file
- `_components/` - Component files
- `_runtimes/` - Runtime JavaScript
- `_json/` - Site data
- `_assets/` - Images and assets
- `_woff/` - Font files

## ⚙️ Configuration

- `vercel.json` - Vercel deployment configuration
- All routes redirect to `index.html` for client-side routing

## 🌐 Custom Domain

After deployment:
1. Go to your project settings on Vercel
2. Navigate to "Domains"
3. Add your custom domain
4. Update DNS records as instructed

## 📝 Notes

- This is a static site, no build process needed
- All assets are served from the root directory
- The site uses client-side JavaScript for rendering
