# Archioz Design Studio — Website

**Live Preview:** Push to GitHub Pages to view live.

## Setup Instructions

1. Create a new GitHub repository named `archioz` (or any name)
2. Upload all files maintaining the folder structure:
   ```
   index.html
   assets/
     archioz-logo.png
   README.md
   ```
3. Go to Repository Settings → Pages → Branch: main → Save
4. Site will be live at: `https://yourusername.github.io/archioz/`

## AI Design Studio — API Key Setup

The AI Design Studio uses the Anthropic Claude API. For the prototype to work fully:

1. Get your API key from console.anthropic.com
2. In `index.html`, the API is called directly from the browser (prototype mode)
3. **For production:** Move the API call to a backend server (Node.js / n8n) and never expose the API key in frontend code

## Folder Structure
```
index.html          ← Complete single-page website
assets/
  archioz-logo.png  ← Company logo
README.md           ← This file
```

## Customisation Notes
- Colors: Edit CSS variables in `:root` at top of `<style>` tag
- Content: All text is inline in `index.html`
- Portfolio images: Replace Unsplash URLs with actual project photos
- Contact form: Connect to backend / Google Form / n8n webhook
- Payment: Integrate Razorpay payment gateway for DIY section

## Tech Stack
- Pure HTML/CSS/JavaScript — no frameworks, no build tools
- Google Fonts: Cormorant Garamond + Inter
- Images: Unsplash CDN (replace with actual photos)
- AI: Anthropic Claude Sonnet API

## Client Notes
- 4 style variants available (Dark Luxury / Light Minimal / Bold Modern / Warm Earthy)
- Currently live in: **Dark & Luxury** mode
- Portfolio placeholder images are from Unsplash — replace with actual project photography
- DIY AI Studio is a working prototype — needs API key and backend payment integration before public launch

Designed & Developed by **Scalioz Systems**, Chennai
