<p align="center">
  <img src="https://img.shields.io/badge/Office--Craft-v3.0-6366f1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHJlY3QgeD0iMyIgeT0iMyIgd2lkdGg9IjE4IiBoZWlnaHQ9IjE4IiByeD0iMyIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIi8+PHBhdGggZD0iTTggOGg4TTggMTJoNk04IDE2aDQiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMiIgZmlsbD0ibm9uZSIvPjwvc3ZnPg==&logoColor=white" alt="Office-Craft" />
  <img src="https://img.shields.io/badge/100%25_Client--Side-No_Server_Needed-10b981?style=for-the-badge" alt="Client Side" />
  <img src="https://img.shields.io/badge/AI_Powered-WebLLM_%2B_Transformers.js-f59e0b?style=for-the-badge" alt="AI Powered" />
  <img src="https://img.shields.io/badge/License-MIT-22d3ee?style=for-the-badge" alt="MIT License" />
</p>

# ✨ Office-Craft

**A complete, browser-based office suite — no installation, no servers, no accounts.**

Office-Craft is a free, open-source alternative to Microsoft Office and Google Workspace that runs entirely in your browser. It includes a word processor, presentation tool, and spreadsheet — all with built-in **local AI** powered by WebLLM and Transformers.js.

> 🔒 **Your data never leaves your device.** Everything runs client-side. No cloud. No telemetry.

---

## 🚀 Live Demo

