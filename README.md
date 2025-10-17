# Markdown to HTML Converter

This is a simple, single-file web application that converts a Markdown file (`input.md`) into HTML and renders it directly in the browser. It leverages HTML, Tailwind CSS for styling, and Marked.js for efficient Markdown parsing.

## Features

*   **Dynamic Markdown Rendering**: Fetches `input.md` and converts its content to HTML using Marked.js.
*   **Responsive Design**: Built with Tailwind CSS, ensuring a pleasant viewing experience across various devices.
*   **Self-Contained**: A single `index.html` file contains all the necessary code (HTML, CSS, JavaScript) for operation, along with the `input.md` and `LICENSE` files.

## Setup and Usage

1.  **Clone the repository or download the files:**
    Ensure you have `index.html`, `input.md`, `README.md`, and `LICENSE` in the same directory.

2.  **Open `index.html` in your browser:**
    Simply double-click `index.html` or open it with your preferred web browser. The page will automatically load `input.md`, convert it, and display the resulting HTML.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: A utility-first CSS framework for rapid UI development and responsive design.
*   **JavaScript (ES6+)**: Handles fetching the Markdown file and dynamic content updates.
*   **Marked.js**: A fast Markdown parser and compiler written in JavaScript.

## Project Structure

```
.
├── index.html       // The main application file
├── input.md         // The Markdown content to be converted and displayed
├── README.md        // This file
└── LICENSE          // The MIT License
```

## Customization

To use your own Markdown content:

1.  Replace the content of `input.md` with your desired Markdown text.
2.  Refresh `index.html` in your browser to see the updated content.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.