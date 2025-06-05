# ✅ Solutions: CSS Float Challenge

> ⚠️ Spoiler Alert! Only continue if you’ve attempted the challenge first.

---

## 🐱🐶 Goal 1 – Make Both Paragraphs Wrap Around the Image

To make the text wrap around the images, apply `float: left` to each image. This causes the text in the paragraph to flow beside the image:

```css
.cat img,
.dog img {
  float: left;
  margin-right: 10px;
}
```
This ensures each image stays to the left of its corresponding text and adds some spacing between the image and paragraph.

## 🐾 Goal 2 – Use Float to Position the Cat Div to the Left and Dog Div to the Right
Use float on the .cat and .dog divs to position them side by side:

```css
.cat {
  float: left;
}

.dog {
  float: right;
}
```
Tip: Make sure both .cat and .dog have widths less than 50% to avoid overflow.

## 📦 Goal 3 – Use clear to Make the Footer Go Below Both Divs
To make sure the footer appears below the floated .cat and .dog sections, add clear: both to the footer:

```css
footer {
  clear: both;
}
```
This forces the footer to clear any floats applied earlier.

## 🧠 Summary
#### ✅ float: left/right moves elements to the side and lets text/content flow around them.

#### ✅ clear: both prevents the next element from being placed beside floated elements.

#### ✅ Use margin to create spacing between floated content and surrounding text.