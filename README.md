# fumen-canvas
A basic command-line utility for rendering fumens as png/gif images in the style of [four.lol](https://four.lol/). Written using Knewjade's [tetris-fumen](https://github.com/knewjade/tetris-fumen).

<p align="center">
  <img width="440" height="220" src="pc.gif">
</p>

## Usage
Rendering single fumen page to png
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

### Example Usage
```
node fumen-canvas.js gif v115@vhKyOJDkBmfBksB9tBHjBplBNrBkmBHsBAAA pc.gif
```
