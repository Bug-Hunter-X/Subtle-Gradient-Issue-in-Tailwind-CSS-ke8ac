# Subtle Gradient Issue in Tailwind CSS

This repository demonstrates a subtle issue that can occur when using Tailwind CSS gradients. If the `from-` and `to-` colors in a linear gradient are too similar, the resulting gradient may be barely visible or appear unexpectedly.

## Bug Report
The provided HTML uses Tailwind's gradient classes.  In some cases, the gradient may appear faint or not as intended due to the color similarity.  This isn't a syntax error, but rather a design consideration that might not be immediately apparent.

## Solution
The solution file shows how to increase the color contrast between the `from-` and `to-` colors to achieve a more visible and defined gradient.