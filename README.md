# Uncommon HTML innerHTML Bug

This repository demonstrates a subtle bug related to the usage of `innerHTML` in HTML.  The bug arises from incorrect handling of quotes within the string assigned to `innerHTML`.

The `bug.html` file shows the incorrect implementation, while `bugSolution.html` provides the correct solution.

The core issue lies in how double quotes are managed when constructing the new HTML content using `innerHTML`.  The corrected version uses single quotes around the inner HTML, making it more robust.