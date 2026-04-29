# 🐾 PGV - Pug Viewer

**Live Pug (Jade) to HTML compiler with zero dependencies, instant preview, and dark mode.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## ✨ Features

- 🚀 **Zero Dependencies** - Pure vanilla JavaScript, no external libraries required
- 📝 **Full Pug Syntax** - Doctype, tags, attributes, nesting, inline tags, style/script blocks
- ⚡ **Live Preview** - Real-time rendering with debounce + Ctrl+Enter manual compile
- 🎨 **Dark Minimal UI** - Eye-friendly dark theme with glass-morphism design
- 📋 **Copy HTML** - One-click copy of compiled HTML output
- 🖱️ **Resizable Panes** - Drag to adjust source/preview width
- 🔍 **Error Feedback** - Clear compilation errors with detailed messages
- 📊 **Status Metrics** - Line count, render time, and output size

## 🚀 Quick Start

```bash
git clone https://github.com/furqanRupom/pgv.git
cd pgv
open index.html
```

Or use a local server:
```bash
npx serve .
```

## 🎮 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Tab` | Insert 2 spaces |
| `Ctrl/Cmd + Enter` | Force compile/render |

## 🧩 Supported Pug Features

- ✅ Doctype declaration
- ✅ HTML tags and custom elements
- ✅ ID (`#id`) and class (`.class`) selectors
- ✅ Attributes with parentheses `(key=value)`
- ✅ Nested indentation-based structure
- ✅ Inline tags using `#[tag content]`
- ✅ Style blocks (`style.`)
- ✅ Script blocks (`script.`)
- ✅ Text pipes (`\|`)
- ✅ Comments (`//`)
- ✅ Void elements (img, br, input, etc.)

## 📝 Usage Examples

```pug
doctype html
html(lang="en")
  head
    title My Page
  body
    h1 Welcome to PGV
    .container
      p#desc This is a #[strong great] tool
      a.btn(href="https://github.com") GitHub
```

## 🛠️ Built With

- HTML5 / CSS3 (Tailwind CSS)
- Vanilla JavaScript (Custom Pug parser)
- Google Fonts (Syne + JetBrains Mono)
- Font Awesome Icons

## 📁 Project Structure

```
pgv/
├── index.html          # Single-file application
├── README.md           # Documentation
└── LICENSE             # MIT License
```

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` file for more information.

## 👤 Author

**Furqan Ahmad**
- GitHub: [@furqanRupom](https://github.com/furqanRupom)
- Project: [github.com/furqanRupom/pgv](https://github.com/furqanRupom/pgv)

## 🙏 Acknowledgments

- Inspired by Pug.js template engine
- Icons by Font Awesome

---

**Made with 🖤 by Furqan Ahmad**