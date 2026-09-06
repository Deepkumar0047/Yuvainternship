# Week 3 Task: Integrating JavaScript for Interactive User Experience

## 1. Introduction

The objective of this project was to enhance a static webpage by integrating JavaScript and implementing interactive features. HTML was used to define the webpage structure, CSS was used to create a clean and responsive user interface, and JavaScript was used to add dynamic behavior.

The main purpose of this task was to understand DOM manipulation, event handling, form validation, CSS class manipulation, and responsive user interactions using plain JavaScript without external JavaScript libraries.

## 2. Technologies Used

* HTML5
* CSS3
* JavaScript
* DOM Manipulation
* Event Handling
* Responsive Design

## 3. Interactive Features Implemented

### 3.1 Mobile Navigation Menu

A responsive navigation menu was implemented using JavaScript. On smaller screens, the navigation links are hidden and a menu button is displayed. When the user clicks the menu button, JavaScript adds or removes the `active` CSS class.

The menu icon also changes between the hamburger symbol and the close symbol.

### 3.2 Dark Mode

A dark mode feature was added to improve the user experience. When the theme button is clicked, JavaScript toggles the `dark-mode` class on the body element.

This demonstrates DOM manipulation and CSS class management.

### 3.3 Learn More Button

The Learn More button uses an event listener to dynamically change the webpage content. When the user clicks the button, a message is displayed and the button text is updated.

This demonstrates how JavaScript can modify HTML content dynamically.

### 3.4 Contact Form Validation

Client-side form validation was implemented using JavaScript.

The form checks:

* Whether the name is empty.
* Whether the name contains at least three characters.
* Whether the email format is valid.
* Whether the message is empty.
* Whether the message contains at least ten characters.

Error messages are displayed when invalid information is entered.

If all fields are valid, a successful submission message is displayed and the form is reset.

## 4. DOM Manipulation

The project uses JavaScript DOM methods such as:

* `getElementById()`
* `classList.toggle()`
* `classList.contains()`
* `textContent`
* `reset()`

These methods allow JavaScript to access and modify HTML elements dynamically.

## 5. Event Handling

Event listeners were used to respond to user actions.

Examples include:

* Click event for the navigation menu.
* Click event for dark mode.
* Click event for the Learn More button.
* Submit event for the contact form.

The `preventDefault()` method is used during form submission to prevent the browser from submitting the form before validation is completed.

## 6. Challenges Faced

One of the main challenges was managing different user interactions without affecting the existing webpage layout. Another challenge was implementing proper form validation and displaying meaningful error messages.

The responsive navigation menu also required careful integration between CSS media queries and JavaScript class manipulation.

These challenges were solved by separating the HTML, CSS, and JavaScript code and using clear class names and event listeners.

## 7. Debugging and Optimization

The webpage was tested in the browser using the developer console. JavaScript errors were checked and corrected during development.

The code was kept simple and organized by separating different functionalities into sections. No external JavaScript libraries were used, which keeps the project lightweight.

## 8. Result

The static webpage was successfully converted into an interactive webpage. Users can interact with the navigation menu, switch between light and dark modes, click buttons to dynamically update content, and validate the contact form before submission.

## 9. Conclusion

This project provided practical experience with JavaScript fundamentals and DOM manipulation. It demonstrated how JavaScript can improve the usability and functionality of a static webpage.

The implementation successfully integrates HTML, CSS, and JavaScript while maintaining a responsive and user-friendly interface.

