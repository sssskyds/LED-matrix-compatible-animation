
# Tkinter Pixel Grid

This Python script creates a grid of rectangular(version1) & circular (version2)  pixels using the Tkinter library. Each pixel in the grid is represented as a circle.

## Usage Example
create_pixel_grid(rows=128, cols=64, pixel_size=10)
This will create a grid with 128 rows and 64 columns, where each pixel is a circle with a diameter of 10 pixels.

## Functionality
The create_pixel_grid function creates a new Tkinter window, calculates the total size of the grid based on the provided number of rows and columns and the size of each pixel, and creates a canvas to display the grid.

It then iterates over the grid, creating a circular pixel at each position. The `create_oval` function is used to draw the circles. When the width and height of the oval are equal, it becomes a circle.

The grid is displayed in the Tkinter window when the script is run.

## Requirements
This script requires Python 3 and the Tkinter library.
