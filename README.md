# Formula Calculator

Build chained calculations where each row's result becomes a variable for other rows.

[Try it live](https://gatekeeperdev.github.io/formula-calculator/)

## Features

- Add rows of input boxes, each containing a formula
- Each row's output is stored in a named variable (A, B, C, ...)
- Reference variables from other rows in your formulas
- Results update automatically as you type
- Supports standard math operators, built-in functions (`sqrt`, `abs`, `round`, `sin`, `cos`, etc.), and constants (`PI`, `E`)
- Runs entirely in the browser — no server needed

## Usage

1. Click **Add Row** to create a new formula row
2. Type a math expression in the formula input (e.g. `100 * 1.08`)
3. The result appears instantly and is stored in the row's variable
4. Reference that variable in other rows (e.g. `A * 2 + B`)
5. Press **Enter** in a formula input to quickly add another row
