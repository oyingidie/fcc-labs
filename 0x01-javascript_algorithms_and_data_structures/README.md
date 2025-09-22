# Javascript Algorithms & Data Structures

A collection of projects completed while learning Vanilla JS and algorithmic thinking.

### 00. :arrows_counterclockwise::thinking: Palindrome Checker

**Objective:** Build an app that is functionally similar to https://palindrome-checker.freecodecamp.rocks

> <sub>**Hint:** Remove all non-alphanumeric characters (punctuation, spaces, and symbols) and turn everything into the same case (lower or upper case) to check for palindromes.</sub>

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

### 01. :classical_building::1234: Roman Numeral Converter

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

### 02. :mag::iphone: Telephone Number Validator

**Objective:** Build an app that is functionally similar to https://telephone-number-validator.freecodecamp.rocks

> <sub>**Hint:** The area code is required. If the country code is also provided, you must confirm that it is 1.</sub>

**User Stories:**

- You should have an `input` element with an `id` of `"user-input"`
- You should have a `button` element with an `id` of `"check-btn"`
- You should have a `button` element with an `id` of `"clear-btn"`
- You should have a `div`, `span` or `p` element with an `id` of `"results-div"`
- When you click on the `#check-btn` element without entering a value into the `#user-input` element, an alert should appear with the text `"Please provide a phone number"`
- When you click on the `#clear-btn` element, the content within the `#results-div` element should be removed
- When the `#user-input` element contains `1 555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 1 555-555-5555"`
- When the `#user-input` element contains `1 (555) 555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 1 (555) 555-5555"`
- When the `#user-input` element contains `5555555555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 5555555555"`
- When the `#user-input` element contains `555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 555-555-5555"`
- When the `#user-input` element contains `(555)555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: (555)555-5555"`
- When the `#user-input` element contains `1(555)555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 1(555)555-5555"`
- When the `#user-input` element contains `555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 555-5555"`
- When the `#user-input` element contains `5555555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 5555555"`
- When the `#user-input` element contains `1 555)555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 1 555)555-5555"`
- When the `#user-input` element contains `1 555 555 5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 1 555 555 5555"`
- When the `#user-input` element contains `1 456 789 4444` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: 1 456 789 4444"`
- When `#user-input` contains `123**&!!asdf#` and `#check-btn` is clicked, `#results-div` should contain the text `"Invalid US number: 123**&!!asdf#"`
- When the `#user-input` element contains `55555555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 55555555"`
- When the `#user-input` element contains `(6054756961)` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: (6054756961)"`
- When the `#user-input` element contains `2 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 2 (757) 622-7382"`
- When the `#user-input` element contains `0 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 0 (757) 622-7382"`
- When the `#user-input` element contains `-1 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: -1 (757) 622-7382"`
- When the `#user-input` element contains `2 757 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 2 757 622-7382"`
- When the `#user-input` element contains `10 (757) 622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 10 (757) 622-7382"`
- When the `#user-input` element contains `27576227382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 27576227382"`
- When the `#user-input` element contains `(275)76227382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: (275)76227382"`
- When the `#user-input` element contains `2(757)6227382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 2(757)6227382"`
- When the `#user-input` element contains `2(757)622-7382` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 2(757)622-7382"`
- When the `#user-input` element contains `555)-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 555)-555-5555"`
- When the `#user-input` element contains `(555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: (555-555-5555"`
- When `#user-input` contains `(555)5(55?)-5555` and `#check-btn` is clicked, `#results-div` should contain the text `"Invalid US number: (555)5(55?)-5555"`
- When the `#user-input` element contains `55 55-55-555-5` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 55 55-55-555-5"`
- When the `#user-input` element contains `11 555-555-5555` and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: 11 555-555-5555"`
- When the `#user-input` element contains a valid US number and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Valid US number: "` followed by the number
- When the `#user-input` element contains an invalid US number and the `#check-btn` element is clicked, the `#results-div` element should contain the text `"Invalid US number: "` followed by the number

---

### 03. :moneybag::receipt: Cash Register

Here you'll build a cash register app that will return change to the customer based on the price of the item, the amount of cash provided by the customer, and the amount of cash in the cash drawer. You'll also need to show different messages to the user in different scenarios, such as when the customer provides too little cash or when the cash drawer doesn't have enough to issue the correct change.

> <sub>**Hint:** Your application should show different messages depending on the price of the item, the amount of cash provided by the customer, and the amount of cash in the drawer:</sub>
>
> - <sub>`"Status: INSUFFICIENT_FUNDS"`: if `cash-in-drawer` is less than the change due, or if you cannot return the exact change.
> - <sub>`"Status: CLOSED"`: if `cash-in-drawer` is equal to the change due.
> - <sub>`"Status: OPEN"`: if `cash-in-drawer` is greater than the change due and you can return change, with the change due in coins and bills sorted in highest to lowest order.</sub>

<br>

