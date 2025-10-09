# Front-End Development Libraries

A collection of projects completed while learning some popular front-end frameworks and libraries.

> #### :information_source: Info
> Use whichever libraries or APIs you need.<br>
> You can use any mix of HTML, JavaScript, CSS, Bootstrap, SASS, React, Redux, and jQuery.
>
> To run the test cases, put this `<script>` tag into the body of your `.html` file: `<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>`.

### 00. :brain::speech_balloon: Random Quote Machine

**Objective:** Build an app that is functionally similar to this: https://random-quote-machine.freecodecamp.rocks/

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

**Objective:** Build an app that is functionally similar to this: https://markdown-previewer.freecodecamp.rocks/

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

**Objective:** Build an app that is functionally similar to this: https://drum-machine.freecodecamp.rocks/

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
> [Heater 1](https://cdn.freecodecamp.org/testable-projects-fcc/audio/Heater-1.mp3)
> [Heater 2]()
> [Heater 3]()
> [Heater 4]()
> [Clap]()
> [Open-HH]()
> [Kick-n'-Hat]()
> [Kick]()
> [Closed-HH]()

---

### 03. :1234::abacus: Simple Calculator

---

### 04. :tomato::timer_clock: Pomodoro Clock

