# Inconsistent Background Color in CSS Across Browsers

This repository demonstrates a CSS issue where background colors are not consistently applied across different browsers. The problem stems from conflicting styles and CSS specificity.

## Problem

The `bug.css` file contains a CSS rule where a child element (`p`) has a background color that unintentionally overrides the parent container's background color. This inconsistency may lead to different visual results across different browsers or rendering engines.

## Solution

The `bugSolution.css` file presents a corrected version.  It addresses the specificity issue by using more appropriate selectors or adjusting the order of CSS rules to ensure the intended background color takes precedence.