# Incorrectly Hiding a Div Element

This repository demonstrates a subtle bug related to hiding HTML elements using JavaScript.  The bug arises from incorrectly using `style.display = "none"` to hide an element that doesn't have its `display` property set inline. 

The `bug.html` file shows the problem; `bugSolution.html` shows the correct solution.

The common approach `style.display = "none"`  works only when the element's display property is set inline.  If it's not, using `style.visibility = "hidden"` is a more reliable approach to hide the element.