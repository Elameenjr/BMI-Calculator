# BMI Calculator

> A small static Body Mass Index (BMI) calculator built with HTML, CSS and JavaScript.

This repository contains a tiny web page that computes BMI from height (cm) and weight (kg) and displays a simple weight classification.

## Files
- `index.html` — UI for inputs and result
- `style.css` — styles for the page
- `script.js` — BMI calculation and DOM wiring

## Run locally
You can open `index.html` directly in a browser, or serve the folder with a simple HTTP server (recommended):

```bash
# from the project root
python3 -m http.server 8000
# then open http://localhost:8000
```

## Usage
1. Enter height in centimeters and weight in kilograms.
2. Click the "Compute BMI" button.
3. The BMI (rounded to 2 decimals) and a weight condition will be displayed.

## Notes
- Inputs are validated for positive numeric values.
- This is a simple demo — medical decisions should not be made from this app alone.

## License
This project is provided under the MIT License — feel free to reuse and modify.
