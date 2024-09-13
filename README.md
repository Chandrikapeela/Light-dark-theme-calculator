

# Calculator with Light/Dark Theme

This is a simple calculator web application that supports both light and dark themes. It provides basic arithmetic functions and allows users to toggle between themes for a more personalized experience.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- Toggle between light and dark themes.
- Responsive design for mobile and desktop devices.

## Getting Started

### Prerequisites

- A modern web browser (e.g., Google Chrome, Firefox, Safari, Edge).

### Installation

1. **Clone the Repository**

   ```bash
   git clone 
   cd calculator
   ```

2. **Directory Structure**

   - `index.html`: The main HTML file for the calculator.
   - `styles/dark.css`: CSS file for dark theme.
   - `styles/light.css`: CSS file for light theme (create if needed).
   - `scripts/script.js`: JavaScript file containing functionality for the calculator.

3. **Open the Application**

   Open `index.html` in your web browser to view and interact with the calculator.

## Usage

1. **Basic Operations**

   - Click the number buttons to input numbers.
   - Use the arithmetic operator buttons (+, -, *, /) to perform calculations.
   - Click the `=` button to get the result.
   - Click the `C` button to clear the current input.

2. **Theme Toggle**

   - Click the theme icon (moon or sun) to switch between dark and light modes.

## Code Overview

- **HTML**: Defines the structure of the calculator, including the display and buttons.
- **CSS**: Styles the calculator and supports theme switching via external stylesheets.
- **JavaScript**: Handles the logic for button interactions, calculations, and theme toggling.

### JavaScript Functions

- `changeTheme()`: Toggles between light and dark themes.
- `liveScreen(value)`: Updates the display with the input value.
- `calculate(expression)`: Evaluates the expression and displays the result.

## Example

Here's a brief example of how the calculator operates:

1. Click on numbers: `5`, `3`.
2. Click on the operator: `+`.
3. Click on more numbers: `2`, `7`.
4. Click the `=` button to see the result: `60`.

## Contributing

Feel free to fork the repository and submit pull requests with improvements or bug fixes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by various online calculators.
- Fonts provided by Google Fonts.

---

Feel free to modify the content according to your specific project details or preferences.
