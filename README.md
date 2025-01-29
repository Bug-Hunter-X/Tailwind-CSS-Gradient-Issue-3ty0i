# Tailwind CSS Gradient Issue

This repository demonstrates a bug related to gradient rendering in Tailwind CSS. The gradient doesn't display as expected. 

## Bug Description
The `bg-gradient-to-r` utility doesn't render the gradient correctly. The gradient might be cut off, partially displayed, or appear incorrectly across different browsers. This might be due to conflicts with other styles, incorrect configuration, or browser-specific rendering issues.

## Solution
The solution involves ensuring the parent container has sufficient dimensions to display the gradient completely.  Additionally, we can add a fallback for older browser compatibility. 

## How to reproduce the bug
1. Clone the repository.
2. Open `bug.html` in your browser.