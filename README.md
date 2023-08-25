# day9-geekster-assignment
In this app whenever user enter the text in input and by clicking add button the paragraph is appended in the browser below the text input.

The Button constant represents the "Add Text" button element retrieved from the DOM using its id.

The text constant represents the input field element where users can type their text.

The paragraph constant represents the container element where the dynamically added paragraphs will be placed.

An event listener is added to the Button element to listen for a click event.

When the button is clicked, the text from the input field is retrieved using the value property of the text element.

A new p (paragraph) element is created using document.createElement('p').

The content of the new paragraph is set to the retrieved text using the textContent property.

The new paragraph is appended to the paragraph container using the appendChild method.

Finally, the text in the input field is cleared for the next entry.

https://piyushyadavpy.github.io/day9-geekster-assignment/
