# Uncommon HTML Bug: Handling Non-Existent Elements

This repository demonstrates a subtle but important bug in HTML: attempting to modify the `innerHTML` of a non-existent element.  While common errors involve syntax or tag mismatches, this example focuses on a runtime error that can be easily overlooked.

The `bug.html` file shows the incorrect code, which silently fails without any error message in the browser console. The solution is shown in `bugSolution.html`, correctly checking the existence of an element before modifying it. This approach ensures that code execution does not fail unexpectedly.