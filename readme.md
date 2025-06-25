> 🧪 **Side Project | Experimental Demo**  
> This Firefox extension, created circa 2019, brings a playful “doggify” twist to your browsing.  
> Built for fun and experimentation — not intended for production use.  
> Fully functional, but unsupported and unmaintained.  
>   
> 🐶 Because sometimes, the internet just needs more dogs.

---

# 🐾 Doggify-Firefox

A whimsical Firefox WebExtension that transforms your browsing experience by adding dog-themed flair. Originally built as a weekend project to explore browser APIs, DOM manipulation, and WebExtension architecture.

---

## 🧠 Features

- 🐕 Replaces certain images and words on webpages with dog-themed equivalents
- ⚙️ Includes a configurable settings screen (via `about:addons`)
- 🧩 Built as a lightweight Firefox WebExtension
- 🔁 Live DOM manipulation using content scripts
- 🌐 Local development & distribution ready (signed `.xpi` support)

---

## 🚀 Getting started

### 1. Clone the repo
```bash
git clone https://github.com/benjaminlukeclark/Doggify-Firefox.git
```

### 2. Load the extension in Firefox
1. Navigate to `about:debugging#/runtime/this-firefox`
2. Click **Load Temporary Add-on**
3. Select any file in the project directory (e.g., `manifest.json`)

---

## ⚙️ Configuration

After installing, visit `about:addons` and locate **Doggify**.  
Click the **Preferences** button to open the settings screen.  
You can adjust:

- Select a specific breed of dog to use when replacing images
- Choose how aggressively to “doggify” web pages

![Settings screen for Doggify](documentation/settings/Settings.PNG)

---

## 💡 Example usage

Visit your favorite news or blog site with Doggify enabled.  
Watch images get replaced with dog-themed equivalents.

![Original web page before Doggify](documentation/overview/NastyCades.PNG)

![Dog-themed transformation applied](documentation/overview/LovelyDoggos.PNG)

You can also manually “doggify” specific images via a context menu option.

![Before Doggify transformation](documentation/doggify/Doggify-me-pre.png)

![After Doggify transformation](documentation/doggify/Doggify-me-post.PNG)

---

## 🛠 Tech stack

- JavaScript
- Firefox WebExtension APIs
- DOM manipulation

---

## 🧪 Status & notes

- 🔸 Experimental and no longer maintained
- 🔸 Created as a creative exercise — no tests or CI/CD
- 🔸 Still works in modern Firefox as of 2025

---

## 📦 Project structure

```
Doggify-Firefox/
├── icons/             # Extension icons
├── scripts/           # Content and background scripts
├── options.html       # Settings/preferences screen
├── manifest.json      # Extension metadata
└── README.md
```

---

## 🐶 License

[MIT License](./LICENSE)

---

## 📬 Contact

Made with 💻 by [Benjamin Luke Clark](https://github.com/benjaminlukeclark)  
See more projects at [sudoblark.com](https://sudoblark.com)

---

![status: experimental](https://img.shields.io/badge/status-experimental-orange)
![tech: WebExtension](https://img.shields.io/badge/tech-WebExtension-blue)