|Currency Unit      |            Amount|
|:-----------------:|:----------------:|
|Penny              |     $0.01 (PENNY)|
|Nickel             |    $0.05 (NICKEL)|
|Dime               |       $0.1 (DIME)|
|Quarter            |   $0.25 (QUARTER)|
|Dollar             |          $1 (ONE)|
|Five Dollars       |         $5 (FIVE)|
|Ten Dollars        |         $10 (TEN)|
|Twenty Dollars     |      $20 (TWENTY)|
|One Hundred Dollars|$100 (ONE HUNDRED)|

**Objective:** Build an app that is functionally similar to https://cash-register.freecodecamp.rocks

**User Stories:**

- You should have an `input` element with an `id` of `"cash"`
- You should have a `div`, `span` or `p` element with an `id` of `"change-due"`
- You should have a `button` element with an `id` of `"purchase-btn"`
- When the value in the `#cash` element is less than `price`, an alert should appear with the text `"Customer does not have enough money to purchase the item"`
- When the value in the `#cash` element is equal to `price`, the value in the `#change-due` element should be `"No change due - customer paid with exact cash"`
- When `price` is `19.5`, the value in the `#cash` element is `20`, `cid` is `[["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be "Status: OPEN QUARTER: $0.5"
- When `price` is `3.26`, the value in the #cash element is 100, `cid` is `[["PENNY", 1.01], ["NICKEL", 2.05], ["DIME", 3.1], ["QUARTER", 4.25], ["ONE", 90], ["FIVE", 55], ["TEN", 20], ["TWENTY", 60], ["ONE HUNDRED", 100]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: OPEN TWENTY: $60 TEN: $20 FIVE: $15 ONE: $1 QUARTER: $0.5 DIME: $0.2 PENNY: $0.04"`
- When `price` is `19.5`, the value in the #cash element is `20`, `cid` is `[["PENNY", 0.01], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: INSUFFICIENT_FUNDS"`
- When `price` is `19.5`, the value in the `#cash` element is `20`, `cid` is `[["PENNY", 0.01], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 1], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: INSUFFICIENT_FUNDS"`
- When `price` is `19.5`, the value in the `#cash` element is `20`, `cid` is `[["PENNY", 0.5], ["NICKEL", 0], ["DIME", 0], ["QUARTER", 0], ["ONE", 0], ["FIVE", 0], ["TEN", 0], ["TWENTY", 0], ["ONE HUNDRED", 0]]`, and the `#purchase-btn` element is clicked, the value in the `#change-due` element should be `"Status: CLOSED PENNY: $0.5"`

---

### 04. :unicorn::video_game: RPG Creature Search App

In this project, you'll build an app that will search for creatures from an RPG game by name or ID and display the results to the user. To retrieve the creature data and images, you'll use freeCodeCamp's [RPG Creature API](https://rpg-creature-api.freecodecamp.rocks/).

**Objective:** Build an app that is functionally similar to https://rpg-creature-search-app.freecodecamp.rocks

**User Stories:**

- You should have an `input` element with an `id` of `"search-input"`, and is required
- You should have a `button` element with an `id` of `"search-button"`
- You should have an element with an `id` of `"creature-name"`
- You should have an element with an `id` of `"creature-id"`
- You should have an element with an `id` of `"weight"`
- You should have an element with an `id` of `"height"`
- You should have an element with an `id` of `"types"`
- You should have an element with an `id` of `"hp"`
- You should have an element with an `id` of `"attack"`
- You should have an element with an `id` of `"defense"`
- You should have an element with an `id` of `"special-attack"`
- You should have an element with an `id` of `"special-defense"`
- You should have an element with an `id` of `"speed"`
- When the `#search-input` element contains the value `Red` and the `#search-button` element is clicked, an alert should appear with the text `"Creature not found"`
- When the `#search-input` element contains the value `Pyrolynx` and the `#search-button` element is clicked, the values in the `#creature-name`, `#creature-id`, `#weight`, `#height`, `#hp`, `#attack`, `#defense`, `#special-attack`, `#special-defense`, and `#speed` elements should be `PYROLYNX`, `#1` or `1`, `Weight: 42` or `42`, `Height: 32` or `32`, `65`, `80`, `50`, `90`, `55`, and `100`, respectively
- When the `#search-input` element contains the value `Pyrolynx` and the #search-button element is clicked, a single element should be added within the `#types` element that contains the text `FIRE`. The `#types` element content should be cleared between searches
- When the `#search-input` element contains the value `2` and the `#search-button` element is clicked, the values in the `#creature-name`, `#creature-id`, `#weight`, `#height`, `#hp`, `#attack`, `#defense`, `#special-attack`, `#special-defense`, and `#speed` elements should be `AQUOROC`, `#2` or `2`, `Weight: 220` or `220`, `Height: 53` or `53`, `85`, `90`, `120`, `60`, `70`, and `40`, respectively
- When the `#search-input` element contains the value `2` and the `#search-button` element is clicked, two elements should be added within the `#types` element that contain text values `WATER` and `ROCK`, respectively. The `#types` element content should be cleared between searches
- When the `#search-input` element contains an invalid creature name, and the `#search-button` element is clicked, an alert should appear with the text `"Creature not found"`
- When the `#search-input` element contains a valid creature ID and the `#search-button` element is clicked, the UI should be filled with the correct data
