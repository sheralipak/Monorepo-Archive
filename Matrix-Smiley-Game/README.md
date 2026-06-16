```markdown
# 🎮 2D Matrix Smiley Game

A C++ console-based game built as a programming project. The game initializes a grid environment where a player asset (smiley) navigates from the starting coordinates (0, 0) toward a target destination at (9, 9) based on randomized input logic and boundary constraints.

## 📋 Game Rules & Movement Logic
* **Randomized Inputs:** The game simulates steps using `rand() % 7` to determine spatial adjustments.
* **Horizontal Adjustments:** Inputs of `1` or `2` shift the asset columns forward horizontally].
* **Vertical Adjustments:** Inputs of `4` or `5` shift the asset rows downward vertically.
* **Diagonal Shifts:** An input of `6` moves the asset diagonally by 2 units (`row + 2`, `col + 2`).
* **Consecutive Rule:** Two consecutive `6` inputs cancel out the movement to prevent boundary overruns.
* **Victory Condition:** Successfully guiding the asset to the final array slot at index `[9][9]`.

## 🛠️ Concepts Demonstrated
* 2D Array Matrix Manipulations (`char arr[10][10]`)
* Pass-by-reference state management (`int& row`, `int& col`)
* Randomized control flow logic and boundary validation constraints
