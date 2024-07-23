# Digit Challenge

This repository contains a webpage for solving equations with unique numbers that satisfy the equation. It ensures that the numbers in the solution are unique and adhere to specified constraints.

## Usage

### Equation Format

- The equation should be in the form `a + b = X` where `a`, `b`, `c`, and `d` can be used as variables.
- At least two variables (`a` and `b`) are mandatory.
- You can use up to four variables: `a`, `b`, `c`, and `d`.
- Ensure that the equation follows standard mathematical operations.

### Examples

- For the equation `a + b = 3`, a valid solution is `a = 2` and `b = 1`.
- For the equation `a + b = 4`, a solution like `a = 2` and `b = 2` is invalid because `a` and `b` must be unique. Valid solutions include `a = 3, b = 1` or `a = 1, b = 3`.

### Input Constraints

- The input equation should be entered in the specified format.
- Variables other than `a`, `b`, `c`, and `d` will result in an error.

## Webpage Usage

1. **Insert Equation**: In the text box provided, enter your equation.
2. **Submit**: Click the submit button to find the unique solutions.
3. **View Results**: The webpage will display all unique solutions that satisfy the equation.

## Example Usage

1. Open the webpage.
2. Enter `a + b = 4` in the equation text box.
3. Click on the submit button.
4. View the solutions, which will exclude any where `a` and `b` are equal.

## Development

The function uses JavaScript's `eval` function for evaluating the mathematical expressions. Ensure that the input adheres to standard mathematical syntax and the allowed variables (`a`, `b`, `c`, `d`).

### Note

- Always use the variables `a`, `b`, `c`, and `d`.
- Make sure to follow mathematical conventions to avoid errors.

## Authors

- **Praveen Murugan** - *Initial work* - [praveenm09081999](https://github.com/praveenm09081999/)

