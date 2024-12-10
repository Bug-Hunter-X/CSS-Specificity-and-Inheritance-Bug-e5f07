# CSS Specificity and Inheritance Bug

This repository demonstrates an uncommon bug related to CSS specificity and inheritance. The bug arises from unexpected inheritance behavior when dealing with selectors of varying specificity.  The solution clarifies how to solve such inheritance issues and achieve the desired styling.

## Bug Description

The bug involves an unexpected inheritance of the `color` property due to the specificity of CSS selectors. A more specific selector does not always override styles from less specific selectors when it comes to inheritance from parent elements. This can lead to unexpected styles applied to elements.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` to see the problematic CSS.
3. Observe the unexpected color of the `<span>` element.

## Solution

The solution involves explicitly setting the desired color to overcome specificity conflicts and unexpected inheritance behavior.

Open `bugSolution.css` to see the corrected CSS.