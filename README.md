# 🎃 Spooky Login Form 👻

An interactive, responsive authentication page featuring dynamic reactive video feedback based on user login attempts. Built with pure HTML5, modern CSS3, and Vanilla JavaScript.

---

## ✨ Features

- 🎬 **Dynamic Video Feedback**: Visual state changes in real-time depending on the authentication status:
  - ⏳ **Idle State (`1026.mp4`)**: Ambient waiting animation on page load.
  - ❌ **First Failed Attempt (`wrong.mp4`)**: Initial spooky reaction to invalid credentials.
  - ⚠️ **Repeated Failures (`againwrong.mp4`)**: Escalated reaction when multiple wrong attempts occur.
  - ✅ **Successful Login (`correct.mp4`)**: Rewarding success reaction upon correct credentials.
- 📱 **Fully Responsive**: Adapts seamlessly from desktop split-screen to mobile-stacked layout.
- ⚡ **Zero Dependencies**: Lightweight, fast, and runs directly in any modern browser without build tools or external libraries.
- 🔄 **State Reset**: Interactive "Try Again" functionality to clear inputs, reset failure counts, and restore the idle state.

---

## 🔑 Demo Credentials

To test the different states:

| Field | Demo Value |
| :--- | :--- |
| **Email / Username** | `user1` |
| **Password** | `1111` |

> 💡 *Enter any other combination to trigger the spooky failure reactions!*

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/pabitralenka07/Spooky-login.git
cd Spooky-login
```

### 2. Run the project
Simply open `index.html` in your favorite web browser:
- **macOS**: `open index.html`
- **Linux**: `xdg-open index.html`
- **Windows**: `start index.html`

*Or use a local server like VS Code's **Live Server** extension for the best experience.*

---

## 📂 Project Structure

```text
Spooky-login/
├── 1026.mp4          # Default / idle ambient video loop
├── correct.mp4       # Success animation video
├── wrong.mp4         # First failure reaction video
├── againwrong.mp4    # Repeated failure reaction video
├── index.html        # Main markup, styling, and reactive logic
├── .gitignore        # Ignored system files (.DS_Store, etc.)
└── README.md         # Project documentation
```

---

## 🛠️ Built With

- **HTML5** — Semantic layout & HTML5 `<video>` media API
- **CSS3** — Flexbox, smooth transitions, keyframe animations & linear gradients
- **JavaScript (ES6+)** — Asynchronous state management, dynamic DOM updates, and event listeners

---

## 👤 Author

**Pabitra Lenka**
- GitHub: [@pabitralenka07](https://github.com/pabitralenka07)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
