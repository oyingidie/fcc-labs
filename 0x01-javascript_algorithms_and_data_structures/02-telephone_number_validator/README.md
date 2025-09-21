## US Phone Number Validator

### :book: Overview

A lightweight web app that checks if a given input is a valid US phone number. Built with Vanilla JavaScript, it ensures formatting rules are followed and gives instant feedback.

### :sparkles: Features

- Validates phone numbers based on multiple US formats
- Support for quick checking by pressing the Enter key
- Clear button to reset results 

### :hammer_and_wrench: Technologies Used

- **HTML5** for page structure
- **CSS3** for styling and responsive layout
- **Google Fonts** for typography
- **JavaScript (Vanilla)** for validation logic and interactivity

### :file_folder: Project Structure

```
fcc-labs/
|-- ...
|-- 0x01-javascript_algorithms_and_data_structures/
|    |-- ...
|    |-- 02-telephone_number_validator/
|    |    |-- us_number_validator.html
|    |    |-- us_number_validator.css
|    |    |-- us_number_validator.js
|    |    |-- README.md (this document)
|    |-- ...
|    |-- README.md
|-- ...
```

### :rocket: Live Demo

View on [CodePen](https://codepen.io/oyingidie/full/RNNvQvm)

> ##### :zap: How It Works
>
> 1. User enters a phone number
> 2. App tests input against a regex pattern:
>
>      - Allows optional country code `1`
>      - Accepts area codes in `()` or plain digits
>      - Supports dashes `-` or spaces as separators
> 
> 4. Uses a conversion chart (M, CM, D, CD, C, XC, L, XL, X, IX, V, IV, I) to build the Roman numeral
> 5. Displays result instantly

### :recycle: Potential Enhancements

- Implement a parsing algorithm to support reverse conversion from Roman numerals to integers
- Add animations to provide immediate visual feedback for invalid user inputs
- Develop a UI toggle to dynamically switch between light and dark themes

### :paintbrush: Author

Designed by **Oyinkansola Nuel Adebayo**
