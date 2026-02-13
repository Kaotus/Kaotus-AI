# 📸 Nano Pro Studio - AI Photography PWA

Professional AI photography app with Samsung S23 Ultra inspired design. Generate ultra-realistic photos using Nano Banana Pro AI.

## ✨ Features

- **Progressive Web App** - Install on Android, iOS, and Desktop
- **Offline Support** - Works without internet after installation
- **Professional Camera UI** - Samsung S23 Ultra inspired design
- **Batch Generation** - Generate 4 photos at once
- **Multiple Aspect Ratios** - Portrait (9:16), Landscape (16:9), Square (1:1)
- **Reference Images** - Upload reference photos for better results
- **Download Gallery** - Save and manage your generated photos

## 🚀 Installation

### Android

1. Open the app in Chrome or Samsung Internet Browser
2. Tap the menu (⋮) in the top right
3. Select "Install app" or "Add to Home screen"
4. Confirm installation
5. Find "Nano Pro Studio" on your home screen

### iOS

1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it and tap "Add"
5. Launch from your home screen

### Desktop

1. Open the app in Chrome, Edge, or Brave
2. Look for the install icon (⊕) in the address bar
3. Click "Install"
4. Launch from your applications

## 📝 How to Use

1. **Describe Your Photo**: Enter a detailed description
   - Example: "Street photography in Tokyo at night, neon lights, rainy streets"
   - Example: "Portrait of a woman, natural lighting, soft focus"

2. **Choose Aspect Ratio**: Select portrait, landscape, or square

3. **Add References** (Optional): Upload reference images for style guidance

4. **Generate**: Tap "Capture 4 Photos" button

5. **Download**: Tap any generated photo to download it

## 🎨 Tips for Best Results

- Be specific with your descriptions
- Mention lighting conditions (natural, golden hour, studio, etc.)
- Include camera details for realism ("shot on 35mm", "shallow depth of field")
- Add style keywords ("cinematic", "minimalist", "vibrant colors")
- Use the prefix "Hyper-realistic photography" for photorealistic results

## 🛠️ Technical Details

- **Framework**: Vanilla JavaScript PWA
- **AI Model**: Nano Banana Pro (via Puter.js)
- **Service Worker**: Offline caching and background sync
- **Manifest**: Full PWA support with shortcuts

## 📦 Files Structure

```
nano-pro-studio/
├── index.html          # Main app file
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icon-192.png       # App icon (192x192)
├── icon-512.png       # App icon (512x512)
└── README.md          # This file
```

## 🌐 Deployment

### GitHub Pages
1. Push all files to a GitHub repository
2. Go to Settings → Pages
3. Select main branch as source
4. Access at `https://yourusername.github.io/repo-name`

### Netlify
1. Drag and drop the folder to Netlify
2. App is live instantly

### Vercel
```bash
vercel --prod
```

## 🔧 Customization

Edit colors in `index.html` CSS variables:
```css
:root {
    --gold: #d4af37;      /* Primary color */
    --bg: #000000;        /* Background */
    --surface: #1a1a1a;   /* Cards/surfaces */
    --border: #333;       /* Borders */
}
```

## 📱 Browser Support

- ✅ Chrome/Edge 90+
- ✅ Safari 14+
- ✅ Firefox 90+
- ✅ Samsung Internet 14+

## 🐛 Known Issues

- Rate limits may apply from Puter.js API
- Large batches may take time to generate
- Requires internet for first load

## 📄 License

MIT License - Feel free to modify and use!

## 🙏 Credits

- AI Model: Nano Banana Pro
- Platform: Puter.js
- Design: Inspired by Samsung S23 Ultra

---

Made with ❤️ for photographers and creators
