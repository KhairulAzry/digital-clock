# 🕒 Digital Clock

A simple and modern Digital Clock web app built with **HTML**, **CSS**, and **JavaScript**.  
Includes features to **toggle fullscreen mode and prevent the screen from sleeping** while the clock is running.

## ✨ Features

- Real-time digital clock display (HH:MM:SS)
- Toggle **Fullscreen mode and Stay Awake** (Prevents screen from sleeping using the Wake Lock API)
- Clean and responsive UI

## 🚀 Live Preview

You can try it [here](https://www.khairulazry.com/digital-clock/)

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- Wake Lock API (Experimental – supported in modern browsers)

## 📂 Project Structure

```
digital-clock/
├── index.html
├── style.css
├── LICENSE
└── README.md
```

## 🔧 How to Use

1. Clone this repository or download the files.
2. Open `index.html` in any modern web browser.
3. Click the **"Enter Fullscreen & Stay Awake"** button to enter fullscreen mode and prevent your screen from going to sleep.
4. Click the **"Exit Fullscreen & Release Wake Lock"** button to exit fullscreen mode and let your screen going to sleep after certain period of time.

## 📲 Compatibility

- Compatible with all modern browsers (Chrome, Firefox, Edge, Safari)
- Wake Lock API may not be available in all browsers or requires HTTPS

## 🔒 Permissions

The **Stay Awake** feature uses the **Wake Lock API**, which may:
- Require HTTPS connection
- Prompt for permissions depending on the browser

## 📌 Notes

- Best used on devices that support fullscreen and wake lock.
- Ideal for kiosk screens, desktops, or phones while charging.

## 📜 License

This project is open source and available under the [MIT License](LICENSE).