


Answer: getElementById returns an element object that specifies the element for which id property matches with the specified string ie., it returns a single DOM element whose id matches the specific query.On the otherhand, getElementsByClassName returns an array-like object of all child-element that contains all the given class name(s) ie., it will return an HtmlCollection - an array-like structure containing the DOM elements that matched the query, that is needed to iterate through each element in the array to apply the style.
. The querySelector() method returns the first element that matches a CSS selector. To return all matches (not only the first), use the querySelectorAll() instead. Both querySelector() and querySelectorAll() throw a SYNTAX_ERR exception if the selector(s) is invalid.

Answer: const container = document.querySelector(".container");
// create a new element
const newDiv = document.createElement("div");
newDiv.innerText = "This is a new div";
// Append to container
container.apendChild(new div);

Answer: Event bubbling is a type of DOM event propagation where the event first triggers on the innermost target element, and then successively triggers on the ancestors (parents) of the target element in the same nesting hierarchy till it reaches the outermost DOM element or document object.

Answer: Event delegation is a powerful pattern in JavaScript that improves both the performance and maintainability of your code, especially when dealing with dynamic content or a large number of elements. By leveraging event bubbling, you can reduce the number of event listeners and streamline your code.

Answer: preventDefault() is used to prevent the default action that belongs to the event, such as preventing a form from submitting. event. stopPropagation() is used to stop the event from bubbling up to parent elements, preventing any parent event handlers from being executed.
