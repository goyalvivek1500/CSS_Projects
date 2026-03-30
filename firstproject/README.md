# 🇯🇵 Japan Flag (CSS Project)

This is a simple CSS project that recreates the **flag of Japan** using HTML and CSS. The design consists of a white rectangular background with a centered red circle, representing the sun.

---

## 📌 Project Overview

The Japanese flag, also known as the **Nisshoki (日章旗)** or **Hinomaru (日の丸)**, symbolizes the sun. In this project:

* The **container** represents the white background.
* The **red circle** represents the sun at the center.

---

## 🛠️ Technologies Used

* HTML
* CSS

---

## 🎨 CSS Explanation

### 🔹 Reset Styling

```css
* {
    padding: 0px;
    margin: 0px;
}
```

* Removes default browser spacing.

---

### 🔹 Container (Flag Background)

```css
#container {
    height: 200px;
    width: 300px;
    position: relative;
    top: 300px;
    left: 400px;
    border: 2px solid black;
    box-shadow: 10px 10px 10px rgb(238, 137, 130);
}
```

* Creates the flag base.
* White background by default.
* Positioned on the page using `top` and `left`.
* Adds border and shadow for styling.

---

### 🔹 Red Circle (Sun)

```css
.box {
    background-color: red;
    height: 100px;
    width: 100px;
    position: absolute;
    top: 50px;
    left: 100px;
    border-radius: 50%;
}
```

* Creates a perfect circle using `border-radius: 50%`.
* Positioned in the center of the container.
* Represents the sun.

---

## 📷 Output

A rectangular white box with a centered red circle — just like the Japanese flag.

---

## 🚀 How to Run

1. Create an `index.html` file.
2. Add a container and a div inside it:

   ```html
   <div id="container">
       <div class="box"></div>
   </div>
   ```
3. Link your CSS file or paste the CSS inside `<style>` tags.
4. Open the file in a browser.

---

## 💡 Improvements

* Make it responsive using `%` or `flexbox`
* Center the flag using `margin: auto`
* Add animation (e.g., waving flag effect)

---

## 📚 Learning Outcome

* CSS positioning (`relative` & `absolute`)
* Box model
* Centering elements
* Creating shapes with CSS

---

## ⭐ Author

Created as a beginner-friendly CSS project to practice layout and positioning.

---
