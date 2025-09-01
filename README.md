![Stars](https://img.shields.io/github/stars/happyman09/search-anywhere?style=flat-square)
![Issues](https://img.shields.io/github/issues/happyman09/search-anywhere?style=flat-square)
![Last Commit](https://img.shields.io/github/last-commit/happyman09/search-anywhere?style=flat-square)
![License](https://img.shields.io/github/license/happyman09/auto-wallpaper-themer?style=flat-square)
![Downloads](https://img.shields.io/github/downloads/happyman09/search-anywhere/latest/total?style=flat-square)

# 🔥 Hotkey Clipboard Search Tool

**Search Google & YouTube instantly using hotkeys!**  

This lightweight Windows tool lets you search **Google** or **YouTube** directly from your clipboard with global hotkeys. Hotkeys can be toggled ON/OFF. 

---

## ✨ Features

- 🔍 **Google Search** – Ctrl+Alt+G  
- ▶️ **YouTube Search** – Ctrl+Alt+Y  
- ⚡ **Toggle Hotkeys** – Ctrl+Alt+T (ON/OFF Background)  
- 🛑 **Exit Script** – Esc  
- 🖥️ **Runs silently in background**  
- 🚫 **Suppress keypresses** – prevents letters from being typed while using hotkeys  

---
# 📦 Installation & Usage

 - **Download the `search_anywhere!.exe` file**

 - **Hit Win+R and type:** 
 ```
Shell:startup
 ```

 - **Copy .exe to Shell:startup → starts automatically on Windows login**

## - ⚠️ Remember to `Copy` or hit `Ctrl+C` first before using the Hotkey (Ctrl+Alt+G or Y)

---


# ⚠️ Setup Requirements
- Python
**Make sure you have [Python](https://www.python.org/downloads/) installed on your system.**
  
- Environment Variables  
**Ensure Python is added to your `PATH` so you can run it from any directory.**
  
- pip:
**Make sure pip is installed to manage dependencies. You can check by running:**
```
pip --version
```
**If it’s missing, follow the instructions here:**
```
Install pip
```
## 📦 Install dependencies:

Install required Python packages:
```
pip install keyboard pyperclip
```
---

## Run the script:

Double Click on the `search_anywhere!.exe` to run

**⚠️ Note** that copying the `.exe` to `shell:startup` will start the script in the background next time you log in,
**You dont have to click on the `.exe` everytime you log in!**

---

## 💻 Hotkeys
Hotkey	Action

- `Ctrl+Alt+G`	Google search clipboard text
- `Ctrl+Alt+Y`	YouTube search clipboard text
- `Ctrl+Alt+T`	Toggle hotkeys ON/OFF
- `Esc`	Exit the script completely
  
---

## 📝 Notes

- **Works on Windows only (as of now)**
- **Cross-platform toast notifications via plyer**
- **No terminal window will appear; fully silent in background**
- **Hotkeys use Ctrl+Alt to reduce clashes, even during games or any software's hotkeys**
- **In case of clashes while in another app, you can simply hit `Ctrl+Alt+T` to turn off**


## 🤝 Contributions

Want to add Linux or Mac support?

Have ideas for additional search engines or custom hotkeys?

`Open a PR or issue — contributions welcome!`

## 📜 License

MIT License


---
