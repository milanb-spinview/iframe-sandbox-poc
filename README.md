# iframe-sandbox-poc

A small set of static pages demonstrating what an embedded page can do when the
host `<iframe>` has **no `sandbox` attribute**, and how `sandbox` blocks each
one.

Each page is served over https (GitHub Pages) so it can be embedded by another
site as an `<iframe src>`. Open `index.html` for the list. Behaviours covered:
top-level navigation, popups, forced downloads, cross-origin form POST, and
content spoofing.

Educational / testing use.
