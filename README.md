# Tailwind CSS Fractional Width Class Rounding Error

This repository demonstrates a common issue with Tailwind CSS's fractional width classes, specifically `w-1/2`. Due to rounding errors in the underlying CSS calculations, using `w-1/2` on two sibling elements doesn't always result in a perfectly even 100% width distribution. This can lead to unexpected gaps or overlaps in the layout.

The `bug.html` file showcases the problem, while `solution.html` provides a simple workaround using `flex-grow`.