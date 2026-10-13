# Project 02 — CSS & Visual Presentation

**Designing Modern Interfaces**

**Course:** Cybersecurity — Web Application Security  
**Project:** 02 — CSS & Visual Presentation  
**Version:** 1.0

## 📖 About the Project

This project is part of a hands-on **Cybersecurity Course focused on Web Application Security**, running from September 26 to November 6.

Following the HTML fundamentals introduced in Project 01, this project focuses on CSS (Cascading Style Sheets) and the visual presentation of web pages. It explores how layouts, positioning, shapes, colors, and animations transform basic HTML documents into structured and visually engaging interfaces.

Through five core exercises and two bonus exercises, students practice building flexible layouts, controlling element positioning, creating geometric shapes, working with color models and transparency, understanding the CSS box model, and implementing animations and interactive transitions.

## 🎯 Learning Objectives

- Understand how CSS styles and visually organizes HTML elements.
- Build flexible layouts using Flexbox.
- Control element positioning and stacking order.
- Create geometric shapes using pure CSS.
- Work with different color models and alpha transparency.
- Understand the CSS box model and calculate element dimensions.
- Apply consistent sizing using `box-sizing`.
- Develop problem-solving skills through independent practice and peer evaluation.

## 📂 Project Structure

```text
Project-02/
├── ex00/
│   ├── index.html
│   └── style.css
├── ex01/
│   ├── index.html
│   └── style.css
├── ex02/
│   ├── index.html
│   └── style.css
├── ex03/
│   ├── index.html
│   └── style.css
└── ex04/
    ├── index.html
    └── style.css
```

## 📝 Exercises

### Exercise 00 — Flexbox Layout

**Directory:** `ex00/`

Create a navigation bar and a responsive card grid using CSS Flexbox.

**Key concepts:**
- `display: flex`
- `justify-content`
- `align-items`
- `flex-direction`
- `flex-wrap`
- `gap`
- Main axis and cross axis

**Goal:** Understand one-dimensional layouts and arrange elements without using floats or HTML layout tables.

### Exercise 01 — CSS Positioning

**Directory:** `ex01/`

Build a page with a fixed navigation bar, a card containing an absolutely positioned notification badge, and a back-to-top button fixed to the viewport.

**Key concepts:**
- `position: static`
- `position: relative`
- `position: absolute`
- `position: fixed`
- `z-index`
- Positioned ancestors and containing blocks

**Goal:** Control where elements appear on a page and understand how positioning contexts affect their placement.

### Exercise 02 — CSS Shapes

**Directory:** `ex02/`

Create five geometric shapes using HTML elements and pure CSS, without images or SVG files.

**Required shapes:**
1. Square
2. Rectangle
3. Perfect circle
4. Capsule or pill
5. Triangle using CSS borders

**Key concepts:**
- `width` and `height`
- `border`
- `border-radius`
- CSS borders and geometric shapes

**Goal:** Understand how basic CSS properties can be combined to create visual elements.

### Exercise 03 — Colors & Opacity

**Directory:** `ex03/`

Build a color palette demonstrating different CSS color formats and compare two methods of applying transparency.

**Key concepts:**
- Named colors
- HEX color codes
- `rgb()`
- `rgba()`
- `opacity`
- Alpha transparency

**Goal:** Understand color representation and the difference between applying opacity to an entire element and applying transparency only to its background color.

### Exercise 04 — The CSS Box Model

**Directory:** `ex04/`

Create two comparison boxes demonstrating how `content-box` and `border-box` calculate element dimensions.

**Key concepts:**
- Content
- Padding
- Border
- Margin
- `box-sizing: content-box`
- `box-sizing: border-box`
- Universal box-sizing reset

**Goal:** Understand how the box model affects element dimensions, spacing, and layout consistency.


## 🛠️ Technologies & Tools

- **HTML5** — Web page structure
- **CSS3** — Styling, layouts, shapes, and animations
- **Web Browser** — Viewing and testing the exercises
- **Browser Developer Tools** — Inspecting elements and debugging layouts
- **Git & GitHub** — Version control and project submission

JavaScript is not required for these exercises. All specified visual effects should be implemented using CSS.

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url> <Folder-Name>
   ```

2. Navigate to the project directory:

   ```bash
   cd <Folder-Name>
   ```

3. Open an exercise's `index.html` file in your preferred web browser. For example:

   ```bash
   firefox ex00/index.html
   ```

4. Repeat the process for the other exercises and directories.

Each HTML file should link to its corresponding `style.css` stylesheet.

## 📚 References

- [MDN Web Docs — CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [MDN — CSS Flexible Box Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout)
- [MDN — CSS Positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
- [MDN — CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_box_model)
- [MDN — CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_animations)
- [Git Documentation](https://git-scm.com/doc)

## 🎓 Learning Philosophy

The goal of this project is not simply to make web pages look attractive, but to understand the mechanics behind their visual structure. By experimenting with layouts, positioning, colors, dimensions, and motion, students develop a stronger understanding of how browsers render and display web interfaces.

As part of a broader cybersecurity learning journey, understanding the structure and presentation of web interfaces complements the foundational knowledge needed to study web applications and their behavior.

**Understand the layout. Master the styling. Bring interfaces to life.**

---