# That's Next Level! — Geometry Transformations

A standalone browser-based version of the Math Medic Geometry Lesson 3.1 flag transformation activity.

## Run

Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari). No installation, build process, account, or internet connection is required.

## Controls

- Arrow buttons or keyboard arrow keys: move one grid square per move.
- Rotate 90° counterclockwise: changes the flag orientation in place.
- Flip vertically: reflection across a vertical axis through the current square (left–right reversal).
- Flip horizontally: reflection across a horizontal axis through the current square (up–down reversal).
- Undo: reverse the last move.
- Reset: return to the starting flag position.
- Copy moves: copy the numbered move sequence.

The grid is 5×5. The flag starts in the bottom-left square. The target is in column 4, row 3, in the same orientation shown on page 1 of the provided worksheet. Both location and orientation must match.

The current game is saved **locally in the browser** (localStorage). It does not collect student names or transmit data to a server. The move count includes each valid shift, 90° rotation, or flip; moves blocked by the grid boundary are not counted.

## Optional hosting

To share with students, upload the files to a static website host (such as GitHub Pages) and share the resulting link. No backend is needed.