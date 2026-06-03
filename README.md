# ⚡ DevToolkit — Premium Developer Utilities

> A beautiful, zero-dependency collection of **12 developer tools** that run entirely in your browser. No installs, no accounts, no internet required after loading.

![DevToolkit](https://img.shields.io/badge/Tools-12-6366f1?style=for-the-badge)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-10b981?style=for-the-badge)
![Offline Ready](https://img.shields.io/badge/Offline-Ready-06b6d4?style=for-the-badge)

## 🛠️ Tools Included

| # | Tool | Description |
|---|------|-------------|
| 1 | **JSON Formatter** | Format, minify & validate JSON with error highlighting |
| 2 | **Base64 Encoder/Decoder** | Encode and decode Base64 strings |
| 3 | **URL Encoder/Decoder** | Encode/decode URL components and query strings |
| 4 | **Hash Generator** | Generate SHA-1, SHA-256, SHA-384, SHA-512 hashes via Web Crypto API |
| 5 | **UUID Generator** | Bulk-generate RFC-4122 v4 UUIDs |
| 6 | **Color Converter** | Convert between HEX, RGB, HSL with a live palette picker |
| 7 | **Regex Tester** | Test regular expressions with live match highlighting |
| 8 | **JWT Decoder** | Decode JWT header, payload, and check token expiry |
| 9 | **Timestamp Converter** | Convert Unix timestamps ↔ human-readable dates |
| 10 | **Markdown Previewer** | Write Markdown, see live rendered output side-by-side |
| 11 | **Text Diff Viewer** | Compare two text blocks line-by-line with color highlights |
| 12 | **Cron Builder** | Build and decode cron expressions with plain-English descriptions |

## 🚀 Usage

Just open `index.html` in any modern browser — it's **100% client-side**:

```bash
# Clone the repo
git clone https://github.com/VarshuAi/dev-toolkit.git
cd dev-toolkit

# Open in browser (no server needed)
start index.html   # Windows
open index.html    # macOS
xdg-open index.html # Linux
```

Or visit the **GitHub Pages** live demo once enabled in repo settings.

## ✨ Features

- 🌑 **Dark mode by default** — easy on the eyes during late-night coding
- ⚡ **Zero dependencies** — pure HTML + CSS + Vanilla JS
- 📱 **Responsive** — works on desktop, tablet, and mobile
- 🔒 **Privacy-first** — everything runs locally; nothing leaves your browser
- 🎨 **Premium UI** — glassmorphism, micro-animations, gradient accents
- 📋 **One-click copy** — all outputs have a copy button

## 🎨 Tech Stack

- **HTML5** semantic markup  
- **CSS3** custom properties, grid, animations  
- **Vanilla JavaScript** — Web Crypto API for hashes, Clipboard API for copying  
- **Google Fonts** — Inter + JetBrains Mono  
- **No frameworks, no build step** — just open and go

## 📁 Structure

```
dev-toolkit/
├── index.html    # Everything lives here (self-contained)
└── README.md
```

## 🤝 Contributing

Pull requests are welcome! To add a new tool:

1. Fork the repo
2. Add a new nav button in the sidebar
3. Add a new `<div class="tool-panel" id="tool-yourname">` section
4. Add the corresponding JS logic
5. Submit a PR

## 📄 License

MIT — use it, fork it, ship it.

---

Made with ❤️ by **[VarshuAi](https://github.com/VarshuAi)**
