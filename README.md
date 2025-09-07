
<h1 align="center">✨ KeyWrite ✨</h1>
<p align="center">
  <em>Correct, rewrite, and polish text anywhere with a simple hotkey</em>
</p>

---

## 🎥 Demo
<p align="center">
  <!-- Replace with your gif/mp4 later -->
  <img src="demo.gif" alt="KeyWrite Demo" width="600">
</p>

---

## 🚀 Features
- 🔑 **Ctrl+Alt+V** → Correct & replace selected text  
- 📋 **Ctrl+Alt+C** → Correct & copy to clipboard  
- 🌍 Works system-wide in any app (browser, docs, editors, chat)  
- ⚡ Uses [OpenRouter](https://openrouter.ai) models (DeepSeek, GPT, etc.)  
- 🎯 Lightweight, runs in the background, no clutter  



## 🛠️ Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/keywrite.git
   cd keywrite
```

2. Install dependencies:

   ```bash
   pip install keyboard pyperclip requests
   ```

3. Add your API key as an environment variable:

   **Windows (PowerShell):**

   ```powershell
   setx OPENROUTER_KEY "your_api_key_here"
   ```

   **Linux / macOS:**

   ```bash
   export OPENROUTER_KEY="your_api_key_here"
   ```

---

## ▶️ Usage

Run:

```bash
python keywrite.py
```

You’ll see:

```
Running... Press ctrl+alt+v to replace, ctrl+alt+c to copy. ESC to exit.
```

Then simply highlight text anywhere and hit a hotkey 🚀

---

## 📦 Build as EXE (optional)

If you want a portable `.exe`:

```bash
pip install pyinstaller
pyinstaller --onefile keywrite.py
```

The `.exe` will be in the `dist` folder.

---

## 🌟 Roadmap

* [ ] Customizable hotkeys
* [ ] Dark/Light tray icon
* [ ] Multi-language support
* [ ] Offline correction (future idea)

---

## 📬 Connect with Me

<p align="center">
  <a href="https://github.com/yourusername"><img src="https://img.shields.io/badge/GitHub-000?logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/yourprofile"><img src="https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white" /></a>
  <a href="https://twitter.com/yourhandle"><img src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white" /></a>
</p>

---

## 📜 License

MIT License © 2025 \[Samarpan]




