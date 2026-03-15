# Eid Mubarak 🌙

A beautiful, premium, single-page website to wish elders "Eid Mubarak" and request Eidi (money gift) in a respectful and emotional way.

## 🌟 Features

### Design & Animation
- **Gorgeous glowing moon** with realistic craters and soft halo glow
- **Animated twinkling stars** on canvas background
- **Shooting stars** that randomly streak across the sky
- **Beautiful confetti** animations
- **Glassmorphism cards** with smooth hover effects
- **Dark premium green & gold theme** with Islamic aesthetic

### Functionality
- **QR Code Payment** - Scan to send Eidi via UPI (PhonePe, GPay, Paytm, WhatsApp Pay)
- **Contact Methods** - Call, WhatsApp, SMS buttons
- **Background Music** - Optional Eid music toggle
- **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- **Smooth Animations** - Scroll animations and interactive elements

### Sections
1. **Hero Section** - Stunning moon and greeting with Arabic calligraphy
2. **Message Section** - Heartfelt request for Eidi with humor
3. **QR Payment** - Easy digital payment via UPI
4. **Phone Contact** - Direct contact with 3 communication methods
5. **Quotes** - Beautiful Islamic Eid wishes and duas
6. **Footer** - Elegant closing message

## 🚀 Quick Start

### Setup
1. Clone the repository:
```bash
git clone https://github.com/yourusername/eid.git
cd eid
```

2. Open in browser:
```bash
# Simply open the HTML file in your browser
open eid-mubarak.html
# or on Windows
start eid-mubarak.html
```

## ⚙️ Configuration

Edit the `CONFIG` object in `eid-mubarak.html` to customize:

```javascript
const CONFIG = {
    phone: '+918217043090',        // Your phone number
    qrImage: 'qr-code.jpeg',       // Path to your QR code image
    music: 'https://...'           // Music URL (optional)
};
```

### Steps:
1. **Update Phone Number** - Replace `+918217043090` with your number
2. **Add QR Code** - Replace `qr-code.jpeg` with your UPI payment QR code image
3. **Optional Music** - Add a music URL or leave as is

## 📱 Customize

### Phone Number
Find this line in the script:
```javascript
const CONFIG = {
    phone: '+918217043090',  // ← Change this
```

### QR Code
Upload your QR code image and update:
```javascript
qrImage: 'qr-code.jpeg',  // ← Change to your QR path
```

### Colors & Text
- Edit color variables in `:root` in the CSS
- Modify text content directly in HTML sections

## 🎨 Color Scheme

| Element | Color | Hex |
|---------|-------|-----|
| Primary Green | Deep Green | #051510 |
| Gold | Bright Gold | #ffeaa7 |
| Accent | Light Gold | #f0d78c |
| Text | Cream | #faf8f0 |

## 📦 Files

- `eid-mubarak.html` - Main website (HTML + CSS + JS all in one)
- `qr-code.jpeg` - Your UPI payment QR code
- `README.md` - Documentation

## 🔧 Browser Support

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Fully responsive

## 💡 Tips

1. **Share on WhatsApp** - Direct link works perfect on WhatsApp
2. **Mobile Friendly** - Optimized for small screens
3. **Instant Loading** - Single HTML file, super fast
4. **No Dependencies** - Pure HTML/CSS/JavaScript

## 🎁 How It Works

1. Visitor opens the website
2. Sees beautiful Eid greeting with glowing moon
3. Reads emotional message
4. Scans QR code to send Eidi via UPI, OR
5. Calls/WhatsApps/SMSs using contact buttons
6. Enjoys the confetti and shooting stars! ✨

## 📄 License

Feel free to use, modify, and share with elders! Made with ❤️

## 🤲 Dua

May Allah accept from us and you. Eid Mubarak! 🌙

---

**Made with ❤️ for the best elders ever**
