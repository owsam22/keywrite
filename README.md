# ✨ KeyWrite

[![GitHub release](https://img.shields.io/github/v/release/owsam22/keywrite?color=brightgreen&label=Download&style=for-the-badge)](https://github.com/owsam22/keywrite/releases)  


KeyWrite is a lightweight desktop tool that instantly **fixes grammar and rewrites text naturally** using AI.  
Select text anywhere → press a hotkey → and your text is corrected in place or copied to clipboard.  

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbWd5Z21wM3U0bWF2ZXFpZThzY3VrdXU4N3dsY3RzM3liYzBxNTFjeCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/demo.gif" width="700" alt="KeyWrite Demo"/>
</p>

---

## 🚀 Features
- Correct grammar and rewrite text with AI.
- Two hotkeys:
  - `Ctrl+Alt+V` → Correct and Replace selected text.  
  - `Ctrl+Alt+C` → Correct and Copy to clipboard.  
- Works in any app (Notepad, Word, Browser, etc.).
- Simple API key setup — paste your key once and enjoy.

---

## 📦 Installation Options

### 🔹 Option 1: Use the Ready App (Recommended)

1. [⬇️ Download KeyWrite (ZIP)](https://github.com/user-attachments/files/22233100/app.zip)  
2. Extract the `app.zip` file anywhere on your computer.  
3. Open the folder and double-click **`KeyWriteApp.exe`**.  
4. Enter your [OpenRouter API Key](https://openrouter.ai/keys) when asked.  
5. Press **Start** → use hotkeys instantly!  

✅ That’s it — no coding or setup required.  

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYTh3ZG8zaHN5M3N4dXNxN3FvZW9mcmNwYXcyd2dqNm9xeHQzaTd2ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/demo-install.gif" width="700" alt="KeyWrite Install Demo"/>
</p>

---

### 🔹 Option 2: Run from Source Code

If you prefer running in **VS Code** or editing the project:  

1. Clone this repo:
   ```bash
   git clone https://github.com/owsam22/keywrite.git
   cd keywrite


2. Install dependencies:

   ```bash
   pip install keyboard pyperclip requests

   ```

3. Create a `.env` file in the project folder:

   ```
   OPENROUTER_KEY=your_api_key_here
   ```

4. Run the script:

   ```bash
   python keywrite.py
   ```

Now use the same hotkeys:

* `Ctrl+Alt+V` → replace selected text
* `Ctrl+Alt+C` → copy corrected text

---

## ⚙️ Requirements

* Windows 10/11 (for the `.exe` build)
* Python 3.9+ (if running from source)
* [OpenRouter API Key](https://openrouter.ai/keys)
* Internet connection

---

## 📸 Demo Screenshots

<p align="center">
  <img src="assets/ui.png" width="600" alt="KeyWrite UI"/>
</p>

---

## 🙌 Credits

Built with ❤️ by [Sam](https://github.com/owsam22).
Powered by [OpenRouter](https://openrouter.ai/).

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://github.com/owsam22"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/samarpan22/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>



