# Text Diff Viewer

A lightweight, browser-based text comparison tool built using **jsdiff**.  
It allows you to compare two pieces of text by **characters, words, lines, or patches**, with instant visual feedback and optional file upload support — all on the client side.

---

## 🚀 Features

- 🔤 Character-level diff
- 🧩 Word-level diff
- 📄 Line-level diff
- 🧵 Patch (unified diff) view
- 📂 Upload `.txt` files for comparison
- ⚡ Live updates as you type or upload
- 🌐 Runs entirely in the browser (no backend required)

---

## 🛠️ Built With

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **[jsdiff](https://github.com/kpdecker/jsdiff)**

---

## 📸 Preview

Type or paste text into the two input boxes, or upload files, and instantly see what changed on the right.

> Added text is highlighted  
> Removed text is struck through  

---

## 📁 Project Structure

```text
text-diff-viewer/
├── index.html
├── style.css
├── diff.js
├── LICENSE
└── README.md
````

> `diff.js` is provided by the jsdiff library.

---

## 🧑‍💻 Usage

### Option 1: Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/Abhrankan-Chakrabarti/text-diff-viewer.git
   ```
2. Open `index.html` in your browser.

That’s it — no build steps, no dependencies.

---

### Option 2: Use file upload

* Click **Load File A** to load the first text file
* Click **Load File B** to load the second text file
* The diff updates automatically

Supported formats include:

* `.txt`
* `.md`
* `.js`
* `.py`
* `.json`
* `.html`
* `.css`
* `.c`
* `.cpp`
* `.java`
* `.xml`
* `.yaml`
* `.yml`
* `.asc`

Any text-based file supported by the browser can be compared.

---

## ⚙️ Diff Modes Explained

| Mode  | Description                                   |
| ----- | --------------------------------------------- |
| Chars | Highlights differences character by character |
| Words | Compares text word by word                    |
| Lines | Compares text line by line                    |
| Patch | Shows a unified diff similar to `git diff`    |

---

## 🌐 Browser Compatibility

Works in all modern browsers:

* Chrome
* Firefox
* Edge
* Brave

(No special permissions required)

---

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements

* [jsdiff](https://github.com/kpdecker/jsdiff) by Kevin Decker

---

## ✍️ Author

**Abhrankan Chakrabarti**
GitHub: [@Abhrankan-Chakrabarti](https://github.com/Abhrankan-Chakrabarti)

---

## ⭐ Contributing

Pull requests are welcome.
If you have ideas for improvements (drag & drop, syntax highlighting, dark mode), feel free to open an issue or PR.

---

## 📌 Future Enhancements (Ideas)

* Drag & drop file support
* Syntax highlighting for code diffs
* Dark mode
* Support for more file types
* Side-by-side diff view

---

If you find this useful, consider giving the repo a ⭐

