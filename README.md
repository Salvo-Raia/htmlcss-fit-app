![Static Badge](https://img.shields.io/badge/Boolean_Tech_Academy-1565C0?style=for-the-badge)

# Exercise 05/50: FitApp

Modifying an existing application by implementing CSS changes without altering its original HTML structure.

## Project overview

| Repository | Project | Category | Main Focus | Exercise |
|:--|:--|:--|:--|:--|
| htmlcss-fit-app | FitApp | Exercise | CSS selectors & Pseudo-classes | 05/50 |

## Assignment

Today we'll explore an experience that almost every junior developer faces on their first day at work: modifying code written by someone else!

You've been hired by a company that asks you to make changes to its app. However, you'll have to implement these changes **without modifying the HTML!**

The list of requested modifications can be found in the `readme.md` file included in the provided project folder.

Download the provided project folder and immediately initialize a Git repository. As a first step, commit the original files exactly as they are.

Immediately afterwards, link the `solutions.css` file in `index.html`. This will be the only modification you're allowed to make to the HTML file.

Follow the instructions in the provided `readme.md` file and implement your solutions inside `solutions.css`.

#### Instructions

- **Fire icon in the first stat card** - Add the "🔥" emoji above the number in the first statistics card (calories).
- **Highlight the third stat card** - Apply a blue-purple gradient background and white text to the third statistics card (workout minutes).
- **Hover effect on stat cards** - Make every statistics card move up by 5px and increase its shadow on hover.
- **Highlight the second workout plan** - Add a 5px orange left border and a very light yellow background to the second workout plan (Strength and Endurance).
- **Green borders for the first and last exercises** - Apply a green left border and a very light green background to the first and last exercises in the list.
- **Lightning icons on even exercises** - Add the "⚡" emoji at the beginning of the names of even-numbered exercises (2nd and 4th).
- **Input and select focus styles** - Give input and select fields a blue border and blue shadow when focused.
- **Smooth focus transitions** - Add a smooth transition to the focus effect.
- **Button improvements** - Make the "Save Goals" button move up by 2px on hover, change its background color, and add a blue shadow.
- **Progress bar percentage** - Display "65%" in white inside the progress bar, aligned to the right.
- **Navigation hover effect** - Give navigation links a darker background and blue text on hover.
- **Active navigation link** - Make the first navigation link always appear active, as if it were the current page.
- **Decorative quotation marks** - Add decorative quotation marks above the left side and below the right side of the quote, with reduced opacity.

#### Bonus challenge

Try to make the changes smoother by exploring and using the CSS `transition` property.

##### Notes

- Use selectors such as `:first-child`, `:nth-child()` and `:last-child`.
- Remember that `:hover` and `:focus` are pseudo-classes.
- When using the `::before` and `::after` pseudo-elements, don't forget the `content` property.
- To position content inside pseudo-elements, use `position: absolute` and `translate`.

## Technologies

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) 
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

## What I learned

- Working with an existing codebase without modifying its original HTML structure.
- Using CSS pseudo-classes such as `:hover`, `:focus`, `:first-child`, `:nth-child()` and `:last-child`.
- Creating decorative content with the `::before` and `::after` pseudo-elements.
- Applying gradients, shadows, borders and background colors.
- Using CSS transitions to create smoother interactions.

## Credits

Exercise assigned by **Boolean Tech Academy** as part of the Web Development course (Class 152, A.Y. 2025-2026).
