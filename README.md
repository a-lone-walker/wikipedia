# Wikipedia Search Application

## Overview
This is a simple web application that allows users to search Wikipedia articles and displays the results dynamically. The application is built using HTML, CSS, and JavaScript, with additional support from external libraries such as Bootstrap for styling and animations.

## Features
- **Responsive Design**: The application is styled to be responsive and works well on various screen sizes.
- **Dynamic Search**: As users type in the search input and press Enter, the application fetches and displays relevant Wikipedia articles.
- **Loading Spinner**: A loading spinner is displayed while fetching data from the API, enhancing user experience.
- **Interactive UI**: The user interface includes animations and transitions for a smooth and engaging experience.

## Project Structure

simple-wiki-search/
│
├── index.html
├── styles.css
├── script.js
└── README.md


- `index.html`: The main HTML file for the application.
- `styles.css`: The CSS file for styling the application.
- `script.js`: The JavaScript file for handling the search functionality.
- `README.md`: The file you are currently reading.

## Detailed Functionalities

### HTML (`index.html`)
- **Header Section**:
  - Includes the Wikipedia logo and a search input field.
- **Spinner**:
  - A loading spinner that appears when a search is in progress.
- **Search Results**:
  - A container to display the search results dynamically.

### CSS (`styles.css`)
- **Font Imports**:
  - Various Google Fonts are imported for styling text.
- **Body Styling**:
  - A gradient background and a default font are applied to the body.
- **Main Container**:
  - Centralized content with flexbox, and a background animation for visual appeal.
- **Search Header**:
  - Includes styling for the header section with hover effects for interactivity.
- **Search Input**:
  - Custom styling for the search input field, including focus effects.
- **Search Results**:
  - Styling for the container that holds the search results.
- **Result Items**:
  - Each search result is styled with padding, margin, shadows, and hover effects for interactivity.

### JavaScript (`index.js`)
- **Element Selection**:
  - Grabs the necessary DOM elements like the search input, search results container, and the spinner.
- **Create and Append Search Result**:
  - A function to create and append each search result to the DOM.
- **Display Results**:
  - A function to handle the display of search results by hiding the spinner and appending results to the container.
- **Search Wikipedia**:
  - The main function that handles the search operation. It listens for the Enter key, makes a fetch request to the Wikipedia API, and processes the returned data.
- **Event Listener**:
  - Adds an event listener to the search input to trigger the search operation when the Enter key is pressed.

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/simple-wiki-search.git
    ```

2. Navigate to the project directory:

    ```bash
    cd simple-wiki-search
    ```

3. Open the `index.html` file in your web browser:

    ```bash
    open index.html
    ```


## Customization
- The search endpoint in `index.js` can be changed to point to a different API or extended to include more parameters.
- CSS styles in `styles.css` can be adjusted to match a different theme or design language.
- Additional features such as pagination or advanced search filters can be implemented by modifying the JavaScript code.

## Contributing

Feel free to fork this repository and submit pull requests. Any contributions are welcome and appreciated!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Contact

If you have any questions or feedback, please feel free to contact me at [kadagalaashok414@gmail.com](mailto:kadagalaashok414@gmail.com).

