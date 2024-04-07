Summary:
This repository contains a web application for note-taking. Users can create, edit, and delete notes directly in the browser. The interface is minimalistic and intuitive, making it easy for users to manage their notes effectively.

Description:
The project consists of HTML, CSS, and JavaScript files that work together to create a note-taking application. Here's a breakdown of the components:

HTML (index.html): Defines the structure of the web page. It includes elements for the container, headings, buttons, and the area where notes are displayed.

CSS (style.css): Styles the HTML elements to provide a visually appealing interface. It sets up the layout, colors, and styles for buttons, input boxes, and the overall container.

JavaScript (javascript.js): Implements the functionality of the application. It allows users to create new notes, edit existing ones, and delete notes. It also utilizes local storage to persist notes even after the page is refreshed or closed.

Features:

Create Note: Users can click the "Create Note" button to add a new note. Each note is represented as a text input box with an option to delete.
Edit Note: Notes are editable directly within the input boxes. Users can type, edit, and format text as needed.
Delete Note: Each note has a delete button (represented by an image) that allows users to remove unwanted notes from the list.
Persistent Storage: Notes are stored locally using the browser's local storage API. This ensures that notes are saved even if the user closes or refreshes the page.
Responsive Design: The application is designed to work well on different screen sizes, from desktops to mobile devices, thanks to responsive CSS styles.
