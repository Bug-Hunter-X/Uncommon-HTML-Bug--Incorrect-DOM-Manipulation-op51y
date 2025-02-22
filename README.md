# Uncommon HTML Bug: Incorrect DOM Manipulation

This repository demonstrates a subtle bug in HTML and JavaScript related to incorrect DOM manipulation. The bug involves a typo in accessing a DOM element, leading to unexpected behavior.

## Bug Description
The `bug.html` file contains a simple HTML structure with a div element whose innerHTML should be modified by a JavaScript script. However, the script contains a typo, using `getElementByIdx` instead of `getElementById`, which results in the `innerHTML` not being updated as intended.

## Solution
The `bugSolution.html` file provides the corrected code. The typo in the getElementById function is fixed, and the innerHTML is correctly modified to show the changed text.

## How to reproduce
1. Clone this repository
2. Open `bug.html` in a web browser
3. Observe that the text in the div element does not change, demonstrating the bug.
4. Open `bugSolution.html` in a web browser
5. Observe that the text in the div element changes correctly, demonstrating the fix.