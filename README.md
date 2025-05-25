# 🎨 Color Changer

A simple web application that allows users to dynamically change the background color of the page with the click of a button. This project demonstrates the use of **HTML**, **CSS**, and **JavaScript** to manipulate the DOM and create interactive web features.

## 🌟 Features

- Change the background color to a random color with a single click
- Display the current color code on screen
- Smooth UI with responsive design
- Lightweight and beginner-friendly

## 📁 Project Structure


### `index.html`

This file contains the structure of the web page. It includes:

- A heading
- A button to trigger the color change
- A text span to show the current color code

### `style.css`

This file provides styling for the project:

- Centered layout using Flexbox
- Styling for the button and color code display
- Smooth transitions for background color changes

### `script.js`

Handles the logic for:

- Generating random color codes (hex format)
- Applying the new color to the page background
- Updating the displayed color code

---

## 🚀 Getting Started

Follow the steps below to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/himanshukumar-xp/color-changer.git
cd color-changer
```
```
Code Snippet
function getRandomColor() {
  const hex = '0123456789ABCDEF';
  let color = '#';
  for (let i = 0; i < 6; i++) {
    color += hex[Math.floor(Math.random() * 16)];
  }
  return color;
}
```
Author : Himanshu Kumar

