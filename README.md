## 1. **Include the Script**: 
Include the JavaScript file containing the `cartJS` function in your HTML file. You can do this by adding a `<script>` tag in your HTML file that points to the JavaScript file. For example:

```html
<script src="path_to_your_javascript_file.js"></script>
```

## 2. **Call the Function**:
Call the `cartJS` function in your HTML file. You can do this by adding a `<script>` tag in your HTML file that calls the `cartJS` function. For example:

```html
<script>cartJS();</script>
```

## 3. **HTML Structure**:
Your HTML structure should have elements with the classes `.addToCart`, `.itemTitle`, `.itemDescription`, `.itemQuantity`, `.itemPrice`, `.itemImg`, and `.cartItem`. The script will add an event listener to each `.addToCart` element and when clicked, it will retrieve the details of the item and add it to the cart.

## 4. **CSS Styling**:
Style your HTML elements as needed. The script does not provide any styling, so you will need to add your own CSS to style the cart and the items.

Remember to call the `cartJS` function after the DOM has fully loaded. You can ensure this by placing the `<script>` tags just before the closing `</body>` tag, or by calling the function in a `window.onload` or `$(document).ready()` event if you're using jQuery. 
