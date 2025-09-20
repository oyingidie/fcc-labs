# Javascript Algorithms & Data Structures

A collection of projects completed while learning Vanilla JavaScript.

- Roman Numeral Converter
- Telephone Number Validator
- Cash Register
- RPG Creature Search App

### :arrows_counterclockwise::thinking: Palindrome Checker

**Objective:** Build an app that is functionally similar to https://palindrome-checker.freecodecamp.rocks

  ><sub>**Hint:** Remove all non-alphanumeric characters (punctuation, spaces, and symbols) and turn everything into the same case (lower or upper case) to check for palindromes.</sub>

**User Stories:**

- You should have an `input` element with an `id` of `"text-input"`
- You should have a `button` element with an `id` of `"check-btn"`
- You should have a `div`, `span` or `p` element with an `id` of `"result"`
- When you click on the `#check-btn` element without entering a value into the `#text-input` element, an alert should appear with the text `"Please input a value"`
- When the `#text-input` element only contains the letter `A` and the `#check-btn` element is clicked, the `#result` element should contain the text `"A is a palindrome"`
- When the `#text-input` element contains the text `eye` and the `#check-btn` element is clicked, the `#result` element should contain the text `"eye is a palindrome"`
- When the `#text-input` element contains the text `_eye` and the `#check-btn` element is clicked, the `#result` element should contain the text `"_eye is a palindrome"`
- When the `#text-input` element contains the text `race car` and the `#check-btn` element is clicked, the `#result` element should contain the text `"race car is a palindrome"`
- When the `#text-input` element contains the text `not a palindrome` and the `#check-btn` element is clicked, the `#result` element should contain the text `"not a palindrome is not a palindrome"`
- When the `#text-input` element contains the text `A man, a plan, a canal. Panama` and the `#check-btn` element is clicked, the `#result` element should contain the text `"A man, a plan, a canal. Panama is a palindrome"`
- When the `#text-input` element contains the text `never odd or even` and the `#check-btn` element is clicked, the `#result` element should contain the text `"never odd or even is a palindrome"`
- When the `#text-input` element contains the text `nope` and the `#check-btn` element is clicked, the `#result` element should contain the text `"nope is not a palindrome"`
- When the `#text-input` element contains the text `almostomla` and the `#check-btn` element is clicked, the `#result` element should contain the text `"almostomla is not a palindrome"`
- When the `#text-input` element contains the text `My age is 0, 0 si ega ym.` and the `#check-btn` element is clicked, the `#result` element should contain the text `"My age is 0, 0 si ega ym. is a palindrome"`
- When the `#text-input` element contains the text `1 eye for of 1 eye.` and the `#check-btn` element is clicked, the `#result` element should contain the text `"1 eye for of 1 eye. is not a palindrome"`
- When the `#text-input` element contains the text `0_0 (: /-\ :) 0-0` and the `#check-btn` element is clicked, the `#result` element should contain the text `"0_0 (: /-\ :) 0-0 is a palindrome"`
- When the `#text-input` element contains the text `five|\_/|four` and the `#check-btn` element is clicked, the `#result` element should contain the text `"five|\_/|four is not a palindrome"`

---

### :classical_building::1234: Roman Numeral Converter

Roman numerals are based on seven symbols and can be written using various combinations to represent Arabic numerals. For example:

|Roman numerals|Arabic numerals|
|:------------:|:-------------:|
| M            |          1000 |
| CM           |           900 |
| D            |           500 |
| CD           |           400 |
| C            |           100 |
| XC           |            90 |
| L            |            50 |
| XL           |            40 |
| X            |            10 |
| IX           |             9 |
| V            |             5 |
| IV           |             4 |
| I            |             1 |

**Objective:** Build an app that is functionally similar to https://roman-numeral-converter.freecodecamp.rocks

**User Stories:**

- You should have an `input` element with an `id` of `"number"`
- You should have a `button` element with an `id` of `"convert-btn"`
- You should have a `div`, `span` or `p` element with an `id` of `output`
- When you click on the `#convert-btn` element without entering a value into the `#number` element, the `#output` element should contain the text `"Please enter a valid number"`
- When the `#number` element contains the number `-1` and the `#convert-btn` element is clicked, the `#output` element should contain the text `"Please enter a number greater than or equal to 1"`
- When the `#number` element contains the number `4000` or greater and the `#convert-btn` element is clicked, the #output element should contain the text `"Please enter a number less than or equal to 3999"`
- When the `#number` element contains the number `9` and the `#convert-btn` element is clicked, the #output element should contain the text `"IX"`
- When the `#number` element contains the number `16` and the `#convert-btn` element is clicked, the #output element should contain the text `"XVI"`
- When the `#number` element contains the number `649` and the `#convert-btn` element is clicked, the #output element should contain the text `"DCXLIX"`
- When the `#number` element contains the number `1023` and the `#convert-btn` element is clicked, the #output element should contain the text `"MXXIII"`
- When the `#number` element contains the number `3999` and the `#convert-btn` element is clicked, the #output element should contain the text `"MMMCMXCIX"`

---

