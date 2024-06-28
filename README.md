# Super Responsive & Attractive Search Engine
This web application simulates a search engine interface with additional features for managing search history. It offers a clean, responsive design suitable for various screen sizes.

# Features
## Search Interface:
Users can enter search queries in the input field and hit the "Search" button or press Enter to perform a Google search based on the entered query. The search results are opened in a new tab.

## Visited Links History:
Upon performing a search, the URL of the search query is stored in the browser's local storage. A "Visited Links" button appears, allowing users to access previously searched queries. Each visited link is clickable and opens in a new tab.

## Clear History:
An additional "Clear History" button allows users to clear all stored search history. Clicking this button removes all stored URLs from local storage and hides both the "Visited Links" and "Clear History" buttons if there are no more links to display.

## Responsive Design:
The interface adjusts dynamically to different screen sizes using CSS media queries. This ensures that the search container and buttons remain visually appealing and functional on both desktop and mobile devices.

# Usage
Enter a search query in the input field.
Press "Search" or hit Enter to perform the search.
Click on "Visited Links" to view and revisit previously searched queries.
Use "Clear History" to remove all stored search history.

# Technical Details
## HTML & CSS:
The structure and styling of the search interface are defined using HTML for markup and CSS for presentation. The layout is designed to be visually attractive with a focus on usability.

## JavaScript (ES6+):
Event listeners are utilized to capture user interactions, such as form submissions and button clicks. Local storage API is employed to store and retrieve search history across sessions.

## Dynamic Dropdown:
A dynamic dropdown menu is implemented using JavaScript to display visited links as the user types or clicks the "Visited Links" button. This dropdown is styled to enhance usability and provide quick access to historical search queries.

# Contributing
## Contributions are welcome! If you have suggestions or feature requests, please open an issue or submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
