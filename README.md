# Inconsistent Width Calculation with CSS calc() Using Percentages and ems

This repository demonstrates an uncommon issue with CSS's `calc()` function when combining percentage and `em` units.  The problem arises from the inconsistent way browsers interpret and resolve mixed units within the `calc()` function, leading to unexpected and inconsistent widths across different viewport sizes and browsers.

## The Problem
The provided CSS code aims to create an element (`.element`) slightly larger than its parent container (`.container`).  However, the interaction between percentage and `em` units within `calc()` causes unpredictable results, particularly when the parent element's width or the font size changes.

## Solution
The solution explores alternative approaches to achieve the desired layout without relying on the potentially unreliable combination of percentage and `em` units within `calc()`.  These alternatives provide more predictable and consistent results across various browser and screen sizes.