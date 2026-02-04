# Valentine's Day Website 💕

A beautiful, interactive Valentine's Day website with the viral "can't click No" button trend!

## Features 🌟

- **Interactive Question Page**: The trending "No" button that runs away and shrinks when you try to click it
- **Multiple Pages**: 
  - Main question page with floating hearts animation
  - Celebration page with heart rain effect
  - Romantic love letter
  - Timeline of memories
  - Custom playlist page
- **Beautiful Animations**: Smooth transitions, floating hearts, and interactive elements
- **Fully Responsive**: Works perfectly on mobile and desktop
- **Modern Design**: Trendy gradients, custom fonts, and polished UI

## How to Host on GitHub Pages 🚀

### Method 1: Using GitHub Web Interface (Easiest)

1. **Create a New Repository**
   - Go to [GitHub](https://github.com) and log in
   - Click the "+" icon in the top right, then "New repository"
   - Name it: `valentine` (or any name you like)
   - Make it **Public**
   - Click "Create repository"

2. **Upload Files**
   - Click "uploading an existing file"
   - Drag and drop all the HTML files:
     - `index.html`
     - `yes.html`
     - `letter.html`
     - `memories.html`
     - `playlist.html`
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll down to "Pages" section (left sidebar)
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait 1-2 minutes for deployment

4. **Access Your Site**
   - Your site will be live at: `https://YOUR-USERNAME.github.io/valentine/`
   - Share this link with your girlfriend! 💕

### Method 2: Using Git (For developers)

```bash
# Clone your repository
git clone https://github.com/YOUR-USERNAME/valentine.git
cd valentine

# Add the HTML files to the folder
# Copy all 5 HTML files to this directory

# Commit and push
git add .
git commit -m "Add Valentine's Day website"
git push origin main

# Enable GitHub Pages in repository settings (as described above)
```

## Customization Tips ✨

### Personalize the Content:

1. **Love Letter** (`letter.html`):
   - Edit the letter content to make it more personal
   - Change the signature at the bottom

2. **Memories** (`memories.html`):
   - Update the memory titles and descriptions
   - Replace placeholder emoji with actual photos by adding:
     ```html
     <img src="your-photo.jpg" style="width: 100%; height: 100%; object-fit: cover;">
     ```

3. **Playlist** (`playlist.html`):
   - Add your actual favorite songs
   - Include songs that are meaningful to your relationship

4. **Colors**: 
   - Change the color scheme by editing CSS variables in each file
   - Look for `:root` section at the top of `<style>` tags

## File Structure 📁

```
valentine/
│
├── index.html      # Main page with the "Will you be my valentine?" question
├── yes.html        # Celebration page after clicking "Yes"
├── letter.html     # Romantic love letter page
├── memories.html   # Timeline of your memories together
├── playlist.html   # Your special songs playlist
└── README.md       # This file
```

## Browser Support 🌐

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge
- Mobile browsers

## Tips for Best Results 💡

1. **Test Locally First**: Open `index.html` in your browser to see how it looks
2. **Mobile Check**: Test on your phone to ensure everything works smoothly
3. **Timing**: Set this up before Valentine's Day to have it ready!
4. **Sharing**: You can create a short link using bit.ly or tinyurl for easier sharing

## Troubleshooting 🔧

**Site not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check that the repository is Public
- Ensure `index.html` is in the root folder

**Button not working?**
- Make sure JavaScript is enabled in the browser
- Try refreshing the page

**Want to make changes?**
- Edit files directly on GitHub or locally
- Push changes and wait 1-2 minutes for updates to reflect

## License 📄

Free to use and customize for personal purposes. Share the love! 💕

---

Made with ❤️ for your special someone

Enjoy your Valentine's Day! 🌹
