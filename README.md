# New Year Countdown

This is an illustration of using **HTML**, **CSS** and **JavaScript** to make a _simple website_. It follows from the digital clock project (**ProjectN001**). It counts down time to next year.

## Possible Use Cases

- Count down deadlines for projects and processes.
- Measure time from start of project to actual finish time.
- Aligning time to strategies (marketing promotion countdown, operation countdown, etc. )
- Personal Count downs to events (Birthdays, Anniversary, etc.)

## HTML

HTML provides structure to the website.

## CSS

CSS provides styling to the website. The following is examined:

- `::before`
  - creates a pseudo-element that is the first child of the selected element.
  - often used to add cosmetic content to an element with the `content` property.
  - similar usage as the `::after` pseudo-element.
  - more on [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/::before)
- **Note** `::before` used to create content is discouraged where accessibility by screen readers is required. 
  - The project just illustrates the use of this pseudo-element.

## JavaScript

The JavaScript provides interactivity in the website. The following are examined:

- Creating new `Date()` constructor. `new Date("2024-01-01T00:00:00Z").getTime()`
  - more on managing dates with formats [Udacity Blog](https://www.udacity.com/blog/2021/05/managing-dates-with-javascript-date-formats.html)
- `Math.floor()` method rounds a number down to the nearest integer.
- Reminder (`%`) operator returns the remainder when one operand is divided by another.
- Function declaration and Call back function

**ProjectN002**
