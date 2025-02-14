# Silent Failure: Modifying Non-Existent Element in HTML

This repository demonstrates a common but often overlooked error in JavaScript interacting with HTML elements: attempting to modify an element that doesn't exist in the DOM.

The `bug.html` file contains the erroneous code.  The script tries to change the innerHTML of an element with the ID "myDiv2", but this element is not present in the HTML.

The `bugSolution.html` file shows how to correct this error by first checking if the element exists before attempting to modify it.

This type of error can be difficult to debug because it doesn't throw an exception.  The script appears to run normally but doesn't produce the intended result.  Always check for element existence before manipulation to prevent unexpected behavior.