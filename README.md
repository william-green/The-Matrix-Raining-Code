# The-Matrix-Raining-Code

The iconic animation from "The Matrix" recreated with JavaScript's Canvas API. A live demo can be found on [Codepen](https://codepen.io/www139/pen/oNvMPER).

# How does it work?

The frame is redrawn at a set rate. On each redraw, the entire canvas is cleared and redrawn. The frame rate is intentionally low to match the lower frame rate in the movie. Characters are randomly changed. Characters are set in columns. Gradients are applied character opacity exponentially. The first character in each column is a brighter green.

# Upcoming Objectives

- Neated up the code (remove unnecessary stuff)
- Increase redraw efficiency by only drawing what is visible
- Improving column positioning