# First Assignment: Personal Portfolio Website

[![Portfolio Preview](https://media.istockphoto.com/id/1333205574/vector/a-portfolio-folder-with-memos-and-bookmarks-office-paperwork-routine.jpg?s=1024x1024&w=is&k=20&c=tN_YK81GoLqdOJ89UeFA9LTtZM6EDMS59UPshgGQ54Q=)](https://stephanie-ramos.github.io/CodingTemple-2Module-PortfolioAssignment/)

**🌐 Live Website:** [View My Personal Portfolio](https://stephanie-ramos.github.io/CodingTemple-2Module-PortfolioAssignment/)

## Project Description

This project is a **personal portfolio landing page** built with HTML5 and CSS3 that introduces me and showcases my projects. I chose these technologies because HTML provides the structure for organizing webpage content, while CSS allows me to style the layout and create a clean, consistent design using tools like Flexbox for alignment and spacing.

One challenge I faced while building this project was centering the text and navigation elements in the footer, which required experimenting with the `justify-content` and `align-items` properties to achieve the desired layout.

In the future, I hope to expand the website by adding functional navigation links, additional project showcases, and improved responsive design so visitors can easily explore my work.

## Tutorial

### 1. How to Structure a Webpage with HTML

The Document Object Model (DOM) represents the structure of a webpage as a hierarchical tree of HTML elements. Each HTML element becomes a node in the DOM.

![HTML Layout Elements](https://www.w3schools.com/html/img_sem_elements.gif)

HTML layout elements are placed inside the `<body>` tags, as shown below.

**Example HTML:**

```html
<body>
  <header>
    <h1>My Website</h1>
  </header>

  <p>Welcome to my website!</p>
</body>
```

**DOM Tree:**

```text
body
├── header
│   └── h1
└── p
```

### 2. How to Style Sections with CSS

A website typically uses two separate files, HTML and CSS, to structure and style its content. The CSS file must be linked to the HTML document to control the visual presentation of the webpage.

**Example HTML:**

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="style.css">
  <!-- Links the external CSS stylesheet -->
</head>
```

Once the stylesheet is linked, developers can apply consistent colors, spacing, and layouts to webpage elements.

To style specific sections, developers assign unique classes or IDs to HTML elements.

**Example HTML:**

```html
<section id="header">
  <h1>Welcome to My Website</h1>
  <p>This is the introductory section.</p>
</section>

<div class="feature-box">
  <h2>Feature 1</h2>
  <p>Details about the first feature.</p>
</div>

<div class="feature-box">
  <h2>Feature 2</h2>
  <p>Details about the second feature.</p>
</div>
```

**Example CSS:**

```css
/* Styling all feature boxes using their class */
.feature-box {
  border: 1px solid #ccc;
  margin: 10px;
  padding: 15px;
  background-color: #f9f9f9;
}

/* Styling specific elements inside a feature box */
.feature-box h2 {
  color: darkblue;
  font-size: 1.5em;
}
```

It's best practice to name IDs and classes based on their content or purpose rather than their visual appearance.

### 3. How to Organize Content Using Flexbox

The Flexbox layout model provides an efficient way to arrange, align, and distribute space among items within a container. A flex container can expand items to fill available space or shrink them to prevent overflow.

**Note:** Flexbox is particularly useful for smaller-scale layouts and individual application components, while CSS Grid is generally suited to larger, two-dimensional layouts.

#### Justify-Content Property

![Justify-Content Image](https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg)

The `justify-content` property is an important feature of Flexbox. It controls the alignment of items along the main axis and distributes available space between or around flex items.

Common values include:

- `flex-start`: Aligns items at the beginning of the container.
- `flex-end`: Aligns items at the end of the container.
- `center`: Centers items along the main axis.
- `space-between`: Distributes items evenly with space between them.
- `space-around`: Distributes space around each item.
- `space-evenly`: Distributes equal spacing between and around items.

### 4. How to Apply Consistent Spacing

#### Step 1: Define Your Base Unit

The base unit in the 4-point spacing system is 4 pixels (px).

![4 Point Grid System](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*Qk1OMMQMHWcfrCCu3K0zhw.png)

All spacing values are multiples of this base unit. For example:

- 4px
- 8px
- 12px
- 16px
- 20px

#### Step 2: Apply Consistent Margins and Padding

**Margin:** Margin is the space outside an element. It creates separation between an element and surrounding elements, preventing the layout from becoming overcrowded.

**Padding:** Padding is the space inside an element, between its content and its border. It provides breathing room around text, images, and other content.

#### Step 3: Create a Visual Hierarchy

![Create a Visual Hierarchy](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*9ZFFXLfwPLWq22W06vRU8A.png)

To create a clear visual hierarchy, use different spacing values according to the importance and relationship of webpage elements.

For example, use 16px spacing between major sections and 8px spacing between related elements within a section. This helps visitors distinguish primary and secondary content.

## Technologies Used

- HTML5
- CSS3
- Flexbox
- Responsive CSS Media Queries
- Git and GitHub
- GitHub Pages

## Credits and References

- [W3Schools](https://www.w3schools.com/) – HTML semantic elements and webpage structure.
- [CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) – CSS Flexbox guide and alignment properties.
- [Medium / UX Planet](https://uxplanet.org/principles-of-spacing-in-ui-design-a-beginners-guide-to-the-4-point-spacing-system-6e88233b527a) – Principles of spacing in UI design and the 4-point spacing system.
- [Coding Temple](https://www.codingtemple.com/) – Web development coursework and learning resources.

---

**Project Status:** Completed

**Author:** Stephanie Nava Ramos

**Live Project:** [https://stephanie-ramos.github.io/CodingTemple-2Module-PortfolioAssignment/](https://stephanie-ramos.github.io/CodingTemple-2Module-PortfolioAssignment/)

