# Color_Generator

# 🎨 Simple Color Generator

A lightweight, interactive web application that generates random hexadecimal colors and applies them to the page background in real-time. Built with pure HTML, CSS, and Vanilla JavaScript.

## 🚀 Features

* **Random Color Generation:** Creates unique hex codes instantly.
* **Real-time Preview:** Changes the entire page background color on the fly.
* **Dynamic UI:** Displays the specific hex code for easy copying.
* **Responsive Design:** Clean, centered card layout that works on all screen sizes.

## 🛠️ Technologies Used

* **HTML5:** Structure and content.
* **CSS3:** Styling, Flexbox layout, and smooth transitions.
* **JavaScript (ES6):** Logic for randomizing hex values and DOM manipulation.

## 📖 How It Works

A hexadecimal color consists of 6 characters from the string `0123456789ABCDEF`. The application uses a `for` loop and `Math.random()` to pick six characters and combine them with a `#` prefix.

```javascript
for (var i = 0; i < 6; i++) {
    var idx = Math.floor(Math.random() * 16);
    warna += hexa[idx];
}

```

## 📸 Preview

* **Initial State:** Clean white background with a central UI card.
* **Action:** Click the "Ubah Warna" button.
* **Result:** Background transitions smoothly to a new color and the hex code is updated.

## ⚙️ Installation

1. Clone this repository:
```bash
git clone https://github.com/username/color-generator.git

```


2. Open `index.html` in your favorite browser.
