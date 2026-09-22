# Question 1.
## CSS Box Model
 
The CSS Box Model describes how every HTML element is rendered as a rectangular box, made up of nested layers.
 
### Layers of the Box Model
1. Content – the actual text, image, or element data.
2. Padding – space between the content and the border.
3. Border – the line surrounding the padding and content.
4. Margin – space between the border and neighboring elements.

---
 
# Question 2.
## Media Query
 
A Media Query is a CSS technique used to apply styles based on the device's screen size, orientation, or resolution, enabling responsive web design.
 
Key Feature
- Adjusts layout for different screen sizes.
- Uses @media rule with conditions.
- Supports width, height, orientation, resolution checks.

Sample Code
```
<style>
    body {
        background-color: lightblue;
    }
 
    @media (max-width: 600px) {
        body {
            background-color: lightyellow;
        }
    }
</style>
```
 
---

# Question 3.
## Features of Bootstrap
 
Bootstrap is a popular front-end framework that helps build responsive, mobile-first websites quickly.
 
Key Feature
- Responsive Grid System
- Pre-styled Components (buttons, cards, navbars, modals)
- Utility Classes for spacing, colors, and text
- Cross-browser Compatibility
- Customizable Themes
- JavaScript Plugins (carousel, dropdown, tooltip)
---

# Question 4.
## Basic Grid Structure in Bootstrap
 
Bootstrap's grid system is based on a 12-column layout using containers, rows, and columns.
 
```
<div class="container">
    <div class="row">
        <div class="col">Column 1</div>
        <div class="col">Column 2</div>
        <div class="col">Column 3</div>
    </div>
</div>
```
---

# Question 5.
## CSS Selectors
 
CSS Selectors are patterns used to select and style specific HTML elements.
 
Types of Selectors
1. Universal Selector – *
2. Element Selector – p, h1
3. Class Selector – .classname
4. ID Selector – #idname
5. Attribute Selector – type="text"
6. Pseudo-class Selector – :hover, :first-child
7. Pseudo-element Selector – ::before`, `::after
8. Group Selector – h1, h2, p
9. Descendant Selector – div p
10. Child Selector – div > p
---

# Question 6.
## CSS Backgrounds
 
CSS background properties control the background appearance of an element.
 
Properties
- background-color – sets the background color.
- background-image – sets an image as the background.
- background-repeat – controls repetition (repeat, no-repeat, repeat-x, repeat-y).
- background-position – positions the background image.
- background-size – sizes the background image (cover, contain, custom).
- background-attachment – fixed or scrolling background.
- background – shorthand property combining all of the above.
---

# Question 7.
## Overlapping Elements in CSS
 
Elements can be made to overlap by taking them out of the normal document flow and controlling their stacking order.
 
Ways to Overlap Elements
1. Positioning – use position: relative/absolute/fixed along with top, left, right, bottom.
2. z-index – controls which element appears on top when elements overlap.
3. Negative Margins – pull an element over another using negative margin values.
4. CSS Grid/Flexbox – place multiple elements in the same grid cell.
5. Transform – use transform: translate() to shift an element over another.

---
 
# Question 8.
## Positioning Properties in CSS
 
The position property defines how an element is placed in the document.
 
Types
1. Static – default position; follows normal document flow.
2. Relative – positioned relative to its normal position.
3. Absolute – positioned relative to its nearest positioned ancestor.
4. Fixed – positioned relative to the browser window; stays in place while scrolling.
5. Sticky – toggles between relative and fixed depending on scroll position.
---

# Question 9.
## ECMAScript
 
ECMAScript (ES) is the standardized scripting language specification on which JavaScript is based.
 
Key Points
- Maintained by ECMA International (TC39 committee).
- JavaScript is an implementation of the ECMAScript standard.
- Defines syntax, types, statements, and core features of the language.
Major Versions
- ES5 (2009) – basic standard features.
- ES6 / ES2015 – let, const, arrow functions, classes, promises, template literals.
- ES2016 onward – yearly updates adding features like async/await, optional chaining, spread/rest operators.
---

# Question 10.
## var, let, const and Temporal Dead Zone
 
### var
- Function-scoped.
- Can be re-declared and updated.
- Hoisted and initialized with `undefined`.
### let
- Block-scoped.
- Can be updated but not re-declared in the same scope.
- Hoisted but not initialized.
### const
- Block-scoped.
- Cannot be updated or re-declared.
- Must be initialized at declaration.
## Temporal Dead Zone (TDZ)
The Temporal Dead Zone is the period between the start of a block and the point where a `let` or `const` variable is declared, during which the variable exists but cannot be accessed.
