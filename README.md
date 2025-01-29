# CSS Specificity Bug: Unexpected Styling of List Items

This repository demonstrates a subtle CSS specificity bug that can lead to unexpected styling of list items. The bug occurs when using multiple selectors with varying specificity, causing one rule to override another unintentionally.

## Bug Description

The provided CSS code attempts to style two list items within a list with IDs. However, due to specificity issues, only one list item is styled as expected, while the other item remains with the browser's default styling.

## How to Reproduce

1. Open the `bug.css` file and review the provided CSS code.
2. Create an HTML file with the corresponding list structure.
3. Link `bug.css` to your HTML file.
4. Observe that only the second list item is styled according to the second CSS rule, while the first list item is not styled correctly due to the higher specificity of the second selector.

## Solution

The solution is provided in the `bugSolution.css` file.  This addresses the specificity issue and ensures both list items are styled as intended.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.
