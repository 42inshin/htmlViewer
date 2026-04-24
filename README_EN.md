<div align="center">
  <p align="right">
    <a href="./README.md">한국어</a> | <b>English</b>
  </p>
  <br />
  <img src="assets/logo.svg" width="100" alt="HTML Viewer Logo" />

  <h1>HTML & Markdown Viewer</h1>
  <p>Instantly view GitHub HTML presentations and Markdown documents by entering the URL.</p>

  <br />
  <a href="https://42inshin.github.io/htmlViewer/">
    <img src="assets/launch-button.svg" width="240" alt="Launch Viewer" />
  </a>
  <br />
  <br />
</div>

## 🛠 Key Features

- **URL Conversion & Rendering**:
  - **HTML**: Converts GitHub source URLs into executable links for display via [Raw.Githack](https://raw.githack.com/).
  - **Markdown**: Renders `.md` files with the official GitHub Markdown theme.
- **URL Parameter Sharing**: Supports shareable links that open specific items instantly by appending `?url=FULL_URL`.
- **Theme Toggle**: Supports Light/Dark mode (state persists in local storage).
- **Recent History**: Manage a list of viewed items (supports multi-language filenames, URL copying, and original repository links).
- **Content-Focused Viewer**: Minimalist UI designed to keep the focus on your content.

## 📖 How to Use

1. Copy the URL of an HTML or Markdown file from a GitHub repository.
2. Paste the URL into the input field and click **[Open]**.
3. Navigation & Controls:
   - **ESC**: Return to the home screen.
   - **Top Left Corner**: Home/Refresh/Share buttons (revealed on hover/touch).
   - **Language Toggle**: Toggle between KO/EN in the top right.
   - **Theme Toggle**: Sun/Moon icon in the top right.

---
**Tech Stack**: Tailwind CSS, Marked.js, GitHub Markdown CSS, Lucide Icons<br>
**Powered by**: [Raw.Githack](https://raw.githack.com/)
