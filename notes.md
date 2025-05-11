
**Introduction to jQuery**
-------------------------- 

jQuery is a popular JavaScript library designed to simplify and enhance web development. It provides a wide range of features and functions that make it easier to manipulate HTML documents, handle events, create animations, perform AJAX requests, and more. jQuery aims to streamline the process of writing JavaScript code, making it more concise, readable, and cross-browser compatible.


## 📌 jQuery Selectors

jQuery provides powerful and flexible selectors that allow you to easily target and manipulate elements in the DOM. Below are some of the most commonly used selectors:

### 🔹 Basic Selectors

* **Element Selector**
  $$
  Selects all elements by tag name.
  **Syntax:** `$('elementName')`
  **Example:** `$('p')` — selects all `<p>` elements.
  $$

* **ID Selector**
  Selects a single element with a specific ID.
  **Syntax:** `$('#idName')`
  **Example:** `$('#myElement')` — selects the element with `id="myElement"`.

* **Class Selector**
  Selects all elements with a given class.
  **Syntax:** `$('.className')`
  **Example:** `$('.myClass')` — selects all elements with `class="myClass"`.

### 🔹 Advanced Selectors

* **Attribute Selector**
  Targets elements by attribute and value.
  **Syntax:** `$('element[attribute="value"]')`
  **Example:** `$('input[type="text"]')` — selects all text input fields.

* **Descendant Selector**
  Selects all matching elements within a specified parent.
  **Syntax:** `$('parent descendant')`
  **Example:** `$('div p')` — selects all `<p>` elements inside `<div>`s.

* **Child Selector**
  Targets direct children of a parent element.
  **Syntax:** `$('parent > child')`
  **Example:** `$('ul > li')` — selects `<li>`s that are direct children of `<ul>`.

### 🔹 Positional Selectors

* **`:first` Selector**
  Selects the first matched element.
  **Syntax:** `$('selector:first')`
  **Example:** `$('p:first')` — selects the first `<p>` element.

* **`:last` Selector**
  Selects the last matched element.
  **Syntax:** `$('selector:last')`
  **Example:** `$('div:last')` — selects the last `<div>` element.

* **`:even` and `:odd` Selectors**
  Select elements by even or odd index (0-based).
  **Syntax:** `$('selector:even')`, `$('selector:odd')`
  **Example:** `$('tr:even')` — selects even-indexed rows in a table.

* **`:not()` Selector**
  Excludes elements that match a certain selector.
  **Syntax:** `$('selector:not(otherSelector)')`
  **Example:** `$('input:not(:checked)')` — selects unchecked inputs.

---


---

## 📋 jQuery DOM Manipulation Methods (with Syntax)

### ✏️ Content Manipulation

| Method       | Description                                 | Syntax                                                        |
| ------------ | ------------------------------------------- | ------------------------------------------------------------- |
| `.text()`    | Get or set plain text content               | `$('selector').text()`<br>`$('selector').text('New text')`    |
| `.html()`    | Get or set HTML content                     | `$('selector').html()`<br>`$('selector').html('<b>HTML</b>')` |
| `.append()`  | Add content to the end of selected elements | `$('selector').append('<p>Content</p>')`                      |
| `.prepend()` | Add content to the beginning of elements    | `$('selector').prepend('<p>Content</p>')`                     |
| `.after()`   | Insert content after selected elements      | `$('selector').after('<p>After</p>')`                         |
| `.before()`  | Insert content before selected elements     | `$('selector').before('<p>Before</p>')`                       |

---

### 🔧 Attribute and Property Manipulation

| Method          | Description                             | Syntax                                                                |
| --------------- | --------------------------------------- | --------------------------------------------------------------------- |
| `.attr()`       | Get or set an attribute value           | `$('selector').attr('name')`<br>`$('selector').attr('name', 'value')` |
| `.removeAttr()` | Remove an attribute                     | `$('selector').removeAttr('name')`                                    |
| `.prop()`       | Get or set a property (e.g., `checked`) | `$('selector').prop('name')`<br>`$('selector').prop('name', value)`   |
| `.val()`        | Get or set form element value           | `$('selector').val()`<br>`$('selector').val('New value')`             |

---

### 🎨 CSS Class Manipulation

| Method           | Description                                 | Syntax                                   |
| ---------------- | ------------------------------------------- | ---------------------------------------- |
| `.addClass()`    | Add one or more classes                     | `$('selector').addClass('className')`    |
| `.removeClass()` | Remove one or more classes                  | `$('selector').removeClass('className')` |
| `.toggleClass()` | Add class if not present, remove if present | `$('selector').toggleClass('className')` |
| `.hasClass()`    | Check if element has a specific class       | `$('selector').hasClass('className')`    |

---

### 🎨 Style and Visual Effects

| Method       | Description                       | Syntax                                                  |
| ------------ | --------------------------------- | ------------------------------------------------------- |
| `.css()`     | Get or set CSS styles             | `$('selector').css('property', 'value')`                |
| `.width()`   | Get or set the width of elements  | `$('selector').width()`<br>`$('selector').width(200)`   |
| `.height()`  | Get or set the height of elements | `$('selector').height()`<br>`$('selector').height(150)` |
| `.show()`    | Make elements visible             | `$('selector').show()`                                  |
| `.hide()`    | Hide elements from view           | `$('selector').hide()`                                  |
| `.fadeIn()`  | Fade elements into view           | `$('selector').fadeIn()`                                |
| `.fadeOut()` | Fade elements out of view         | `$('selector').fadeOut()`                               |

---


