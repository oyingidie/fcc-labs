## Responsive Web Design

A collection of projects completed while learning HTML and CSS

  - Survey Form
  - Tribute Page
  - Technical Documentation Page
  - Product Landing Page
  - Personal Portfolio Webpage

### :clipboard: Survey Form

**Objective:** Build an app that is functionally similar to https://survey-form.freecodecamp.rocks

**User Stories:**
  - You should have a page title in an `h1` element with an `id` of `title`
  - You should have a short explanation in a `p` element with an `id` of `description`
  - You should have a `form` element with an `id` of `survey-form`
  - Inside the form element, you are required to enter your name in an `input` field that has an `id` of `name` and a `type` of `text`
  - Inside the form element, you are required to enter your email in an `input` field that has an `id` of `email`
  - If you enter an email that is not formatted correctly, you will see an HTML5 validation error
  - Inside the form, you can enter a number in an `input` field that has an `id` of `number`
  - The number input should not accept non-numbers, either by preventing you from typing them or by showing an HTML5 validation error (depending on your browser).
  - If you enter numbers outside the range of the number input, which are defined by the `min` and `max` attributes, you will see an HTML5 validation error
  - For the name, email, and number input fields, you can see corresponding `label` elements in the form, that describe the purpose of each field with the following ids: `id="name-label"`, `id="email-label"`, and `id="number-label"`
  - For the name, email, and number input fields, you can see placeholder text that gives a description or instructions for each field
  - Inside the form element, you should have a `select` dropdown element with an `id` of `dropdown` and at least two options to choose from
  - Inside the form element, you can select an option from a group of at least two radio buttons that are grouped using the `name` attribute
  - Inside the form element, you can select several fields from a series of checkboxes, each of which must have a `value` attribute
  - Inside the form element, you are presented with a `textarea` for additional comments
  - Inside the form element, you are presented with a button with `id` of `submit` to submit all the inputs

### :saluting_face: Tribute Page

**Objective:** Build an app that is functionally similar to https://tribute-page.freecodecamp.rocks

**User Stories:**
  - Your tribute page should have a `main` element with a corresponding `id` of `main`, which contains all other elements
  - You should see an element with an `id` of `title`, which contains a string (i.e. text), that describes the subject of the tribute page (e.g. "Dr. Norman Borlaug")
  - You should see either a `figure` or a `div` element with an `id` of `img-div`
  - Within the `#img-div` element, you should see an img element with a corresponding `id="image"`
  - Within the `#img-div` element, you should see an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `#img-div`
  - You should see an element with a corresponding `id="tribute-info"`, which contains textual content describing the subject of the tribute page
  - You should see an `a` element with a corresponding `id="tribute-link"`, which links to an outside site, that contains additional information about the subject of the tribute page.
  <sub>:bulb: You must give your element an attribute of `target` and set it to `_blank` in order for your link to open in a new tab</sub>
  - Your `#image` should use `max-width` and `height` properties to resize responsively, relative to the width of its parent element, without exceeding its original size
  - Your `img` element should be centered within its parent element
