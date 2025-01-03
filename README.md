# CSS Specificity Gotcha: Unexpected Color Inheritance

This repository demonstrates a subtle bug related to CSS selector specificity.  The bug showcases a situation where the expected color inheritance doesn't occur as anticipated due to how the browser resolves specificity conflicts between different CSS selectors.

## The Bug

The `bug.css` file contains CSS rules that define the color of paragraph elements within a specific div container.  While intuition might suggest a certain color order based on selector specificity, the browser's actual rendering may differ. The unexpected output highlights a nuanced understanding of CSS selector specificity that is often overlooked.

## The Solution

The `bugSolution.css` file offers a solution that addresses the specificity issue by either making the specificity more explicit or restructuring the selectors to ensure the intended color is applied reliably.  This solution provides clarity on how to avoid such surprises in the future.

## How to Reproduce

1. Clone the repository.
2. Open `index.html` (You need to create this with the corresponding divs and paragraphs).
3. Observe the unexpected color of the paragraph element.