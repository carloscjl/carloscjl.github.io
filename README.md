# Jiale Cai's Personal Academic Website

This is the source code for my personal academic website hosted on GitHub Pages.

## 🌐 Live Website

Visit: [https://jialecai.github.io](https://jialecai.github.io)

## 📁 Project Structure

```
jialecai.github.io/
├── index.html          # Main webpage
├── assets/
│   ├── photo.jpg       # Profile photo (add your own)
│   └── cv.pdf          # Your CV (add your own)
└── README.md           # This file
```

## 🚀 Deployment Guide

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the **"+"** icon in the top-right corner → **"New repository"**
3. **Important**: Name your repository exactly `jialecai.github.io` (replace `jialecai` with your GitHub username)
4. Set the repository to **Public**
5. Do NOT initialize with README (we'll push our own files)
6. Click **"Create repository"**

### Step 2: Upload Files

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click **"uploading an existing file"**
2. Drag and drop:
   - `index.html`
   - Create an `assets` folder and add your `photo.jpg` and `cv.pdf`
3. Click **"Commit changes"**

#### Option B: Using Git Command Line

```bash
# Clone the repository
git clone https://github.com/jialecai/jialecai.github.io.git
cd jialecai.github.io

# Copy your files here (index.html, assets folder, etc.)

# Add, commit, and push
git add .
git commit -m "Initial website deployment"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (gear icon)
3. In the left sidebar, click **"Pages"**
4. Under **"Source"**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **"Save"**
6. Wait 1-2 minutes for deployment
7. Your site will be live at `https://jialecai.github.io`

## ✏️ Customization

### Add Your Photo

1. Prepare a professional photo (recommended: 400x400px, square)
2. Name it `photo.jpg`
3. Place it in the `assets/` folder

### Add Your CV

1. Export your CV as PDF
2. Name it `cv.pdf`
3. Place it in the `assets/` folder

### Update Links

In `index.html`, update these placeholders:

1. **Google Scholar**: Replace `YOUR_ID` in the Scholar link with your actual Google Scholar ID
   ```html
   <a href="https://scholar.google.com/citations?user=YOUR_ID">
   ```

2. **GitHub Username**: Replace `jialecai` with your actual GitHub username
   ```html
   <a href="https://github.com/YOUR_USERNAME">
   ```

3. **Paper Links**: Replace `#` with actual paper URLs (arXiv, conference pages, etc.)

### Update Content

- Edit publication information when new papers are accepted
- Add/remove news items in the News section
- Update academic service as you review more papers

## 🎨 Design Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Clean Typography**: Uses Source Serif 4 and Source Sans 3 fonts
- **Smooth Animations**: Subtle fade-in effects on page load
- **Sticky Navigation**: Navigation bar stays visible while scrolling
- **Academic Icons**: Includes Google Scholar and other academic platform icons

## 📝 Updating Your Website

After making changes to your files:

```bash
git add .
git commit -m "Update website"
git push origin main
```

Changes will be live within 1-2 minutes.

## 📧 Contact

- Email: jcai336@uwo.ca / jialecai6@gmail.com
- Website: https://jialecai.github.io

---

© 2025 Jiale Cai. Built with ❤️ for academia.
