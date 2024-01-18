# jhilimili


# README.md

## Description

This HTML file creates a simple interactive webpage with a grid of four cells that change colors randomly when a button is clicked.

## Key Features

- **Interactive Buttons:** Two buttons allow users to trigger the color change effect.
- **Table Structure:** A simple HTML table organizes the cells.
- **CSS Styling:** Basic CSS styles the cells to create a grid-like appearance.
- **JavaScript Function:** A JavaScript function named `change()` handles the color change logic.

## Functionality

1. **Initial State:**
   - The page loads with four empty cells, each with a 1px border.
   - The `change()` function is called to set initial random colors.
2. **Button Click:**
   - Clicking either "Change the style" button invokes the `change()` function.
3. **Color Change:**
   - The function:
     - Assigns an array of colors (`red`, `blue`, `yellow`, `green`).
     - Retrieves references to the individual cell elements.
     - Iterates through the cells:
       - Generates a random index between 0 and 3.
       - Assigns a random color from the array to the cell's background color.

## File Structure

- `index.html` (or any preferred filename)

## Usage

1. Open the HTML file in a web browser.
2. Click either button to change the cell colors randomly.
