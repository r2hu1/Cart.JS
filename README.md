## 1. **Include the Script**: 
Include the JavaScript file containing the `cartJS` function in your HTML file. You can do this by adding a `<script>` tag in your HTML file that points to the JavaScript file. For example:

```html
<script src="https://cdn.jsdelivr.net/gh/r2hu1/cart.JS@latest/src/cart.js"></script>
```

## 2. **Call the Function**:
Call the `cartJS` function in your HTML file. You can do this by adding a `<script>` tag in your HTML file that calls the `cartJS` function. For example:

```html
<script>cartJS();</script>
```

## 3. **HTML Structure**:
Your HTML structure should have elements with the classes `.addToCart`, `.itemTitle`, `.itemDescription`, `.itemQuantity`, `.itemPrice`, `.itemImg`, and `.cartItem`. The script will add an event listener to each `.addToCart` element and when clicked, it will retrieve the details of the item and add it to the cart.
For Example:

```html
<div class="item">
    <img src="product_img.png" class="itemImg"/>
    <h1 class="itemTitle">Product Title</h1>
    <p class="itemDescription">Product Description</p>
    <select class="itemQuantity">
      <option>1</option>
      <option>2</option>
      <option>3</option>
    </select>
    <h2 class="itemPrice">Product Price</h2>
    <button class="addToCart">Add To Cart (edit according to your need)</button>
  </div>
```

You can change select to input just add class `.itemQuantity` to it, For Example:
```html
<input type="number" class="itemQuantity"/>
```

[Live Demo](https://cartsjss.r2hu1.repl.co/)
[Code Demo](https://replit.com/@r2hu1/cartsjss#index.html)

## 4. **CSS Styling**:
Style your HTML elements as needed. The script does not provide any styling, so you will need to add your own CSS to style the cart and the items.

Remember to call the `cartJS` function after the DOM has fully loaded. You can ensure this by placing the `<script>` tags just before the closing `</body>` tag, or by calling the function in a `window.onload` or `$(document).ready()` event if you're using jQuery. 
