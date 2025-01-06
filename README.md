# CSS Specificity Bug

This repository demonstrates an uncommon bug related to CSS specificity. The bug involves unexpected styling due to the complex specificity rules of CSS.  The `bug.css` file contains the problematic CSS.  The `bugSolution.css` offers a solution. Understanding CSS Specificity is crucial to avoid such issues.

## Setup

1. Clone this repository.
2. Open `index.html` (not included in this json, needs to be created separately to test) in your browser to see the unexpected styling.

## Bug Description

The `bug.css` file uses complex selectors that lead to unexpected style application due to the way CSS specificity resolves conflicting styles.  The solution involves a better understanding of specificity and restructuring the CSS to avoid conflicts. 

## Solution

Refer to `bugSolution.css` for the corrected CSS.  The solution addresses the issue by simplifying selectors and prioritizing styles effectively. 