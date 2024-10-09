# Grocery List App

## Introduction
The **Grocery List App** is a simple web application that allows users to create and manage a list of grocery items. Users can add items to the list, search through existing items, and remove items that are no longer needed.

This project is designed to practice basic HTML, CSS (via Bootstrap), and JavaScript, and demonstrates how to manipulate the DOM dynamically.

## Project Structure
- **HTML**: Provides the structure of the page, including headers, input fields, and lists.
- **CSS (via Bootstrap)**: Bootstrap 4.6 is used to style the page and provide a responsive layout.
- **JavaScript**: Handles the functionality for adding, searching, and deleting items.

## Features
1. **Add Items**: Allows users to type in the name of a grocery item and submit it to the list.
2. **Delete Items**: Each item has a delete button ("X") that removes the item from the list when clicked.
3. **Search Items**: Users can search through the list of items by typing in the search field. The list is dynamically filtered as the user types.

## How It Works
- **Add Items**: The form at the top of the list lets users add a new grocery item. When the user clicks "Submit", the item is appended to the list.
- **Delete Items**: Each item in the list has a delete button (`<button class="btn btn-danger btn-sm float-right delete">X</button>`). When clicked, the corresponding item is removed from the list.
- **Search Items**: The search input allows users to filter the items in real-time. As the user types, the list updates to show only matching items.

## Technologies Used
- **HTML5**: Provides the structure of the page.
- **CSS/Bootstrap 4.6**: Used to style the page and ensure it's responsive.
  - Bootstrap classes like `form-control`, `list-group`, and `btn` are used to style input fields, lists, and buttons.
- **JavaScript**: Controls dynamic functionality, such as adding and removing list items and filtering the list.
  - JavaScript functions are written to handle form submissions and dynamically update the DOM.
 
## Future Improvements
- Add local storage support to save the list between browser sessions.
- Implement a more user-friendly design using a modern CSS framework or custom styling.
- Add item editing functionality to allow users to update existing items.
