# Contextify for Coders ✨
> **Instant AI-powered code explanations, right in your browser!**
> Select any code snippet on any website and get clear, structured explanations with usage examples and syntax-highlighted code blocks.

---

## 🚀 Features
- ✅ **AI-Powered Explanations** using **Google Gemini 1.5 Flash** (Free Tier).
- ✅ **Supports Multiple Languages**: JavaScript, Python, Java, C++, HTML, CSS, SQL, and more.
- ✅ **Beautiful Tooltip UI** with:
  - Glassmorphism design & smooth animations.
  - Syntax highlighting for code blocks.
  - Copy button with success feedback.
- ✅ **Popup Dashboard** with:
  - Step-by-step instructions.
  - Test Code Snippet feature for quick demo.
  - Dark mode support.
- ✅ **Advanced Language Detection** and Markdown parsing.

## ⚙️ Installation
1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/your-username/contextify-for-coders.git
   ```
2. Open **Chrome Extensions** → Enable **Developer Mode**.
3. Click **Load Unpacked** → Select the `contextify-for-coders` folder.

---

## 🔑 Setup API Key
1. Get your **Google Gemini API key**:
   - [Sign up on Google AI Studio](https://ai.google.dev/gemini-api/docs/get-started/tutorial?lang=javascript)
2. Open **Extension Options** → Paste your API key → Save.

---

## 🛠 How to Use
1. Select any **code snippet** on any webpage.
2. Wait for the **tooltip** to appear.
3. Read AI-generated explanation + examples instantly.
4. Click **Copy** to save explanation.

---

## ✅ Supported Languages
`JavaScript` | `Python` | `Java` | `C++` | `HTML` | `CSS` | `SQL` | `C`

---

## 📌 Key Files
- `content/contentScript.js` → Main logic for selection, API calls, and UI.
- `styles/tooltip.css` → Tooltip design + animations.
- `popup/popup.html` → Dashboard UI.
- `popup/popup.js` → Test snippet & settings link.
- `options/options.html` → API key storage.

---

## 🔮 Roadmap
- [ ] Save explanations to **Dev Notes Board** in popup.
- [ ] Multi-model support (Gemini + Hugging Face).
- [ ] User settings for theme and tooltip size.
- [ ] Offline fallback mode.

---

## 🛡 Security
- API key stored securely in **Chrome Storage**.
- Never hardcoded in source code.
- You control your own key.

---

## 💡 Perfect For
- Coding learners & beginners.
- Developers reading documentation.
- Anyone curious about unfamiliar code!

---

## 📜 License
MIT License © 2025 [Anish K]
