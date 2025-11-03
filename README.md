# Vema POS Promotional Website

A simple, responsive promotional and support website for Vema POS mobile application.

## Features

- Modern, responsive design
- Vietnamese language support
- Feature highlights
- Support contact information
- FAQ section
- Mobile-friendly layout

## Local Testing

Open `index.html` in your web browser:

```bash
open index.html
```

Or start a simple local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## Deployment Options

### 1. GitHub Pages (Free)
1. Create a new repository on GitHub
2. Push this code to the repository
3. Go to Settings > Pages
4. Select branch and folder
5. Your site will be live at `https://yourusername.github.io/repo-name`

### 2. Netlify (Free)
1. Visit [netlify.com](https://www.netlify.com)
2. Drag and drop the `promo-website` folder
3. Your site will be live instantly with a custom URL

### 3. Vercel (Free)
1. Visit [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload directly
3. Automatic deployment on every push

### 4. Firebase Hosting (Free)
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login and initialize
firebase login
firebase init hosting

# Deploy
firebase deploy
```

## Customization

Update the following in `index.html`:

- **Contact Email**: Change `support@vemapos.vn` to your actual email
- **Website URL**: Update `https://vemapos.vn` to your domain
- **App Store Link**: Replace `https://apps.apple.com/app/vemapos` with your actual App Store URL
- **Support Hours**: Modify working hours as needed

## File Structure

```
promo-website/
├── index.html          # Main website file
└── README.md          # This file
```

## Support

For questions about the website, contact support@vemapos.vn
