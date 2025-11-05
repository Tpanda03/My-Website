# 🌐 90s Cyber Research Zone - GitHub Pages Setup Guide

## 🚀 Quick Start Guide

Welcome to your totally rad 90s-style website template! This guide will help you get your site live on GitHub Pages in just a few steps.

## 📁 What You've Got

Your website includes these tubular pages:
- `index.html` - Homepage with classic 90s design
- `research.html` - Store your research about 90s internet culture
- `timeline.html` - Document important events from the 90s internet
- `gallery.html` - Display vintage graphics and screenshots
- `links.html` - Collection of cool links and resources
- `guestbook.html` - Classic 90s guestbook (display only)

## 🛠️ How to Deploy to GitHub Pages

### Step 1: Create a GitHub Account
If you don't have one already, sign up at [github.com](https://github.com)

### Step 2: Create a New Repository
1. Click the **"+"** button in the top right corner
2. Select **"New repository"**
3. Name it: `your-username.github.io` (for a main site) OR any name you want (for a project site)
4. Make sure it's **Public**
5. Don't initialize with README (you already have this one!)
6. Click **"Create repository"**

### Step 3: Upload Your Files
#### Option A: Using GitHub Web Interface (Easiest)
1. Click **"uploading an existing file"** on your new repo page
2. Drag and drop ALL the HTML files (index.html, research.html, etc.)
3. Write a commit message like "Initial 90s website upload"
4. Click **"Commit changes"**

#### Option B: Using Git Command Line
```bash
git init
git add .
git commit -m "Initial 90s website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **"Settings"** (in the repo navigation)
3. Scroll down to **"Pages"** section
4. Under "Source", select **"Deploy from a branch"**
5. Choose **"main"** branch
6. Select **"/ (root)"** folder
7. Click **"Save"**

### Step 5: Access Your Live Site!
- If you named your repo `your-username.github.io`:
  - Your site will be at: `https://your-username.github.io`
- If you used a different name:
  - Your site will be at: `https://your-username.github.io/repo-name`

*Note: It may take 5-10 minutes for your site to go live the first time!*

## ✏️ How to Customize Your Site

### Adding Your Research Content
1. Open `research.html` in any text editor
2. Find the placeholder sections marked with `[...]`
3. Replace with your actual research content
4. Save and push changes to GitHub

### Adding to the Timeline
1. Open `timeline.html`
2. Look for the placeholder events
3. Add your events with dates and descriptions
4. Follow the existing format for consistency

### Adding Images to Gallery
1. Upload images to your repository
2. In `gallery.html`, replace `[Add Image]` placeholders with:
   ```html
   <img src="your-image.gif" alt="Description">
   ```

### Updating Links
1. Open `links.html`
2. Replace `#` in href attributes with actual URLs
3. Update descriptions and add your favorite sites

### Customizing Colors
Look for the `<style>` sections in each HTML file to change:
- Background colors (look for `background-color`)
- Text colors (look for `color`)
- Border colors (look for `border`)

## 🎨 Pro Tips for Maximum 90s Authenticity

1. **Use Web Archive for Graphics**: The images currently use archived GeoCities graphics. You can find more at [archive.org](https://archive.org)

2. **Keep the Cheese**: Comic Sans, bright colors, and animated GIFs are essential!

3. **Add a MIDI File** (optional):
   ```html
   <embed src="your-song.mid" autostart="true" loop="true" hidden="true">
   ```

4. **More Marquees**: Can't have too many scrolling texts!

5. **Under Construction**: Always have at least one "Under Construction" GIF

## 🔧 Troubleshooting

**Site not showing up?**
- Make sure GitHub Pages is enabled in Settings
- Wait 10 minutes after first deployment
- Check you're using the correct URL format

**Images not loading?**
- Use relative paths (e.g., `images/pic.gif` not `/images/pic.gif`)
- Make sure image files are uploaded to your repo
- Check file names are case-sensitive

**Changes not appearing?**
- Hard refresh your browser (Ctrl+Shift+R or Cmd+Shift+R)
- Changes can take 5-10 minutes to propagate

## 🌟 Making It Even More Awesome

Consider adding:
- A visitor counter (using a service like [hits.seeyoufarm.com](https://hits.seeyoufarm.com/))
- Background MIDI music
- More animated GIFs
- ASCII art
- Frames (for ultimate 90s vibes)
- A "Best Viewed in Netscape" banner

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Internet Archive](https://archive.org) - Find vintage graphics
- [GifCities](https://gifcities.org/) - GeoCities GIF search engine
- [90s Web Design Inspiration](https://www.cameronsworld.net/)

## 🎉 You're Ready!

Your site is now ready to transport visitors back to the golden age of the World Wide Web! 
Don't forget to share your site and keep it "Under Construction" forever!

---

*Remember: Optimized for Netscape Navigator 4.0, 800x600 resolution, 256 colors!* 😄