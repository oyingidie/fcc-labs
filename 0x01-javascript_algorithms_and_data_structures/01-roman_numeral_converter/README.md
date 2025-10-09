## Roman Numeral Checker

### :book: Overview

A simple, interactive web app that converts numbers (1–3999) into their Roman numeral equivalents. Built with Vanilla JavaScript, it validates input and ensures results align with traditional Roman numeral rules.

### :sparkles: Features

- Input validation for out-of-range or invalid values
- Support for quick checking by pressing the Enter key
- Clear and responsive result display

### :hammer_and_wrench: Technologies Used

- **HTML5** for page structure
- **CSS3** for styling and responsive layout
- **JavaScript (Vanilla)** for core conversion logic and interactivity

### :file_folder: Project Structure

```
fcc-labs/
|-- ...
|-- 0x01-javascript_algorithms_and_data_structures/
|    |-- ...
|    |-- 01-roman_numeral_converter/
|    |    |-- roman_numeral.html
|    |    |-- roman_numeral.css
|    |    |-- roman_numeral.js
|    |    |-- README.md (this document)
|    |-- ...
|    |-- README.md
|-- ...
```

### :rocket: Live Demo

View on [CodePen](https://codepen.io/oyingidie/full/EaYoeJL)

> #### :zap: How It Works
>
> 1. User enters a number
> 2. App checks for validity (i.e. non-empty, ≥1, ≤3999)
> 3. Uses a conversion chart (M, CM, D, CD, C, XC, L, XL, X, IX, V, IV, I) to build the Roman numeral
> 4. Displays result instantly

### :recycle: Potential Enhancements

- Implement a parsing algorithm to support reverse conversion from Roman numerals to integers
- Add animations to provide immediate visual feedback for invalid user inputs
- Develop a UI toggle to dynamically switch between light and dark themes

### :paintbrush: Author

Designed by **Oyinkansola Nuel Adebayo**
