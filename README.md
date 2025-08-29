# A04
1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById gets one single element using its unique ID.

getElementsByClassName gets a list of all elements that have a specific class name.

querySelector is a flexible search that finds the first element matching a CSS selector. querySelectorAll is similar but finds all matching elements.

2. How do you create and insert a new element into the DOM?
It's a two-step process. First, you create the element in memory with document.createElement(). Then, you find an element already on the page and add your new element to it using appendChild().

3. What is Event Bubbling and how does it work?
Event bubbling is when an event that happens on one element (like a click) also triggers on its parent, and then its parent's parent, and so on, all the way up the chain. The event "bubbles up" from the inside out.

4. What is Event Delegation in JavaScript? Why is it useful?
Event delegation is a technique where you put a single event listener on a parent element instead of putting one on every single child. Because of bubbling, the parent can catch events from its children. It's useful because it improves performance and automatically works for new child elements you add later.

5. What is the difference between preventDefault() and stopPropagation() methods?
preventDefault() stops the browser's default behavior for an element, like stopping a link from going to a URL or a form from submitting.

stopPropagation() stops event bubbling, preventing an event from traveling up to parent elements.
