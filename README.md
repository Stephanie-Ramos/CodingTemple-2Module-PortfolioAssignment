# First Assignment

![Portfolio Clip Art](https://media.istockphoto.com/id/1333205574/vector/a-portfolio-folder-with-memos-and-bookmarks-office-paperwork-routine.jpg?s=1024x1024&w=is&k=20&c=tN_YK81GoLqdOJ89UeFA9LTtZM6EDMS59UPshgGQ54Q=)

# Project Description 
This project is a ***personal portfolio landing page** built with HTML and CSS that introduces me and showcases my projects. I chose these technologies because HTML provides the structure for organizing the webpage content, while CSS allows me to style the layout and create a clean, consistent design using tools like Flexbox for alignment and spacing. One challenge I faced while building this project was centering the text in the footer, which required experimenting with justify-content property to achieve the desired layout. In the future, I hope to add working webpage links to the navigation bar so visitors can easily navigate between sections and view more of my work.

# Tutorial
## How to Structure a Webpage with HTML
Document Object Model (DOM) represents the structure of a web page as a hierarchical tree of HTML elements. Each HTML element becomes a node in the DOM. 

![HTML Layout Elements](https://www.w3schools.com/html/img_sem_elements.gif)

The HTML layout elements goes inside the body tags, as shown below: 

Example HTML:
```
<body>
  <header>
    <h1>My Website</h1>
  </header>
  <p>Welcome to my website!</p>
</body>
```
DOM Tree:
```
body
├─ header
│  └─ h1
└─ p
```

## How to Style Sections with CSS
The developer must contain two files, HTML and CSS, in order to structure and style the website. The CSS file must linked into the HTML file in order to demonstrate the visual representation of the website, as shown below:

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="style.css"> /* referencing to the "style.css" file */
</head>
```

Once it's linked, the developer can apply consistent colors and layout to the containers. To style specific sections of a website using CSS, the developer must first assign unique classes or IDs to the HTML elememnts. 

For Example:
In HTML:
```
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

In CSS: 
```
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
It's best practice to name the IDs and classes based on their content or purpose and not on their appearance. 

## How to Organize Content using Flexbox
The flexbox layout aims at providing a more efficient way to lay out, align and distribute space among items in a container. A flex container expands items to fill available free space or shrinks them to prevent overflow.

Note: Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the Grid layout is intended for larger scale layouts.

### Justify-Content Property 
![Justify-Content Image](https://css-tricks.com/wp-content/uploads/2018/10/justify-content.svg)

justify-content is a key property of flexbox. This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size. It also exerts some control over the alignment of items when they overflow the line.


## How to Apply Consistent Spacing
### Step 1: Define Your Base Unit
The base unit in the 4-point spacing system is 4 pixels (px).

![4 Point Grid System](https://miro.medium.com/v2/resize:fit:4800/format:webp/1*Qk1OMMQMHWcfrCCu3K0zhw.png)

All spacing values will be multiples of this base unit. For example, you can use 4px, 8px, 12px, 16px, and so on.

### Step 2: Apply Consistent Margins and Padding 
**Margin**: Margin is the space outside an element. It creates a gap between the element and other elements around it, ensuring that everything isn’t too crowded together.

**Padding**: Padding is the space inside an element. It creates a gap between the element’s content (like text or images) and its border, giving the content some breathing room.

### Step 3: Create a Visual Hierarchy
To create a clear visual hierarchy, use different spacing values for different levels of importance.

![Create a Visual Hierarchy](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*9ZFFXLfwPLWq22W06vRU8A.png)

For example, you can use 16px spacing between major sections and 8px spacing between related elements within a section. This helps users easily distinguish between primary and secondary content.


# Credits
[W3Schools](https://www.w3schools.com/)
[CSS-Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
[Medium](https://uxplanet.org/principles-of-spacing-in-ui-design-a-beginners-guide-to-the-4-point-spacing-system-6e88233b527a)
[Coding Temple](https://www.codingtemple.com/?utm_source=google_ads&utm_medium=paid_search&utm_campaign=Branded_Search&ad_group_id=142673746073&ad_id=763015858249&utm_term=coding%20temple%20bootcamp&match_type=e&placement&device=c&target_id=kwd-367583562367&network=g&ad_variation_id&ad_position&placement_category&ad_type&campaign_id=18333267253&keyword_id=kwd-367583562367&tw_source=google&tw_adid=763015858249&tw_campaign=18333267253&tw_kwdid=kwd-367583562367&gad_source=1&gad_campaignid=18333267253&gbraid=0AAAAAC7KGVlOb1C5cdXBQi-GnXg2ug8Tj&gclid=Cj0KCQiA8KTNBhD_ARIsAOvp6DI_lJ89xEGoPiyaCkXwg6bMC1Fn82Ze0LPqUXsKsEidLQkeXcid2WsaAqb-EALw_wcB)

