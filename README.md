# Uncommon HTML Bugs

This repository demonstrates two uncommon errors that can occur in HTML:

1. **Accessing Non-Existent Properties of Dynamically Created Elements:**  In many browsers, attempting to set a property on a dynamically created element that does not exist does not throw an error. However, accessing this non-existent property later might lead to unexpected behavior.
2. **Using innerHTML on a Non-Existent Element:**  Trying to access and modify the innerHTML of an element that doesn't exist will throw an error.

The `bug.html` file showcases these errors.  The `bugSolution.html` provides solutions for handling these situations gracefully.

## Solutions

The `bugSolution.html` provides improved code to address these issues. It includes checks to ensure elements exist before attempting to access their properties or modify their innerHTML.