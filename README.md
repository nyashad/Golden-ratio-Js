# Golden Ratio Animation

This JavaScript project, powered by p5.js, animates rotating hexagons based on the **Golden Ratio**. The canvas is responsive to window size, and the animation refreshes when clicked or resized.

## Features

- **Golden Ratio Hexagons**: Rotating hexagons scale dynamically based on golden ratio principles.
- **Responsive Design**: The canvas adjusts to fit the window dimensions.
- **Interactive**: Reanimates on mouse click or window resize.

## Setup and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/nyashad/Golden-ratio-Js.git
cd Golden-ratio-Js

## 2. Open in Browser

-To see the animation, simply open the index.html file in a browser.

##3. Adjust the Canvas

    ** Resize: The canvas automatically resizes to fit.
    ** Click: The animation refreshes with the same golden ratio principles.

## Code Overview

    - setup(): Initializes the canvas and prepares the animation environment.
    - draw(): Manages the cyclic animation and draws hexagons.
    - chex(): Creates the hexagons based on trigonometric calculations.
    - drawGrid(): (Optional) Draws a grid when nGrid > 0 is set.
    - mousePressed() and windowResized(): Reinitialize the animation on click or resize.

## Dependencies

- This project uses p5.js. Include it by adding this in your index.html file: