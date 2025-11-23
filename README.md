# daily-quote
A simple Quote of the Day web app that fetches inspiring quotes from an API and displays them dynamically. Users can load a new quote instantly with a single click. Clean UI, lightweight code, and easy to customize.

---

## 🚀 Features

* Fetches a new quote dynamically from an API
* Smooth and clean UI
* Responsive design
* Beginner-friendly JavaScript code
* Easy to customize

---

## 📌 Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (Fetch API)**

---

## 🔧 How It Works

The app uses the Quotable API:

```
https://api.quotable.io/random
```

JavaScript fetches the quote, extracts the content and author, and updates the HTML:

```js
quote.innerHTML = data.content;
author.innerHTML = data.author;
```

---

## ▶️ How to Run

1. Download or clone the project
2. Open `index.html` in any browser
3. Click **New Quote** to load a fresh quote

---

## 📂 Project Structure

```
/project-folder
│── index.html
│── style.css
```

---

## 📜 License

This project is free to use for learning and personal development.

---


