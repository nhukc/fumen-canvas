# fumen-canvas

## Usage
Rendering single page to png
```
fumen-canvas.js image <fumen> <output file>

Renders page of fumen into a png.

Options:
  --version      Show version number                                   [boolean]
  --help         Show help                                             [boolean]
  --page         Render a specific page of the fumen.      [number] [default: 0]
  --height       Number of rows to render starting at the bottom.       [number]
  --transparent  Make empty squares transparent.                       [boolean]                                       [boolean]
```
Rendering full fumen to gif
```
fumen-canvas.js gif <fumen> <output file>

Renders fumen into a gif.

Options:
  --version      Show version number                                   [boolean]
  --help         Show help                                             [boolean]
  --start        Specify index of first page to be rendered.
                                                           [number] [default: 0]
  --end          Specify index at which to stop rendering.              [number]
  --height       Number of rows to render starting at the bottom.       [number]
  --transparent  Make empty squares transparent.                       [boolean]
```
