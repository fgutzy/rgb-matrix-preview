# RGB Matrix Preview

A simple browser-based preview tool for RGB LED matrix displays.

This tool lets you quickly test how much text fits on a matrix display without having to repeatedly upload firmware, flash a device, or physically test on hardware.

<img width="1450" height="814" alt="image" src="https://github.com/user-attachments/assets/8ef8a479-28c3-420f-8f84-8039ea2c75c1" />


## Features

* Adjustable matrix dimensions (width and height in pixels)
* Configurable zoom level
* Custom LED and background colors
* Multi-line text preview
* Horizontal alignment (left, center, right)
* Vertical alignment (top, center, bottom)
* Adjustable line spacing
* Text scrolling simulation
* Live statistics showing:

  * Number of lines
  * Maximum lines that fit
  * Approximate characters per line
  * Current matrix resolution

## Use Case

When developing projects for RGB LED matrix displays, it is often difficult to estimate:

* How many characters fit on a display
* How many lines fit vertically
* Whether text layouts will overflow
* How scrolling text will appear

This tool provides an instant visual preview directly in the browser, making it easier to design display content before deploying it to hardware.

## Getting Started

1. Open [matrixdisplay.ink](https://matrixdisplay.ink)

   OR
1. Download/clone the repository.
2. Open `index.html` in a modern web browser.
3. Adjust the matrix dimensions to match your display.
4. Enter your text.
5. Experiment with alignment, colors, spacing, and scrolling.

No installation or build process is required.

# Lowercase letters

Line spacing might look off, as its calculated on the lowest possible point of any letters (i.e. q goes below the "normal" line), even if theyre not used in the text. 

## Technical Notes

* Uses a built-in 5-pixel-high bitmap font.
* Implemented as a single self-contained HTML file.
* No dependencies.
* No backend required.

## Attribution

The code for this project was generated with assistance from Claude AI and subsequently adapted for this use case.
