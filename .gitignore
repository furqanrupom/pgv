
# 🐾 PGV - Pug Viewer

**Live Pug (Jade) to HTML compiler with zero dependencies, instant preview, and dark mode.**

![PGV Preview](https://via.placeholder.com/800x400?text=PGV+Pug+Viewer+Demo)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## ✨ Features

- 🚀 **Zero Dependencies** - Pure vanilla JavaScript, no external libraries required
- 📝 **Full Pug Syntax Support** - Doctype, tags, attributes, nesting, inline tags, style./script. blocks, and more
- ⚡ **Live Preview** - Real-time rendering with debounce, plus Ctrl+Enter for manual compile
- 🎨 **Dark Minimal UI** - Eye-friendly dark theme with smooth gradients
- 📋 **Copy HTML** - One-click copy of compiled HTML output
- 🖱️ **Resizable Panes** - Drag to adjust source/preview width
- 🔍 **Error Feedback** - Clear compilation errors with line-specific messages
- 📊 **Status Metrics** - Line count, render time, and output size
- 🧭 **Sticky Navigation** - Persistent navbar with landing page and editor views
- 📱 **Responsive Design** - Works on desktop and tablet devices

## 🎯 Live Demo

Visit the live demo: [PGV - Pug Viewer](https://furqanRupom.github.io/pgv)

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/furqanRupom/pgv.git
   cd pgv
   ```

2. **Open the application**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # OR use a local server
   npx serve .
   ```

3. **Start writing Pug!**
   - Edit the left pane with Pug syntax
   - Watch the live preview update automatically
   - Use Ctrl+Enter to manually trigger compilation

### Usage Examples

#### Basic Pug Template
```pug
doctype html
html(lang="en")
  head
    title My Page
  body
    h1 Welcome to PGV
    p.p-1 This is a paragraph with class
    .container
      span#highlight Highlighted text
```

#### With Dynamic Data
```pug
- var name = "PGV User"
- var year = new Date().getFullYear()
h1 Hello #{name}!
footer © #{year} Furqan Ahmad
```

#### Inline Attributes and Classes
```pug
a.btn.btn-primary(href="https://github.com", target="_blank") GitHub
input(type="text", placeholder="Enter name", required)
```

#### Style and Script Blocks
```pug
style.
  .custom {
    color: #d4930a;
    font-weight: bold;
  }

script.
  console.log("Hello from Pug!");
```

## 🛠️ Built With

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS with CSS variables, Flexbox, Grid
- **Vanilla JavaScript** - Custom Pug parser implementation
- **Google Fonts** - Syne (sans-serif) + JetBrains Mono (monospace)

## 📁 Project Structure

```
pgv/
├── index.html          # Main application (single file)
├── README.md           # Documentation
└── LICENSE             # MIT License
```

## 🎮 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Tab` | Insert 2 spaces (indent) |
| `Ctrl + Enter` | Force compile/render |
| `Cmd + Enter` (Mac) | Force compile/render |

## 🧩 Supported Pug Features

- ✅ Doctype declaration
- ✅ HTML tags and custom elements
- ✅ ID (`#id`) and class (`.class`) selectors
- ✅ Attributes with parentheses `(key=value)`
- ✅ Nested indentation-based structure
- ✅ Inline tags using `#[tag content]`
- ✅ Style blocks (`style.`)
- ✅ Script blocks (`script.`)
- ✅ Text pipes (`|` for raw text)
- ✅ Comments (`//` comments)
- ✅ Void elements (img, br, input, etc.)
- ✅ Self-closing tags

## 🎨 Color Palette

| Variable | Hex | Usage |
|----------|-----|-------|
| `--bg` | `#0f0f11` | Main background |
| `--bg2` | `#17171a` | Secondary background |
| `--accent` | `#d4930a` | Primary accent |
| `--accent2` | `#f0aa1e` | Accent hover |
| `--text` | `#e8e6e0` | Primary text |
| `--text2` | `#888784` | Secondary text |
| `--green` | `#4caf7d` | Success indicator |
| `--red` | `#e05c5c` | Error indicator |

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Priorities

- [ ] Add support for Pug mixins
- [ ] Include/extends functionality
- [ ] Save/Load templates to localStorage
- [ ] Export/Import .pug files
- [ ] Add more keyboard shortcuts
- [ ] Mobile-responsive improvements
- [ ] Dark/Light theme toggle
- [ ] Multiple tabs for templates

## 📝 License

Distributed under the MIT License. See `LICENSE` file for more information.

## 👤 Author

**Furqan Ahmad**
- GitHub: [@furqanRupom](https://github.com/furqanRupom)
- Project Link: [https://github.com/furqanRupom/pgv](https://github.com/furqanRupom/pgv)
- Live Demo: [https://furqanRupom.github.io/pgv](https://furqanRupom.github.io/pgv)

## 🙏 Acknowledgments

- Inspired by the original Pug.js template engine
- Fonts provided by Google Fonts
- Icons and emojis for visual enhancement

## ⭐ Show Your Support

If you found this project helpful, please give it a ⭐ on GitHub and share it with others!

---

## 📊 Parser Implementation Details

PGV uses a custom-built Pug parser that:

1. **Parses indentation** to determine nesting levels
2. **Tokenizes tags**, IDs, classes, and attributes
3. **Handles block expansion** for text and child elements
4. **Processes inline tags** using regex-based transformation
5. **Generates clean HTML** with proper formatting

### Example Transformation

**Input (Pug):**
```pug
.container
  h1.title Hello World
  p#desc This is a #[strong great] tool
```

**Output (HTML):**
```html
<div class="container">
  <h1 class="title">Hello World</h1>
  <p id="desc">This is a <strong>great</strong> tool</p>
</div>
```

## 🐛 Known Issues & Limitations

- Mixins are not yet supported
- Includes/extends not implemented
- JavaScript iteration (each loops) limited
- No runtime variable interpolation beyond simple `#{...}`

## 🔮 Future Roadmap

- [ ] Full Pug.js compatibility mode
- [ ] Syntax highlighting for editor
- [ ] Auto-completion for tags
- [ ] Multiple file support
- [ ] Export as standalone HTML file
- [ ] Theme customization options
- [ ] Collaborative editing features

---

**Made with 🖤 by Furqan Ahmad**