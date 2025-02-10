# Uncommon HTML Bug: Typo in getElementById

This repository showcases a subtle bug in HTML/JavaScript related to a simple typo in accessing DOM elements.

## Bug Description
The JavaScript code contains a typo in the function call `document.getElementByIdx()`. The correct function is `document.getElementById()`, which is used to retrieve elements from the HTML document using their ID.

## Bug Solution
The solution simply corrects the typo in the JavaScript code by changing `document.getElementByIdx()` to `document.getElementById()`, thus properly interacting with the HTML element.

## How to Reproduce
1. Open `bug.html` in a web browser.
2. Observe that the text within the div element is unexpectedly still visible (despite an attempt to hide it).
3. Open `bugSolution.html` and observe the correct behavior, where the text is hidden successfully.
