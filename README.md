# Training Academy Website

## Project Description

Training Academy is a simple educational website created using HTML5 and CSS. It contains three web pages that introduce the academy, provide course information, and allow students to fill out a registration form.

## Website Pages

- **index.html:** The home page introduces the academy, displays an image, and lists four courses. It uses inline CSS.
- **information.html:** This page provides course information, a fee table, audio, and video. It uses embedded CSS.
- **registration.html:** This page contains a student registration form with text fields, radio buttons, checkboxes, a dropdown menu, and a text area. It uses external CSS from `style.css`.

## CSS Selectors

CSS selectors identify HTML elements that need styling. The `body` selector is an element selector, `#registration-form` is an ID selector, `.notice` is a class selector, and `input[type="email"]` is an attribute selector. In `color: navy;`, `color` is the property and `navy` is its value. CSS comments identify the required selector types.

## Types of CSS

Inline CSS is written in an HTML element using the `style` attribute. Embedded CSS is written inside a `style` tag in the document head. External CSS is stored in a separate file and connected using a `link` tag. External CSS makes it easier to maintain consistent styling across multiple pages.

## CSS History and Browser Support

CSS1 introduced basic styling. CSS2 and CSS 2.1 added more styling and layout features. Modern CSS uses separate modules for features such as layouts, colors, and responsive design. Browser support can vary, so websites should be tested in different browsers.

I tested the website in Google Chrome and Microsoft Edge to check the page layout and form behavior. Media playback is also be checked in both browsers.

## HTML Elements

Semantic elements such as `header`, `nav`, `main`, `section`, and `footer` describe the purpose of content. Non-semantic elements such as `div` and `span` do not describe their content's meaning by themselves.