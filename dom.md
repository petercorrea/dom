# DOM API Cheatsheet

## Basic Selection

- `document.getElementById('id')` - Selects an element by ID.
- `document.querySelector('selector')` - Selects the first element that matches the CSS selector.
- `document.querySelectorAll('selector')` - Selects all elements that match the CSS selector.

## Element Manipulation

- `element.textContent` - Get/Set the text content of an element.
- `element.innerHTML` - Get/Set the HTML content of an element.
- `element.setAttribute('name', 'value')` - Sets the value of an attribute.
- `element.getAttribute('name')` - Gets the value of an attribute.
- `element.removeAttribute('name')` - Removes an attribute.

## Style Manipulation

- `element.style.property = 'value'` - Sets the style of an element (camelCase for CSS properties).

## Class Manipulation

- `element.classList.add('class')` - Adds a class to an element.
- `element.classList.remove('class')` - Removes a class from an element.
- `element.classList.toggle('class')` - Toggles a class on an element.
- `element.classList.contains('class')` - Checks if an element has a specified class.

## Creating & Appending Elements

- `document.createElement('tag')` - Creates a new element.
- `parentElement.appendChild(childElement)` - Appends a child element to a parent.
- `element.insertAdjacentHTML('position', 'html')` - Inserts HTML relative to the element (`beforebegin`, `afterbegin`, `beforeend`, `afterend`).

## Event Handling

- `element.addEventListener('event', function)` - Attaches an event listener to an element.
- `element.removeEventListener('event', function)` - Removes an event listener from an element.

## Node Properties and Methods

- `node.childNodes` - Returns a NodeList of child nodes.
- `node.firstChild` - Returns the first child node.
- `node.lastChild` - Returns the last child node.
- `node.nextSibling` - Returns the next sibling node.
- `node.previousSibling` - Returns the previous sibling node.
- `node.parentNode` - Returns the parent node.

## Document Properties and Methods

- `document.forms` - Collection of the forms in the document.
- `document.images` - Collection of the images in the document.
- `document.links` - Collection of the links in the document.
- `document.createElement('tag')` - Creates a new element.
- `document.createTextNode('text')` - Creates a new text node.

## Navigation

- `element.parentElement` - Selects the parent element.
- `element.children` - Returns a live HTMLCollection of the child elements.
- `element.nextElementSibling` / `element.previousElementSibling` - Navigates to the next/previous element sibling.
