# 🧩 Challenge: CSS `display` Property

## 📄 Description

This is a hands-on exercise focused on understanding the `display` property in CSS. The goal is to modify **only the `display` property** to align three colored squares (`<p>` elements) in different ways, according to the specified objectives.

## 🎯 Challenge Goals

1. **Align all three squares horizontally** (as shown in `goal1.png`) by changing only the `display` property in the CSS.
2. **Align all three squares vertically** (as shown in `goal2.png`) again by changing only the `display` property.

## 🧪 Instructions

1. Open the HTML file in a browser.
2. Inspect and edit the CSS, modifying **only** the `display` property of the `.red`, `.green`, and `.blue` classes.
3. Achieve both layout goals without changing the HTML or adding extra CSS rules.

## 🛠️ Technologies Used

- HTML5  
- CSS3

## 📝 Notes

- This exercise is meant to help you practice how different `display` values (`block`, `inline`, `inline-block`, `flex`, etc.) affect layout behavior.
- Do **not** modify the HTML structure.
- Focus **only** on the `display` property for each class.

## ✅ Solutions (Spoiler Alert!)

> ⚠️ Only check this section after attempting the challenge yourself!

### Goal 1 – Horizontal Alignment

To align the squares horizontally, set all three classes to use `inline-block` or wrap them in a flex container (if allowed):

```css
    .red {
      display: inline-block;
      width: 200px;
      height: 200px;
      background-color: red;
    }

    .green {
      display: inline-block;
      width: 200px;
      height: 200px;
      background-color: green;
    }

    .blue {
      display: inline-block;
      width: 200px;
      height: 200px;
      background-color: blue;
    }
```
### Goal 2 – Vertical Alignment
To align the squares vertically (stacked on top of each other), set all elements to `block`:
```css
    .red {
      display: block;
      width: 200px;
      height: 200px;
      background-color: red;
    }

    .green {
      display: block;
      width: 200px;
      height: 200px;
      background-color: green;
    }

    .blue {
      display: block;
      width: 200px;
      height: 200px;
      background-color: blue;
    }
```

