# My Profile and Contact Page

## 1. Project Overview

The My Profile and Contact Page is a single-page website developed using HTML5. The purpose of this project is to demonstrate my understanding of HTML document structure, semantic HTML elements, and accessible form creation.

The webpage introduces me as a student learning web development, presents my interests and goals, and provides a contact form through which visitors can enter their information and select the reason for their inquiry.

## 2. Project Objectives

The main objectives of this project are to:

- Create a valid HTML5 document using the correct boilerplate.
- Apply semantic HTML elements to organize webpage content.
- Create an About Me section containing a profile image, personal introduction, and lists.
- Develop an accessible contact form using appropriate input types.
- Connect form labels to their corresponding form controls.
- Apply basic HTML form validation using the `required` attribute.
- Maintain proper indentation and close HTML elements correctly.

## 3. Technologies Used

- HTML5:Used to structure the webpage, organize content, create navigation, display lists, and build the contact form.

No JavaScript or external libraries are required for the webpage.

## 4. Page Structure

The webpage is organized into the following sections:

### Header

The header contains the main page title, a welcome message, and navigation links that allow visitors to move to the About Me and Contact Me sections.

### Navigation

The navigation menu uses the `<nav>` element and links to section IDs within the same webpage.

### About Me

The About Me section is contained in an `<article>` element. It includes:

- A profile image with alternative text.
- A short personal introduction.
- An unordered list of interests.
- An ordered list of personal learning goals.

### Contact Me

The contact form is contained within a `<section>` element. It allows visitors to enter their details and provide information about their inquiry.

The form includes:

- Full Name:A text input for the visitor's name.
- Email Address: An email input for the visitor's email address.
- Inquiry Category: A dropdown list containing General Question, School Project, Work Opportunity, and Other.
- Message: A textarea for entering a message.
- Newsletter Subscription: A checkbox that allows visitors to indicate their subscription preference.
- Submit Button: A button for submitting the form.

### Footer

The footer contains the copyright notice for the webpage.

## 5. Semantic HTML Elements Used

The project uses semantic and structural HTML elements to organize the document.

HTML Element Purpose 
`<header>`  Contains the page heading and introductory content.
`<nav>` Groups the navigation links.
`<main>` Contains the main content of the webpage.
`<article>`  Groups the About Me content.
`<section>`Groups the Contact Me form.
`<footer>`Contains the copyright information.
`<h1>`, `<h2>`, `<h3>` Establish a clear heading hierarchy.
`<ul>` and `<ol>` | Display interests and goals as lists. 
`<form>` Groups the contact form controls.
`<label>` Identifies each form field.
`<input>`, `<select>`, `<textarea>` Collect visitor information.
`<button>`Provides the form submission control.

## 6. Accessibility and Form Validation

Accessibility was considered when developing the contact form.

- Each form control has a corresponding `<label>`.
- The `for` attribute on each label matches the `id` of its form control.
- Appropriate input types, including `text` and `email`, are used.
- The `required` attribute ensures that the name, email address, inquiry category, and message must be provided before a normal browser submission can proceed.
- The profile image includes alternative text through the `alt` attribute.
- Navigation links use section IDs to help visitors move around the page.

These features improve the structure and usability of the webpage.

## 7. Project File Structure

The project contains the following files and folders:

profile-contact-page/
│
├── index.html
├── README.md
└── images/
    └── profile.jpeg

- `index.html` contains the webpage structure and contact form.
- `README.md` documents the project and its implementation.
- `images/profile.jpeg` contains the profile image displayed in the About Me section.

The webpage itself is implemented in a single HTML file, as required by the project objective.

## 8. How to Run the Project

1. Download or clone the project repository.
2. Open the project folder.
3. Locate `index.html`.
4. Open `index.html` in a web browser.
5. Use the navigation links to move between the About Me and Contact Me sections.
6. Enter information into the contact form to test its required fields.

## 9. Limitations

The contact form currently uses `action="#"` and does not connect to a backend or external form-processing service. Therefore, it does not send messages to an email address or store submissions.

The newsletter checkbox records the visitor's selection only within the form; it does not subscribe the visitor to a mailing list.

## 10. Conclusion

This project helped me practice HTML5 document structure, semantic elements, lists, images, internal navigation, and accessible form creation. It also strengthened my understanding of how to organize webpage content using appropriate HTML elements.

The project demonstrates my progress in learning web development and provides a foundation for building more advanced websites in the future.
