# Build a Job Application Form


## Description


This project is part of a front-end development lab where you'll practice structuring and styling an interactive web form. The objective is to build a functional and visually appealing **Job Application Form** that fulfills all the user stories and passes all the provided tests. While the functionality should mirror the example project, you’re encouraged to add your own unique design and flair to make it stand out.


## User Stories


1. The page should include a `div` element with the class `container`.

2. Inside the `.container`, there should be a `form` element.

3. The form must include:

   - A `text` input with the `id="name"` for entering the user's full name.

   - An `email` input with the `id="email"` for entering the user's email address.

   - A `select` element with the `id="position"` to choose a job position.

4. A `fieldset` (or `section`) with the class `radio-group` should be present.

   - It must contain radio buttons with the same `name="availability"` for choosing availability (e.g., Full-Time, Part-Time), each with an associated `label`.

5. Include a `textarea` with the `id="message"` for users to enter a message.

6. Add a `submit` button to send the form.


## Styling Requirements


- Use the `:focus` pseudo-class on `input` and `textarea` elements to change their border color when focused.

- Use the `:invalid` pseudo-class to style `input`, `select`, and `textarea` elements with a red border when input is invalid.

- Use the `:valid` pseudo-class to style the same elements with a green border when input is valid.

- Apply the `:hover` pseudo-class to the `button` to change the background color on hover.

- Use the `:checked` pseudo-class to:

  - Style selected radio buttons with custom border, background, and shadow.

  - Change the text color of the corresponding `label` when a radio is selected.

- Use the `:nth-child` pseudo-class to style the first input fields (e.g., rounded corners).


## How to Run


1. Open the `index.html` file in a browser to view the form.

2. Ensure your `styles.css` file is properly linked in the `<head>` section of your HTML.

3. Use the freeCodeCamp test suite to confirm all user stories are implemented and all tests pass.


## Example Project


Use the provided example as a guide for functionality—but don’t copy it. Focus on giving your version a personal and creative touch.


## My Solution


[Live Demo](https://mbahomaid.github.io/freeCodeCamp-labs/2-css/5-job-form/)


Check the [index.html](https://github.com/mbahomaid/freeCodeCamp-labs/blob/main/2-css/5-job-form/index.html) & [styles.css](https://github.com/mbahomaid/freeCodeCamp-labs/blob/main/2-css/5-job-form/styles.css) to see my implementation.