**[Open Office-Craft →](https://pariharshyamu.github.io/office-craft/)**

---

## 📦 The Suite

### 📝 Wordcraft — Word Processor
A rich-text word processor with a clean, distraction-free writing experience.

| Feature | Details |
|---|---|
| **Rich Text Editing** | Bold, italic, underline, headings, lists, alignment, colors, highlights |
| **AI Assistant** | Local AI with WebLLM (Qwen 0.5B) — summarize, rewrite, fix grammar, expand |
| **AI Algorithm Tools** | 11 tools: word frequency, readability, sentiment, key phrases, statistics, long sentences, repeated words, outline, insert/replace, markdown export |
| **Version Snapshots** | Save up to 15 named snapshots, restore or delete anytime |
| **Readability Score** | Live Flesch reading ease score with Easy/OK/Hard indicator |
| **File Support** | Import DOCX · Export PDF, DOCX, Markdown, TXT |
| **Writing Stats** | Live word count, character count, reading time, paragraph count |
| **Focus Mode** | Distraction-free writing with dimmed UI |
| **Dark Mode** | Toggle between light and dark themes |
| **Templates** | Built-in document templates for quick start |
| **Find & Replace** | Full find and replace with highlighting |
| **Comments** | Add and resolve comments on your document |

### 🎨 SlidesCraft — Presentations
A powerful presentation tool with smooth animations, themes, and voice control.

| Feature | Details |
|---|---|
| **7 Slide Templates** | Blank, Title, Content, Two-Column, Image+Text, Quote, Section Break |
| **Element System** | Text, shapes (rect, ellipse, triangle), images, icons, tables, charts, emoji |
| **Animations** | 6 entrance animations: fade, slide-up, zoom, bounce, slide-left, slide-right |
| **Slide Transitions** | Slide, fade, zoom, flip, none — per-slide control |
| **Themes & Gradients** | Pre-built slide themes with gradient backgrounds |
| **Icon Library** | 200,000+ icons via Iconify API — search and insert instantly |
| **Photo Search** | Free stock photos (Unsplash/Lorem.space) — search and add to slides |
| **Presenter Mode** | Fullscreen with speaker notes, laser pointer, drawing tools, timer |
| **Voice Commands** | Hands-free slide control: "next slide", "go back", "add text" |
| **AI Assistant** | Local AI for content generation, bullet points, speaker notes, design tips |
| **AI Algorithm Tools** | 5 tools: presentation stats, content density, consistency check, text extract, outline |
| **File Support** | Import/Export PPTX · Export PDF |
| **Customizable UI** | 5 themes, 3 shapes, 3 densities, accent colors, canvas patterns |

### 📊 SheetCraft — Spreadsheet
A feature-rich spreadsheet with 80+ formula functions and AI integration.

| Feature | Details |
|---|---|
| **80+ Formulas** | SUM, AVERAGE, VLOOKUP, IF, IFS, COUNTIF, STDEV, MEDIAN, and many more |
| **Math Functions** | ABS, SQRT, POWER, ROUND, FLOOR, CEILING, SIN, COS, TAN, LOG, EXP, PI |
| **Text Functions** | UPPER, LOWER, TRIM, LEFT, RIGHT, MID, SUBSTITUTE, CONCATENATE, TEXTJOIN |
| **Date Functions** | TODAY, NOW, YEAR, MONTH, DAY, DATEDIF, NETWORKDAYS, WEEKDAY |
| **Statistical** | STDEV, VAR, MEDIAN, LARGE, SMALL, RANK, PERCENTILE |
| **Conditional Formatting** | 8 rule types: greater, less, equal, not-blank, between, contains, negative, positive |
| **Sparklines** | `=SPARKLINE(A1:A10)` for line charts · `=SPARKBAR(A1:A10)` for bar charts |
| **Charts** | Bar, line, area, pie, donut, scatter, radar, heatmap, waterfall, box plot, bubble |
| **AI Assistant** | Local AI with TinyLlama — ask for formula help, data analysis, chart suggestions |
| **AI Algorithm Tools** | 5 tools: spreadsheet stats, column analysis, data quality, outlier detection, formula suggestions |
| **File Support** | Import CSV/XLSX · Export CSV, XLSX, JSON |
| **Multi-Sheet** | Multiple sheet tabs with add/delete/rename |
| **Cell Formatting** | Bold, italic, underline, colors, fill, alignment, number formats, merge, wrap |
| **Find & Replace** | Search across all cells with replace |
| **Undo/Redo** | Full undo/redo stack |
| **Freeze Panes** | Freeze rows and columns for easier navigation |

---

## 🧠 AI — Runs Locally in Your Browser

Office-Craft uses **WebLLM** and **Transformers.js** to run AI models directly in your browser via WebGPU or WebAssembly. No API keys, no cloud services, no data sent anywhere.

| App | AI Model | Runtime |
|---|---|---|
| Wordcraft | Qwen2.5-0.5B-Instruct | WebLLM (WebGPU) |
| SlidesCraft | Qwen2.5-0.5B-Instruct | WebLLM (WebGPU) |
| SheetCraft | TinyLlama-1.1B | WebLLM (WebGPU) |

**Requirements for AI features:**
- Chrome 113+ or Edge 113+ (WebGPU support)
- ~1-2 GB free RAM for model loading
- GPU with WebGPU support (NVIDIA, AMD, Apple Silicon, Intel Arc)

> 💡 The apps work perfectly **without** AI too — the AI features are optional and load on-demand.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | Vanilla HTML, CSS, JavaScript (zero dependencies for core) |
| **AI** | [WebLLM](https://github.com/nicklimmm/web-llm) + [Transformers.js](https://github.com/xenova/transformers.js) |
| **DOCX** | [docx.js](https://github.com/dolanmiu/docx) |
| **PPTX** | [PptxGenJS](https://github.com/gitbrent/PptxGenJS) |
| **XLSX** | [SheetJS](https://github.com/SheetJS/sheetjs) |
| **Charts** | Pure Canvas/SVG (no chart library) |
| **Icons** | [Iconify API](https://iconify.design/) (200K+ icons) |
| **Fonts** | Google Fonts (DM Sans, Syne, JetBrains Mono) |

**No build step.** No Node.js. No npm. No webpack. Just open the HTML files.

---

## 📁 Project Structure

```
office-craft/
├── index.html          # Home dashboard with app launcher
├── Wordcraft.html      # Word processor (single file, ~4800 lines)
├── SlidesCraft.html    # Presentation tool (single file, ~4990 lines)
├── SheetCraft.html     # Spreadsheet (single file, ~4270 lines)
├── .gitignore
└── README.md
```

Each app is a **single, self-contained HTML file** — no external JS files, no CSS files, no assets to manage. Just copy and open.

---

## 🚀 Getting Started

### Option 1: Use Online
Visit **[pariharshyamu.github.io/office-craft](https://pariharshyamu.github.io/office-craft/)**

### Option 2: Run Locally
```bash
git clone https://github.com/pariharshyamu/office-craft.git
cd office-craft
# Open index.html in your browser — that's it!
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

### Option 3: Deploy Your Own
Since it's all static files, deploy anywhere:
- **GitHub Pages** — push and enable in settings
- **Netlify** — drag and drop the folder
- **Vercel** — `npx vercel`
- **Cloudflare Pages** — connect your repo
- **Any static host** — just upload the HTML files

---

## ⌨️ Keyboard Shortcuts

### Wordcraft
| Shortcut | Action |
|---|---|
| `Ctrl+B/I/U` | Bold / Italic / Underline |
| `Ctrl+Shift+S` | Save Snapshot |
| `Ctrl+S` | Save Document |
| `Ctrl+F` | Find & Replace |
| `Ctrl+P` | Export PDF |
| `F7` | Spell Check |

### SlidesCraft
| Shortcut | Action |
|---|---|
| `←/→` | Previous / Next Slide |
| `N` | New Slide |
| `Delete` | Delete Selected Element |
| `Ctrl+Z/Y` | Undo / Redo |
| `F` | Toggle Fullscreen |
| `Escape` | Exit Presenter |

### SheetCraft
| Shortcut | Action |
|---|---|
| `Ctrl+C/X/V` | Copy / Cut / Paste |
| `Ctrl+Z/Y` | Undo / Redo |
| `Ctrl+F` | Find & Replace |
| `Ctrl+D/R` | Fill Down / Right |
| `Ctrl+G` | Go To Range |
| `Ctrl+/` | Show All Shortcuts |
| `S` | Toggle Selection Tool |
| `Tab` | Move to Next Cell |

---

## 🎨 Design Philosophy

- **Glassmorphism UI** with subtle blur effects and gradients
- **Dark mode first** design across all apps
- **Responsive** — works on desktop, tablet, and mobile
- **Smooth animations** with CSS transitions and keyframes
- **Zero-dependency core** — every app is a single HTML file
- **Privacy-first** — all data stays in `localStorage`, never sent anywhere

---

## 📄 License

MIT License — free for personal and commercial use.

---

## 🤝 Contributing

Contributions are welcome! Since each app is a single HTML file, the barrier to entry is low:

1. Fork the repo
2. Edit the HTML file you want to improve
3. Test in your browser
4. Submit a PR

**Ideas for contributions:**
- More slide templates and themes
- Additional spreadsheet formula functions
- Improved AI prompts and tool integrations
- Accessibility improvements
- Internationalization (i18n)
- PWA support with service workers

---

## 🙏 Acknowledgments

- [WebLLM](https://github.com/nicklimmm/web-llm) for browser-based LLM inference
- [Transformers.js](https://github.com/xenova/transformers.js) for ML in the browser
- [Iconify](https://iconify.design/) for the massive icon library
- [Google Fonts](https://fonts.google.com/) for beautiful typography

---

<p align="center">
  <strong>Built with ❤️ — no servers, no accounts, no tracking.</strong><br>
  <em>Your documents. Your device. Your privacy.</em>
</p>
