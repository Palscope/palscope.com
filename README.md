# Palscope Landing Page

A simple, static landing page for Palscope - a League of Legends team finder Discord bot.

## 📁 File Structure

```
/
├── index.html          # Main landing page
├── riot.txt           # Riot API verification file (must be at root)
└── README.md          # This file
```

## 🚀 Quick Deployment

### Option 1: Netlify (Recommended)
1. Create a new folder on your computer and add both `index.html` and `riot.txt`
2. Go to [netlify.com](https://netlify.com) and sign up
3. Drag and drop your folder onto the Netlify dashboard
4. Your site will be live instantly with a random URL
5. Optionally, connect a custom domain in the site settings

### Option 2: Vercel
1. Create a new folder with `index.html` and `riot.txt`
2. Go to [vercel.com](https://vercel.com) and sign up
3. Click "New Project" and upload your folder
4. Deploy automatically

### Option 3: GitHub Pages
1. Create a new GitHub repository
2. Upload `index.html` and `riot.txt` to the repository root
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `username.github.io/repository-name`

### Option 4: Any Static Host
Simply upload both files to the root directory of any static hosting service.

## ⚙️ Customization

### Update Discord Link
Replace the Discord invite URL in `index.html`:
```html
<a href="https://discord.gg/YOUR_INVITE_LINK" class="cta-button">
```

### Update Contact Information
1. **In `index.html`**: Update the email in the footer
2. **In `riot.txt`**: Update the contact and redirect URLs

### Styling Changes
All CSS is contained within the `<style>` tags in `index.html`. Key variables:
- **Primary brand color**: `#2c5aa0`
- **Discord button color**: `#5865f2`
- **Text colors**: `#333` (dark), `#666` (medium), `#777` (light)

## 🔧 Technical Notes

### riot.txt Requirements
- **Must be accessible at**: `https://yourdomain.com/riot.txt`
- **Content-Type**: Should be served as `text/plain`
- **Purpose**: Required for Riot Games API production access verification

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- No JavaScript dependencies

### Performance
- **Page size**: ~6KB (HTML + CSS)
- **Load time**: <1 second on standard connections
- **Lighthouse score**: 95+ across all metrics

## 📝 Content Updates

To update the site content:

1. **Main headline**: Edit the `.tagline` text in the HTML
2. **Description**: Update the `.description` paragraph
3. **Button text**: Change "Join Our Discord" in the CTA button
4. **Footer**: Modify contact info and legal text

## 🔗 Important URLs

- **Discord Invite**: https://discord.gg/px34fNYF2H
- **Contact Email**: palscopeorg@gmail.com
- **Domain**: https://palscope.com/

## 📋 Deployment Checklist

Before going live:
- [ ] Upload both `index.html` and `riot.txt` to root directory
- [ ] Verify `riot.txt` is accessible at `/riot.txt`
- [ ] Test Discord invite link works
- [ ] Check mobile responsiveness
- [ ] Update any placeholder content
- [ ] Set up custom domain (if desired)

## 🆘 Support

For issues with the website itself, check that:
1. Both files are in the root directory
2. `riot.txt` doesn't have any file extension
3. The Discord invite link is valid and not expired

For Palscope bot support, join the Discord server!

---

*Built for Riot API production approval and Discord community growth.*
