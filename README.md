# CSS Specificity Bug
This repository demonstrates a common CSS issue related to selector specificity.  A `<div>` element with the class `red` unexpectedly renders green due to a more specific selector overriding the expected color.

The `bug.css` file contains the buggy CSS code.  The solution, found in `bugSolution.css`, addresses the specificity conflict by carefully ordering or adjusting selectors. 

This example highlights the importance of understanding CSS specificity when styling elements.