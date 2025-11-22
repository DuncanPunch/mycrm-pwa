# myCRM - Personal Relationship Manager PWA

A secure, offline-capable Progressive Web App for managing your personal relationships, notes, and important details about the people in your life.

## Features

- 🔒 **PIN-Protected** - Keep your personal data secure
- ⭐ **Favorites** - Quick access to your most important contacts
- 📝 **Quick Notes** - Capture thoughts on the go, even from the lock screen
- 🏷️ **Tagging System** - Organize notes by category
- 🌙 **Dark Mode** - Easy on the eyes
- 📱 **PWA** - Install on your phone like a native app
- 💾 **Offline Mode** - Works without internet connection
- 📤 **Export Data** - Export your contacts to CSV

## Deployment Instructions

### Option 1: Deploy to Vercel (Recommended - FREE)

1. **Install Git and push to GitHub:**
   ```bash
   # Navigate to the project folder
   cd mycrm-pwa
   
   # Initialize git
   git init
   git add .
   git commit -m "Initial commit"
   
   # Create a new repo on GitHub, then:
   git remote add origin https://github.com/YOUR_USERNAME/mycrm-pwa.git
   git push -u origin main
   ```

2. **Deploy on Vercel:**
   - Go to https://vercel.com
   - Sign up/login with your GitHub account
   - Click "New Project"
   - Import your `mycrm-pwa` repository
   - Click "Deploy"
   - Done! Vercel will give you a URL

3. **Install on your Android phone:**
   - Open the Vercel URL in Chrome on your Android
   - Tap the menu (three dots) → "Add to Home Screen" or "Install App"
   - The app will appear on your home screen like a native app!

### Option 2: Deploy to Netlify (Also FREE)

1. **Push to GitHub** (same as above)

2. **Deploy on Netlify:**
   - Go to https://netlify.com
   - Sign up/login with GitHub
   - Click "Add new site" → "Import an existing project"
   - Select your GitHub repo
   - Click "Deploy"
   - Done!

3. **Install on Android** (same as above)

## Project Structure

```
mycrm-pwa/
├── index.html           # Main app file
├── manifest.json        # PWA manifest
├── service-worker.js    # Offline functionality
├── icons/
│   ├── icon-192.png    # App icon (192x192)
│   └── icon-512.png    # App icon (512x512)
└── README.md           # This file
```

## Usage

### Default PIN
- Default PIN is `1234`
- Change it in Settings after first login

### Quick Note from Lock Screen
- Tap the green + button on the lock screen
- Add a note and link it to a contact (or create a new one)
- Perfect for capturing thoughts on the go

### Managing Contacts
- Tap the "People" tab to see all contacts
- Tap + button to add new contacts
- Tap any contact to view details and add notes
- Swipe left on a note to dismiss it from the dashboard

## Development

To modify the app:
1. Edit `index.html` (all app logic is in this single file)
2. Test locally by opening `index.html` in a browser
3. Push changes to GitHub
4. Vercel/Netlify will auto-deploy the updates

## Privacy & Security

- All data is stored **locally** on your device using `localStorage`
- No data is sent to any servers
- PIN protection keeps your data secure
- Works completely offline after first load

## Browser Support

- Chrome/Edge (recommended for Android)
- Safari (iOS)
- Firefox

## License

Free to use and modify for personal use.
