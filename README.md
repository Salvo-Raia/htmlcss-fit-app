![Static Badge](https://img.shields.io/badge/Boolean_Tech_Academy-001632?style=for-the-badge)

# 🎓 Exercise 05/50 - FitApp

Modifying an existing application by implementing CSS changes without altering its original HTML structure.

## 📌 Project Overview

| Property | Details |
|:--|:--|
| Repository | htmlcss-fit-app |
| Category | Boolean Tech Academy |
| Type | Exercise |
| Exercise | 05/50 |

## 🎯 Assignment

Today we'll explore an experience that almost every junior developer faces on their first day at work: modifying code written by someone else!

You've been hired by a company that asks you to make changes to its app. However, you'll have to implement these changes **without modifying the HTML!**

The list of requested modifications can be found in the `readme.md` file included in the provided project folder.

### 📋 Rules

- Download the provided project folder and immediately initialize a Git repository.
- As a first step, commit the original files exactly as they are.
- Immediately afterwards, link the `solutions.css` file in `index.html`. This will be the only modification you're allowed to make to the HTML file.
- Follow the instructions in the provided `readme.md` file and implement your solutions inside `solutions.css`.

### 🔎 Requested Changes

1. **🔥 Fire icon in the first stat card** - Add the 🔥 emoji above the number in the first statistics card (calories).
2. **🌟 Highlight the third stat card** - Apply a blue-purple gradient background and white text to the third statistics card (workout minutes).
3. **✨ Hover effect on stat cards** - Make every statistics card move up by 5px and increase its shadow on hover.
4. **📌 Highlight the second workout plan** - Add a 5px orange left border and a very light yellow background to the second workout plan (Strength and Endurance).
5. **🟢 Green borders for the first and last exercises** - Apply a green left border and a very light green background to the first and last exercises in the list.
6. **⚡ Lightning icons on even exercises** - Add the ⚡ emoji at the beginning of the names of even-numbered exercises (2nd and 4th).
7. **🎯 Input and select focus styles** - Give input and select fields a blue border and blue shadow when focused.
8. **🎯 Smooth focus transitions** - Add a smooth transition to the focus effect.
9. **🔘 Button improvements** - Make the "Save Goals" button move up by 2px on hover, change its background color, and add a blue shadow.
10. **📊 Progress bar percentage** - Display "65%" in white inside the progress bar, aligned to the right.
11. **🧭 Navigation hover effect** - Give navigation links a darker background and blue text on hover.
12. **🧭 Active navigation link** - Make the first navigation link always appear active, as if it were the current page.
13. **💭 Decorative quotation marks** - Add decorative quotation marks above the left side and below the right side of the quote, with reduced opacity.

### 💡 Suggestions & Notes

- Use selectors such as `:first-child`, `:nth-child()` and `:last-child`.
- Remember that `:hover` and `:focus` are pseudo-classes.
- When using the `::before` and `::after` pseudo-elements, don't forget the `content` property.
- To position content inside pseudo-elements, use `position: absolute` and `translate`.

### ⭐ Bonus

Try to make the changes smoother by exploring and using the CSS `transition` property.

## 🛠️ Technologies

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

## 💡 What I Learned

- Working with an existing codebase without modifying its original HTML structure.
- Using CSS pseudo-classes such as `:hover`, `:focus`, `:first-child`, `:nth-child()` and `:last-child`.
- Creating decorative content with the `::before` and `::after` pseudo-elements.
- Applying gradients, shadows, borders and background colors.
- Using CSS transitions to create smoother interactions.

## ©️ Credits

Exercise assigned by **Boolean Tech Academy** as part of the Web Development course - Class 152 - Year 2025-2026
