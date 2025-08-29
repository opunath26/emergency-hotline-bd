1.What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll? 
Ans:
getElementById - Selects one element by its unique id.
getElementsByClassName - Selects multiple elements with the same class (HTMLCollection).
querySelector - Selects the first element matching a CSS selector.
querySelectorAll - Selects all elements matching a CSS selector (NodeList).

2.How do you create and insert a new element into the DOM? 
Ans:
Create the element - use document.createElement("tagName").
Add content/attributes - set innerText, innerHTML, or add classes/IDs.
Insert into DOM - use methods like appendChild(), append(), prepend(), or insertBefore() to place it in the document.

3.What is Event Bubbling and how does it work? 
Ans:
Event Bubbling means when an event happens on a child element, it first runs on that element, then automatically goes upward to its parent, then grandparent, and so on until the root (document).
 In short: event flows from child - parent - root.

4.What is Event Delegation in JavaScript? Why is it useful? 
Ans:
Event Delegation is a technique where we add an event listener to a parent element to handle events of its child elements using event bubbling.

Useful because:
*We don’t need separate listeners for each child.
*Improves performance.
*Works even for dynamically added child elements.

5.What is the difference between preventDefault() and stopPropagation() methods? 
Ans:
*preventDefault() - Stops the default action of an element (e.g., stopping a form from reloading the page on submit).
*stopPropagation() - Stops the event from bubbling up to parent elements.