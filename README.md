# Hidden HTML Element Bug

This repository demonstrates a common yet subtle bug in HTML/JavaScript where an element is hidden using JavaScript but never made visible again. The `myFunction()` hides the div with id "myDiv", but there is no code to restore its visibility.  This can lead to unexpected UI behavior and frustrated users.  The solution demonstrates how to properly manage element visibility. 

## Bug
The `bug.html` file contains the faulty code.  Clicking the button hides the div and never shows it again.

## Solution
The `solution.html` file provides a corrected version that addresses this issue by adding code to restore the element's visibility after a short delay using `setTimeout()`.