# random-selector
# Random Selector

This project is a simple web-based Random Selector application. It allows users to input any number of names or entries and then randomly selects one of the choices.

## Files

- `index.html`: The main HTML file containing the structure of the Random Selector application.
- `style.css`: The CSS file containing styles for the Random Selector application.
- `script.js`: The JavaScript file containing the functionality for managing and selecting entries.
- `README.md`: This file, providing an overview of the project.

## Usage

1. Open `index.html` in a web browser.
2. To add an entry:
   - Enter the entry (e.g., a name) in the input field.
   - Click the "Add" button to add the entry to the list.
3. To randomly select an entry:
   - Click the "Select" button to randomly choose one entry from the list.

## HTML Structure

- The `main` tag contains the primary content of the Random Selector application.
- The `div` with the class `todo` contains the heading and the entry list.
- The `div` with the class `heading` contains the title.
- The `div` with the class `list` contains the input field, add button, and the list of entries.
- The `ul` with the id `listcontainer` holds the entries.
- The "Select" button triggers the random selection.

## CSS Styling

- The page is styled with basic CSS to make it visually appealing and user-friendly.
- Google Fonts is used to include the `Madimi One` font for the heading.
- Flexbox is used for layout and alignment.

## JavaScript Functionality

- The `script.js` file contains the logic for adding entries and selecting a random entry.
- An event listener is added to the "Add" button to add entries to the list.
- An event listener is added to the "Select" button to randomly select an entry from the list.

## Future Improvements

- Add persistent storage using LocalStorage to save entries between sessions.
- Implement validation to prevent adding empty entries.
- Improve the user interface with animations and transitions.
- Add the ability to remove individual entries from the list.
- Provide visual feedback for the selected entry.

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License.
