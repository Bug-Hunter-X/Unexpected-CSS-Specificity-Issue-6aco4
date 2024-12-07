# Unexpected CSS Specificity Issue

This repository demonstrates a common CSS issue related to selector specificity.  The `bug.css` file shows how an overly broad selector can unintentionally style elements, while `solution.css` provides a more specific solution.

## Problem

The provided CSS styles `.container .box` elements in an unexpected way due to the lack of specificity in the selector. If the class 'box' is used elsewhere, it will also be styled. This is demonstrated in the `bug.css` file.