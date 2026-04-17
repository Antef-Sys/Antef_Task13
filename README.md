# 🔢 Even or Odd Number Checker

This is a simple JavaScript project that checks whether a given number is **even** or **odd**.
https://antef-sys.github.io/Antef_Task13/
---

## 🚀 Project Overview

The program uses a basic conditional statement to determine if a number is divisible by 2.

* If the number is divisible by 2 → **Even**
* Otherwise → **Odd**

---

## 📁 Project Structure

```id="r1"
project-folder/
│── index.html
│── script.js
```

---

## 💻 Code Explanation

### HTML (`index.html`)

* Basic structure of the webpage
* Connects the JavaScript file using the `<script>` tag

---

### JavaScript (`script.js`)

```js id="r2"
const a = 6;

if (a % 2 == 0) {
    console.log("The number", a, "is even.");
} else {
    console.log("The number", a, "is odd.");
}
```

### 🔍 Logic Used

* `%` (modulus operator) returns the remainder
* If `a % 2 == 0`, the number is divisible by 2 → **Even**
* Otherwise → **Odd**

---

## ▶️ How to Run the Project

1. Create two files:

   * `index.html`
   * `script.js`

2. Copy the HTML code into `index.html`

3. Copy the JavaScript code into `script.js`

4. Open `index.html` in any browser

5. Open Developer Console:

   * Press `F12` or `Ctrl + Shift + I`
   * Go to **Console tab**

6. Output will be displayed like:

```id="r3"
The number 6 is even.
```

---

## ✨ Features

* Beginner-friendly project
* Simple logic using conditionals
* Easy to modify input value
* No external libraries required

---

## 🔧 Future Improvements

* Take input from user (prompt or form)
* Display result on webpage instead of console
* Check multiple numbers
* Add styling using CSS

---

## 📚 Learning Outcome

By completing this project, you will learn:

* How to use conditional statements (`if-else`)
* How modulus operator works
* Basic JavaScript syntax
* How to run JavaScript in browser console

---

## 📄 License

This project is free to use for learning and practice.
