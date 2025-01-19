# Dynamic Product Card Creation using JavaScript Data Objects

## Overview
This project demonstrates the creation of dynamic product cards entirely using JavaScript. The product details are defined as JavaScript objects, and the cards are generated dynamically on the webpage using DOM manipulation. Styling is implemented directly in JavaScript without relying on external or internal CSS files.

## Features
- Dynamic generation of product cards based on JavaScript object data.
- Cards include product details such as name, description, price, and category.
- All styles are applied directly through JavaScript, ensuring no dependency on external CSS.

## Project Structure
The project is implemented entirely in a single JavaScript file. The HTML document is minimal, with only a root container where the dynamically generated cards are appended.

### Key JavaScript Concepts Used:
- JavaScript objects for storing product data.
- DOM manipulation methods like `document.createElement`, `appendChild`, and `style`.
- Inline styling using `element.style`.
- Event-driven programming for potential future extensions.

## Example Product Data
```javascript
let obj = [
    {
        "id": 1,
        "title": "Fjallraven - Foldsack No. 1 Backpack, Fits 15 Laptops",
        "price": 109.95,
        "description": "Your perfect pack for everyday use and walks in the forest. Stash your laptop (up to 15 inches) in the padded sleeve, your everyday",
        "category": "men's clothing",
        "image": "https://fakestoreapi.com/img/81fPKd-2AYL._AC_SL1500_.jpg",
        "rating": {
            "rate": 3.9,
            "count": 120
        }
    }
];
```

## JavaScript Logic
1. **Creating Product Data**:
   - Product data is stored in using for loop objects.
2. **Dynamic DOM Manipulation**:
   - Elements such as `div`, `h2`, `p`, etc., are created dynamically.
   - Properties like `textContent` and `style` are used to set content and styling.
3. **Appending to the Document**:
   - The dynamically created elements are appended to a root container in the HTML body.

## Inline Styling Example
All styles are applied via JavaScript using the `style` property. For example:
```javascript
card.style.border = "1px solid #ddd";
card.style.padding = "16px";
card.style.margin = "16px";
card.style.borderRadius = "8px";
card.style.boxShadow = "0 2px 5px rgba(0,0,0,0.1)";
```

## How to Run
1. Open the `index.html` file in any modern web browser.
2. The JavaScript code will dynamically generate the product cards and display them on the page.

## Customization
- To add more products, define additional objects in the script.
- Update the styles in the JavaScript file to match your design preferences.

## Example Output
Each product card will display:
- Product Name
- Description
- Price
- Category
- rating

The cards are styled with a minimalistic and modern look directly from the JavaScript file.

