# Front-End Development Libraries

A collection of projects completed while learning some popular front-end frameworks and libraries.

> #### :information_source: Info
> Use whichever libraries or APIs you need.<br>
> You can use any mix of HTML, JavaScript, CSS, Bootstrap, SASS, React, Redux, and jQuery.
>
> To run the test cases, put this `<script>` tag into the body of your `.html` file: `<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>`.

### 00. :brain::speech_balloon: Random Quote Machine

**Objective:** Build an app that is functionally similar to [this](https://random-quote-machine.freecodecamp.rocks/).

**User Stories:**

- I can see a wrapper element with a corresponding `id="quote-box"`
- Within `#quote-box`, I can see an element with a corresponding `id="text"`
- Within `#quote-box`, I can see an element with a corresponding `id="author"`
- Within `#quote-box`, I can see a clickable element with a corresponding `id="new-quote"`
- Within `#quote-box`, I can see a clickable a element with a corresponding `id="tweet-quote"`
- On first load, my quote machine displays a random quote in the element with `id="text"`
- On first load, my quote machine displays the random quote's author in the element with `id="author"`
- When the `#new-quote` button is clicked, my quote machine should fetch a new quote and display it in the `#text` element.
- My quote machine should fetch the new quote's author when the `#new-quote` button is clicked and display it in the `#author` element.
- I can tweet the current quote by clicking on the `#tweet-quote` `a` element. This `a` element should include the `"twitter.com/intent/tweet"` path in its `href` attribute to tweet the current quote.
- The `#quote-box` wrapper element should be horizontally centered. Please run tests with browser's zoom level at 100% and page maximized.

> <sub>**Note:** Twitter does not allow links to be loaded in an iframe. Try using the `target="_blank"` or `target="_top"` attribute on the `#tweet-quote` element if your tweet won't load. `target="_top"` will replace the current tab so make sure your work is saved.</sub>

---

### 01. :computer::framed_picture: Markdown Previewer

**Objective:** Build an app that is functionally similar to [this](https://markdown-previewer.freecodecamp.rocks/).

**User Stories:**

- I can see a `textarea` element with a corresponding `id="editor"`
- I can see an element with a corresponding `id="preview"`
- When I enter text into the `#editor` element, the `#preview` element is updated as I type to display the content of the textarea
- When I enter GitHub flavored markdown into the `#editor` element, the text is rendered as HTML in the `#preview` element as I type

    > <sub>**Hint:** You don't need to parse Markdown yourself - you can import the Marked library for this: https://cdnjs.com/libraries/marked</sub>

- When my markdown previewer first loads, the default text in the `#editor` field should contain valid markdown that represents at least one of each of the following elements: a heading element (H1 size), a sub heading element (H2 size), a link, inline code, a code block, a list item, a blockquote, an image, and bolded text
- When my markdown previewer first loads, the default markdown in the `#editor` field should be rendered as HTML in the `#preview` element

> <sub>**Optional Bonus (you do not need to make this test pass):** My markdown previewer interprets carriage returns and renders them as `br` (line break) elements.</sub>

---

### 02. :drum::control_knobs: Drum Machine

**Objective:** Build an app that is functionally similar to [this](https://drum-machine.freecodecamp.rocks/).

**User Stories:**

- I should be able to see an outer container with a corresponding id="drum-machine" that contains all other elements.
- Within #drum-machine I can see an element with a corresponding id="display".
- Within #drum-machine I can see 9 clickable drum pad elements, each with a class name of drum-pad, a unique id that describes the audio clip the drum pad will be set up to trigger, and an inner text that corresponds to one of the following keys on the keyboard: Q, W, E, A, S, D, Z, X, C. The drum pads MUST be in this order.
- Within each .drum-pad, there should be an HTML5 audio element which has a src attribute pointing to an audio clip, a class name of clip, and an id corresponding to the inner text of its parent .drum-pad (e.g. id="Q", id="W", id="E" etc.).
- When I click on a .drum-pad element, the audio clip contained in its child audio element should be triggered.
- When I press the trigger key associated with each .drum-pad, the audio clip contained in its child audio element should be triggered (e.g. pressing the Q key should trigger the drum pad which contains the string Q, pressing the W key should trigger the drum pad which contains the string W, etc.).
- When a .drum-pad is triggered, a string describing the associated audio clip is displayed as the inner text of the #display element (each string must be unique).

> Here are some audio samples you can use for your drum machine:
> 
> [Heater 1](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Heater-1.mp3), [Heater 2](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Heater-2.mp3), [Heater 3](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Heater-3.mp3), [Heater 4](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Heater-4_1.mp3), [Clap](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Heater-6.mp3), [Open-HH](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Dsc_Oh.mp3), [Kick-n'-Hat](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Kick_n_Hat.mp3), [Kick](https://cdn.freecodecamp.org/testable-projects-fcc/audio/RP4_KICK_1.mp3), [Closed-HH](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Cev_H2.mp3)

---

### 03. :1234::abacus: Simple Calculator

Objective: Build an app that is functionally similar to [this](https://javascript-calculator.freecodecamp.rocks/).

Fulfill the below user stories and get all of the tests to pass. Use whichever libraries or APIs you need. Give it your own personal style.

You can use any mix of HTML, JavaScript, CSS, Bootstrap, SASS, React, Redux, and jQuery to complete this project. You should use a frontend framework (like React for example) because this section is about learning frontend frameworks. Additional technologies not listed above are not recommended and using them is at your own risk. We are looking at supporting other frontend frameworks like Angular and Vue, but they are not currently supported. We will accept and try to fix all issue reports that use the suggested technology stack for this project. Happy coding!

User Story #1: My calculator should contain a clickable element containing an = (equal sign) with a corresponding id="equals".

User Story #2: My calculator should contain 10 clickable elements containing one number each from 0-9, with the following corresponding IDs: id="zero", id="one", id="two", id="three", id="four", id="five", id="six", id="seven", id="eight", and id="nine".

User Story #3: My calculator should contain 4 clickable elements each containing one of the 4 primary mathematical operators with the following corresponding IDs: id="add", id="subtract", id="multiply", id="divide".

User Story #4: My calculator should contain a clickable element containing a . (decimal point) symbol with a corresponding id="decimal".

User Story #5: My calculator should contain a clickable element with an id="clear".

User Story #6: My calculator should contain an element to display values with a corresponding id="display".

User Story #7: At any time, pressing the clear button clears the input and output values, and returns the calculator to its initialized state; 0 should be shown in the element with the id of display.

User Story #8: As I input numbers, I should be able to see my input in the element with the id of display.

User Story #9: In any order, I should be able to add, subtract, multiply and divide a chain of numbers of any length, and when I hit =, the correct result should be shown in the element with the id of display.

User Story #10: When inputting numbers, my calculator should not allow a number to begin with multiple zeros.

User Story #11: When the decimal element is clicked, a . should append to the currently displayed value; two . in one number should not be accepted.

User Story #12: I should be able to perform any operation (+, -, *, /) on numbers containing decimal points.

User Story #13: If 2 or more operators are entered consecutively, the operation performed should be the last operator entered (excluding the negative (-) sign). For example, if 5 + * 7 = is entered, the result should be 35 (i.e. 5 * 7); if 5 * - 5 = is entered, the result should be -25 (i.e. 5 * (-5)).

User Story #14: Pressing an operator immediately following = should start a new calculation that operates on the result of the previous evaluation.

User Story #15: My calculator should have several decimal places of precision when it comes to rounding (note that there is no exact standard, but you should be able to handle calculations like 2 / 7 with reasonable precision to at least 4 decimal places).

Note On Calculator Logic: It should be noted that there are two main schools of thought on calculator input logic: immediate execution logic and formula logic. Our example utilizes formula logic and observes order of operation precedence, immediate execution does not. Either is acceptable, but please note that depending on which you choose, your calculator may yield different results than ours for certain equations (see below example). As long as your math can be verified by another production calculator, please do not consider this a bug.

---

### 04. :tomato::timer_clock: Pomodoro Clock

