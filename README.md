# Saanmu & Abinaya Wedding Website

This is a customized wedding website based on the Theatre Demo template, personalized for Saanmu & Abinaya's wedding on May 27, 2026.

## 🎊 Wedding Details

- **Couple:** Saanmu & Abinaya
- **Date:** May 27, 2026
- **Venue:** Narayanasamy Gounder Thirumana Mandapam
- **Address:** Nearby Pappireddipatti Bus Stand, Salem Main Road, Pappireddipatti, Dharmapuri-636905, Tamil Nadu
- **Google Maps:** [View Location](https://share.google/PFaN4y0ZktKWLIwBC)

## 📁 Project Structure

```
theatre-demo-clone/
├── index.html              # Main HTML file
├── favicon.png            # Site favicon
├── assets/                # All site assets
│   ├── index-BBIwAgSn.js      # Main JavaScript bundle (React SPA)
│   ├── index-bYuRLTYZ.css     # Main stylesheet (Tailwind CSS)
│   ├── curtain-closed-Bpkadld4.jpg
│   ├── curtain-open-C9MqdT6G.jpg
│   ├── curtain-video-BAKLj3Y5.mp4
│   ├── scratch-gold-DQrdz0lH.png
│   ├── venue-illustration-DebdGS8I.png
│   ├── menu-frame-BFE5kCs7.png
│   ├── dresscode-illustration-BT5yPEQh.png
│   ├── gift-icon-BssCdzah.png
│   └── thedigitalyes-logo-B7PGcLFc.png
└── README.md              # This file
```

## 🚀 Quick Start

### Option 1: Using Python's Built-in Server

```powershell
cd C:\Users\User\Documents\wedding\theatre-demo-clone
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

### Option 2: Using Node.js http-server

```powershell
# Install http-server globally (first time only)
npm install -g http-server

# Run the server
cd C:\Users\User\Documents\wedding\theatre-demo-clone
http-server -p 8000
```

Then open http://localhost:8000 in your browser.

### Option 3: Using VS Code Live Server Extension

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🎨 Features

This wedding website includes:

- **Intro Section**: Animated curtain reveal with video
- **Reveal Section**: Interactive scratch-off date reveal
- **Countdown Timer**: Live countdown to the wedding date (May 27, 2026)
- **Venue Information**: Details about Villa Medicea di Artimino
- **Menu Display**: Wedding menu with Italian cuisine
- **Dress Code**: Formal attire guidelines with illustration
- **Gifts Section**: Bank transfer details for wedding gifts
- **Transport Information**: Bus schedule from Florence
- **RSVP Form**: Guest confirmation form (non-functional in static version)
- **Thank You**: Closing message

## 🛠️ Technology Stack

- **Framework**: React (built and bundled)
- **Styling**: Tailwind CSS with custom design tokens
- **Animations**: Framer Motion
- **Fonts**:
  - Cormorant Garamond (display)
  - Great Vibes (script)
  - Lora (body)
- **Build Tool**: Vite (pre-built)

## 📝 Customizations Made

### Content Updates:

- ✅ Couple names changed to: **Saanmu & Abinaya**
- ✅ Wedding date changed to: **May 27, 2026**
- ✅ Venue changed to: **Narayanasamy Gounder Thirumana Mandapam**
- ✅ Address updated to Tamil Nadu location
- ✅ Google Maps link added with map icon

### Sections Removed:

- ✅ Buy Now button and branding removed
- ✅ Language selection button removed
- ✅ "Extra: custom illustration" badge removed
- ✅ Dress Code section hidden
- ✅ Gifts/Wedding Registry section hidden
- ✅ RSVP/Confirm Attendance form hidden

### Technical Implementation:

- Custom CSS file (`custom.css`) for styling and hiding unwanted sections
- JavaScript injection in `index.html` to dynamically hide sections and add map link
- Direct string replacements in the minified JavaScript bundle for content changes

## 🛠️ How It Works

The customizations are applied through three methods:

1. **Direct JS Edits:** Names, dates, and venue text replaced directly in the minified JavaScript
2. **Custom CSS:** Hides unwanted sections using display: none
3. **Runtime JavaScript:** Dynamically hides sections and injects the Google Maps link after page load

## 📝 Customization

To further customize the content, you can edit:

1. **Quick text changes**: Use browser dev tools to inspect and manually edit the minified JS
2. **Full rebuild**: Request the original source code or rebuild from scratch using React + Vite

### Key customization points in the JS bundle:

- Wedding date: Search for `"2026-05-27"` or `"May 27, 2026"`
- Couple names: Search for `"Saanmu"` and `"Abinaya"`
- Venue details: Search for `"Villa Medicea di Artimino"`
- Bank details: Search for `"IBAN"`

## 🌐 Deployment

### Deploy to Netlify

1. Create a Netlify account
2. Drag and drop the entire `theatre-demo-clone` folder
3. Your site will be live instantly

### Deploy to Vercel

1. Install Vercel CLI: `npm install -g vercel`
2. Run: `vercel` in the project directory
3. Follow the prompts

### Deploy to GitHub Pages

1. Create a GitHub repository
2. Push the files to the repository
3. Go to Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://yourusername.github.io/repo-name/`

## ⚠️ Important Notes

### RSVP Form

The RSVP form is currently **non-functional** as it was connected to a backend service in the original site. To make it functional, you need to:

1. Set up a backend service (e.g., Formspree, Netlify Forms, or custom API)
2. Modify the JavaScript bundle to point to your endpoint

### Content Ownership

- This is a clone of a demo wedding website
- Ensure you have permission to use all content before deploying publicly
- The original demo is from "The Digital Yes" (https://www.thedigitalyes.com/)
- Replace placeholder content (names, dates, bank details, etc.) with your own information

### Analytics Removed

The original analytics tracking script has been removed from this clone.

## 📱 Responsive Design

The site is fully responsive and optimized for:

- Desktop (1920px and above)
- Tablet (768px - 1919px)
- Mobile (320px - 767px)

## 🎯 Browser Compatibility

Tested and working on:

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This is a cloned demo site. Please respect the original creator's intellectual property rights and customize appropriately for your use case.

---
