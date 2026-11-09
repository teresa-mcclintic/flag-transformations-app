# That's Next Level! — Geometry Transformations

An interactive browser game based on the flag transformation activity in Math Medic Geometry Lesson 3.1.

## Play

**Live game:** https://teresa-mcclintic.github.io/flag-transformations-app/

The app is a standalone `index.html` with no build step or student login.

## Five levels

Each challenge starts in the bottom-left square of a 5 × 5 grid. Match both the position and the orientation of the target flag. A level unlocks the next one when solved.

- Move one square with the labeled direction pad or arrow keys.
- Rotate 90° counterclockwise, reflect across a vertical line, or reflect across a horizontal line.
- Undo, Reset, and Copy moves.
- Separate counts for shifts, transformations, and total moves.

## New features

### Minimum moves and personal best

After completing a level, students see their own number of moves, the **fewest possible moves**, and their **personal best** for that level. The fewest moves are computed from the start to the target based on the allowed moves and flag orientations. The minimum is revealed **after** the level is solved so the challenge remains open-ended.

Personal best scores are saved to the browser using `localStorage`. Replaying a level can improve a student's best score.

### Create Your Own Level

Select **Create Your Own Level**, click a grid square to position the target, and use the target-specific rotation and reflection buttons to choose its orientation.

The app computes the shortest solution for the designed target and requires **at least 7 moves** before permitting the challenge to begin.

Use **Copy challenge link** to send the designed challenge to a partner. Opening that link loads the target as a playable custom challenge, requiring no login or backend. Students can also swap the same device and use **Play this challenge**.

A distinct personal-best record is kept for each custom target configuration.

## Notes for teachers

- Completion and best-score records are stored on each browser/device, not collected by the teacher.
- Clearing site data may erase progress.
- A custom challenge link contains only the target coordinates and orientation; it contains no student information.
- This version is an independent interactive adaptation, not an official Math Medic product.
