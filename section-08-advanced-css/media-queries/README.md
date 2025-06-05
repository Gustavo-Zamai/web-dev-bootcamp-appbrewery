# 🧩 Challenge: Responsive Background with Media Queries

## 📄 Description

This is a beginner-friendly CSS exercise focused on understanding **media queries** and how to apply different styles based on screen size. The goal of this activity is to change the background color of the page depending on the width of the user's device.

## 🎯 Challenge Goals

Use CSS media queries to apply the following background colors based on screen width:

| Device Type       | Screen Width Range      | Background Color |
|-------------------|-------------------------|------------------|
| 📱 Mobile          | 319px — 480px           | `lightsalmon`    |
| 📱 Tablets/iPads   | 481px — 1200px          | `powderblue`     |
| 💻 Laptops         | 1201px — 1600px         | `limegreen`      |
| 🖥️ Desktops        | 1601px and up           | `seagreen`       |

## 🧪 Instructions

1. Open the HTML file in your browser.
2. Resize the browser window or use developer tools to simulate different screen sizes.
3. Observe how the background color of the page changes based on the width.

## 🛠️ Technologies Used

- HTML5  
- CSS3 (`@media` queries)

## 💡 Learning Objectives

- Understand how to use `@media` queries in CSS.
- Learn how to apply responsive design techniques using screen width breakpoints.
- Practice the **mobile-first approach** by starting with a base style and overriding it as the screen size increases.

## ✅ Example Media Query Structure

```css
@media (max-width: 480px) {
  body {
    background-color: lightsalmon;
  }
}
```

## 📝 Notes
The default background color is aquamarine — this acts as the fallback or "base" style.

Make sure to test on real devices or emulators for a more accurate result.

This exercise is a foundation for more advanced responsive design techniques.