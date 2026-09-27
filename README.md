# Temperature Converter Website

## Objective
A web-based temperature converter built as part of the Oasis Infobyte Web
Development Internship (Level 1, Task 3). The tool converts a temperature
value between Celsius, Fahrenheit, and Kelvin, with input validation and
real-time result display.

## Features
- Numeric input field with validation (rejects non-numeric input)
- Dropdown to select the input unit: Celsius, Fahrenheit, or Kelvin
- Convert button that calculates and displays results in all three units
  simultaneously
- Error handling for invalid input (empty or non-numeric)
- Edge case handling for temperatures below absolute zero (-273.15°C)
- Clean, centered, responsive UI

## Tech Stack
- HTML5
- CSS3
- JavaScript (Vanilla)

## How It Works
1. The user enters a temperature value and selects the unit they entered it in.
2. On clicking "Convert," the script converts the value to Celsius first
   (as a common base), then calculates Fahrenheit and Kelvin from that.
3. If the resulting Celsius value is below -273.15°C, the app shows an error
   instead of a result, since that is physically impossible.
4. All three converted values are displayed at once, each with a clear label.

## Conversion Formulas Used
- Celsius to Fahrenheit: `(C × 9/5) + 32`
- Fahrenheit to Celsius: `(F − 32) × 5/9`
- Celsius to Kelvin: `C + 273.15`

## Files
- `index.html` — Page structure and layout
- `style.css` — Styling and responsive design
- `script.js` — Conversion logic and input validation

## How to Run
Open `index.html` in any web browser. No installation or server required.

## Author
[Your Full Name]
Web Development Track — Oasis Infobyte Internship
