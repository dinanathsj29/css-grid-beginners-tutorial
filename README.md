<p align="center">
 <img src="_images-css-grid/1-css3-logo-1.png" alt="CSS Grid Layout Module" title="CSS Grid Layout Module" width="200" />
</p>

CSS Grid
=====================

CSS Grid Layout Module (CSS Grid) is one of the most widely used and popular mechanisms which provides flexibility to create/build or design complex, nested, highly professional and ` two-dimensional system layouts (2D - handles both columns as well as rows)`.

Welcome
---------------------

Hi All, I'm **`Dinanath Jayaswal, Senior UI/Web Developer and Adobe Certified Expert Professional`**, I wanna welcome you to CSS Grid Tutorial for beginners. 

About the Course/Tutorial
---------------------

This is a comprehensive guide to the CSS Grid Layout Module. This complete guide explains everything about the CSS Grid Layout Module (CSS Grid).

Who is this for? 
---------------------

This Course/Tutorial is ideal for:
- Any Web designer/developer interested in getting a deep understanding of CSS Grid Layout Module (CSS Grid)
- CSS lovers want to acquire knowledge of next/latest CSS level (properties/features)
- Candidates desire to become CSS Expert and better Front End web Developer / Designer
- Web designers/developers who want to improve skills with new web standards

Course/Tutorial achievement
---------------------

Course/Tutorial Goal
---------------------

After completing/attending/finishing this Course/Tutorial, participants should be able to: 
- Align/arrange elements using modern CSS module, like CSS Grid 
 - Create Complex grid-based web layouts
- Use the new CSS3 Grid model to create responsive web layouts more effectively!
- Use/Operate CSS Grid confidently to create modern/advanced layouts
 - implement complete complex-nested site layouts / create modern grids

Prerequisites for current course / What you need to know
---------------------

- Basic knowledge of HTML5 and CSS3

Topics included/covered
=====================

1. [Introduction to CSS Grid](#1-introduction-to-css-grid)
    - 1.1. [What is CSS Grid](#11-what-is-css-grid)
    - 1.2. [Layout modes](#12-layout-modes)
    - 1.3. [Why CSS Grid?](#13-why-css-grid)
    - 1.4. [Browser support](#14-browser-support)
    - 1.5. [Important Terminology](#15-important-terminology)

1 Introduction to CSS Grid
=====================

1.1. What is CSS Grid
---------------------

- `CSS Grid is a two-dimensional layout system` created specifically to tackle grid-based user interfaces on the web
- `CSS Grid Layout Module` is a CSS3 layout mode that provides an easy, professional and advanced clean way to arrange child elements/items within a container
- CSS Grid is a brand new layout system in CSS! It's not a framework or library - it's an addition to the CSS stylesheet language that allows us to quickly `create flexible, two-dimensional layouts` (with Columns and Rows)
- CSS Grid can be used to `place, size, align, arrange and architect complex layouts/designs` that were previously pretty difficult or even impossible with floats or flexbox
- The Grid Layout Working Draft was published back in April 2011, W3C Candidate Recommendation as of 14 December 2017

1.2. Layout modes
---------------------

Before CSS there were 5 layout modes/models:
1. **`Block`** (for different sections in a webpage)
2. **`Inline`** (for text and spans in the same line)
3. **`Table`** (for two-dimensional tabular data)
4. **`Position`** (for the explicit position of an element)
5. **`Flexbox`** (for one-dimensional grid layout)

### Pre-CSS Grid we have used:
- Different positional properties like `fixed, absolute` to set alignment at the exact required place
- `Floats and clear fixes` to create navigation, detailed section
- Fixed heights columns to show equality
- Above mentioned layout modes does not provide enough flexibility to create/build or design professional/nested/modern layouts
- we need to include another CSS mechanism like Floats, Vertical alignment of text/elements and other hacks with Margin, Padding to create the accurate/desired layout
- `CSS Flexible Box Layout Module (Flexbox)`, makes it easier to design flexible responsive layout structure without using float or positioning

1.3. Why CSS Grid?
---------------------

Grid/CSS Grid Layout provides lots of flexibilities while creating complex layouts like:
- CSS Grid is a new way of creating layouts, the first time a proper layout system available natively in the browser with tons of benefits
- Grid is a new CSS display type designed to craft CSS layouts in a much easier way
- No CSS Float used
- Helps to create a nested Grid layout and place them on a webpage
- Arrange items from left to right or top to bottom and vice versa
- Adjust the spacing between objects
- Position and alignments of items
- Order and placements of various elements 
- Improve the items alignment, directions and order in the container even when they are with dynamic or even unknown size
- Equal height columns
- Ability to modify the width or height of its children to fill the available space in the best possible way on different screen sizes
- Control the position, size, and spacing of child elements relative to parent container and other child elements
- CSS Grid works great responsively (RWD - Responsive Web Design)
- Responsive and Mobile friendly

1.4. Browser support
---------------------

The CSS Grid properties are supported in all modern browsers:

<p>
  <figure>
    &nbsp;&nbsp;&nbsp; <img src="_images-css-grid/1.4-css-grid-browser-support.png" alt="CSS Grid browser support" title="CSS Grid browser support" width="1000" border="2" />
    <figcaption>&nbsp;&nbsp;&nbsp; Image - CSS Grid browser support </figcaption>
  </figure>
</p>

1.5. Important Terminology
---------------------

Let's learn some of the Important Terminology/concepts related to CSS Grid Layout to get proper understandings and how does it work. Here are the main terms or entities while dealing with CSS Grid:
- **`display:grid`** (CSS property/style which converts an HTML element to a grid container - *`display: grid or inline-grid`*)
1. **`Grid Container`** (Direct Parent/Container to hold sub-items, to the container we apply *` display: grid or inline-grid`* property)
2. **`Grid Items`** (Child/sub-items [direct descendants] within Container - All direct children of the `grid container` automatically become `grid items`)
3. **`Grid Column`** (The vertical series-part/portrait lines of the grid, table, chart or spreadsheet)
4. **`Grid Row`** (The horizontal series-part/landscape lines of grid, table, chart or spreadsheet)
5. **`Grid Gaps`** (The spaces (margin or cell-spacing) between each column/row)
6. **`Grid Line`** (The lines between columns/rows, the dividing lines that make up the structure of the grid )
7. **`Grid Track`** (A grid track is a space between 2 adjacent grid lines, they are the rows and columns of your grid)
8. **`Grid Cell`** (A box/intersection point where the column and row get insects it creates a box/cell like a table cell, A grid cell is the space between 2 adjacent row grid lines and 2 adjacent column grid lines)
9. **`Grid Area`** (The total space surrounded by four grid lines, A grid area is made up of 1 or more grid cells, and is bound by 4 grid lines on each side of the grid area)
10. **`The fr Unit`** (The new `fr unit` represents a fraction of the available space in the grid container)

To start with CSS Grid just apply a property `display` type of `grid` to the parent container/Grid Container (grid container), so Grid Items/child items/elements automatically turn to the grid item.


