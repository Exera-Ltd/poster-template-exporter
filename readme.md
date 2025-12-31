# 🎨 Poster Template Creator

A powerful, browser-based tool for creating poster templates and bulk exporting multiple variations. Design once, export hundreds!

## ✨ Features

- **Background Management**: Upload any image as your poster background
- **Unlimited Text**: Add text with full formatting (font, size, color, positioning)
- **Unlimited Images**: Add images with drag-and-drop positioning
- **AI Background Removal**: Automatically remove image backgrounds using AI (no API needed!)
- **Template System**: Mark any text/image as a template field
- **Bulk Export**: Fill in multiple data rows and export all posters as a ZIP file
- **Mobile Responsive**: Works perfectly on phones and tablets
- **100% Frontend**: No server, no installation, no API keys required

## 🚀 GitHub Pages Setup (Free Hosting)

Follow these steps to host your app on GitHub with automatic updates:

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon (top right) → **New repository**
3. Name it anything (e.g., `poster-creator`)
4. Make it **Public**
5. Click **Create repository**

### 2. Upload the File

1. On your repository page, click **Add file** → **Upload files**
2. Drag and drop the `index.html` file
3. Click **Commit changes**

### 3. Enable GitHub Pages

1. Go to your repository **Settings** (tab at top)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
4. Click **Save**

### 4. Access Your App

After 1-2 minutes, your app will be live at:
```
https://YOUR-USERNAME.github.io/poster-creator/
```

Replace `YOUR-USERNAME` with your GitHub username and `poster-creator` with your repo name.

## 📱 Usage Guide

### Creating Your First Template

1. **Upload Background**: Click "Upload Background Image"
2. **Add Text**: 
   - Enter text content
   - Choose font, size, color
   - Check "Make this a template field" if you want to replace it later
   - Click "Add Text"
3. **Add Images**:
   - Upload an image
   - Check "Remove background" for transparent PNGs
   - Check "Make this a template field" for bulk replacement
4. **Position Elements**: Click and drag text/images to position them

### Bulk Export (The Magic!)

1. Click **"Bulk Export Templates"**
2. You'll see all your template fields
3. Fill in data for each row (each row = one poster)
4. Click **"Add Row"** for more variations
5. Click **"Generate & Download All"**
6. Get a ZIP with all your posters!

### Example Use Cases

- **Event Posters**: Create template with event name/date, bulk generate for 50 events
- **Product Catalogs**: Template with product image/name/price, generate for all products
- **Social Media Posts**: Template with quote/author, generate 100 quote graphics
- **Certificates**: Template with name/achievement, generate for all recipients

## 🔧 Technical Details

**Libraries Used:**
- Fabric.js - Canvas manipulation
- @imgly/background-removal - AI background removal
- JSZip - Bulk export to ZIP
- FileSaver.js - Download functionality

**No Installation Required:**
- All libraries loaded from CDN
- Pure HTML/JavaScript
- Runs entirely in browser
- No backend needed

## 📝 Updates

To update your app:
1. Edit `index.html` locally
2. Go to your GitHub repository
3. Click on `index.html`
4. Click the pencil icon (Edit)
5. Paste your updated code
6. Click **Commit changes**
7. Your site updates automatically in 1-2 minutes!

## 🎯 Tips

- **Template Fields**: The blue outline indicates a template field
- **High Quality**: Exports are full resolution PNGs
- **Mobile**: Pinch to zoom, drag to position on mobile
- **Keyboard**: Press Delete/Backspace to remove selected element
- **AI Background Removal**: Works best with clear subject photos

## 🐛 Troubleshooting

**Background removal not working?**
- Make sure you have a good internet connection (AI model downloads on first use)
- Try with a smaller image first
- Clear your browser cache

**Can't see the app?**
- Wait 2-3 minutes after enabling GitHub Pages
- Clear browser cache
- Check the URL matches your GitHub username

**Bulk export fails?**
- Make sure all required fields are filled
- Try with fewer rows first
- Check browser console for errors

## 📄 License

Free to use and modify!

---

Made with ❤️ using only browser technologies
