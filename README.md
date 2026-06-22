# IBM Plex Glyph Viewer

A compact, IBM Carbon Design System compliant glyph display application for viewing and copying IBM Plex font characters.

## 🚀 Live Demo

[View Live Demo](https://yourusername.github.io/plex-glyph-viewer/)

> **Note:** Replace `yourusername` with your GitHub username after deploying to GitHub Pages.

## ✨ Features

- **IBM Carbon Design System**: Fully compliant with Carbon design tokens and styling
- **IBM Plex Fonts**: Supports both IBM Plex Sans and IBM Plex Mono
- **Click-to-Copy**: Click any glyph to instantly copy it to your clipboard
- **Multiple Unicode Ranges**: Browse through 12 different Unicode character ranges:
  - Basic Latin (0020-007F)
  - Latin-1 Supplement (00A0-00FF)
  - Latin Extended-A (0100-017F)
  - Latin Extended-B (0180-024F)
  - Greek and Coptic (0370-03FF)
  - Cyrillic (0400-04FF)
  - General Punctuation (2000-206F)
  - Currency Symbols (20A0-20CF)
  - Arrows (2190-21FF) - **Default View**
  - Mathematical Operators (2200-22FF)
  - Box Drawing (2500-257F)
  - Geometric Shapes (25A0-25FF)
- **Responsive Design**: Works on desktop and mobile devices
- **Visual Feedback**: Hover effects and copy notifications

## 🎯 Usage

1. Open `index.html` in a web browser
2. Select a font family (IBM Plex Sans or IBM Plex Mono)
3. Choose a Unicode range to display
4. Click on any glyph to copy it to your clipboard
5. A notification will confirm the copy action

## 🚀 Deployment to GitHub Pages

1. Create a new repository on GitHub
2. Push this code to your repository:
   ```bash
   git add .
   git commit -m "Initial commit: IBM Plex Glyph Viewer"
   git branch -M main
   git remote add origin https://github.com/yourusername/plex-glyph-viewer.git
   git push -u origin main
   ```
3. Go to your repository Settings → Pages
4. Under "Source", select "Deploy from a branch"
5. Select the `main` branch and `/ (root)` folder
6. Click Save
7. Your site will be live at `https://yourusername.github.io/plex-glyph-viewer/`

## 🎨 Design Principles

- Uses IBM Carbon Design System color tokens
- IBM Plex typography throughout
- Compact grid layout for efficient browsing
- Smooth transitions following Carbon motion guidelines
- Accessible keyboard navigation and focus states

## 🛠️ Technical Details

- Pure HTML, CSS, and JavaScript (no build process required)
- Uses Google Fonts CDN for IBM Plex fonts
- Carbon Components CSS for base styling
- Clipboard API for copy functionality
- Responsive grid with CSS Grid

## 📦 Project Structure

```
plex-glyph-viewer/
├── index.html          # Main application file
├── README.md           # This file
└── .gitignore         # Git ignore rules
```

## 🌐 Browser Compatibility

Works in all modern browsers that support:
- CSS Grid
- Clipboard API
- ES6 JavaScript

## 📄 License

MIT License - see the [LICENSE](LICENSE) file for details.

This project showcases IBM Carbon Design System and IBM Plex fonts.

## 🙏 Acknowledgments

- [IBM Carbon Design System](https://carbondesignsystem.com/)
- [IBM Plex Fonts](https://www.ibm.com/plex/)

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

---

Made with ❤️ using IBM Carbon Design System