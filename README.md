# :nth-child(n+2) CSS Selector Issue with Combined Selectors

This repository demonstrates a problem with the `:nth-child(n+2)` CSS selector when it's combined with other selectors. The selector aims to target all elements except the first child, but unexpected behavior can occur when it's combined with other styles.

## Problem

The `bug.css` file contains a simple CSS rule that attempts to style list items, excluding the first one. The result isn't what is expected when other styles are added.

## Solution

The `bugSolution.css` file provides a solution to this issue. It ensures that the styling of list elements is unaffected by other selectors and addresses the unexpected behavior observed in `bug.css`.