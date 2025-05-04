# Color Full Screen

Display chosen color on fullscreen
    --
## User Interface
A circular control panel contains:
- Color picker (central circular button)
- SET button: enters fullscreen with selected color
- HIDE button: hides the control panel

## Interactions
- Click on color picker to select a color
- Click SET button or anywhere in the control panel (except buttons/picker) to set color and enter fullscreen
- Click HIDE button or outside the control panel to hide controls
- Click anywhere when controls are hidden to show them again
- Buttons appear on mouseover

## Query String
You can set the initial background color using a query string parameter.
Examples:
- index.html?color=ff0000
- index.html?color=%23ffff00
The color can be:
- Hex format with or without # (e.g., ff0000 or #ff0000)
- RGB format (e.g., rgb(255, 0, 0))
- HSL format (e.g., hsl(0, 100%, 50%))
Take care of url encoding of values.