# Markdown Renderer

A simple, single-page web application designed to render Markdown content from an `input.md` file directly into HTML using Tailwind CSS for styling and Marked.js for markdown parsing.

## Features

*   **Markdown to HTML Conversion:** Dynamically converts the content of `input.md` into beautifully rendered HTML.
*   **Responsive Design:** Built with Tailwind CSS, ensuring a consistent and responsive layout across various devices.
*   **Client-Side Rendering:** All processing happens in the browser, requiring no backend server (beyond serving static files).
*   **Easy to Use:** Simply place your markdown content in `input.md` and open `index.html`.

## File Structure

This project consists of the following files:

```
.
├── index.html      # The main application page
├── input.md        # Your markdown content goes here
├── README.md       # This file
└── LICENSE         # MIT License details
```

## Getting Started

To run this application, follow these simple steps:

1.  **Save the files:** Ensure `index.html`, `input.md`, `README.md`, and `LICENSE` are all saved in the same directory.
2.  **Edit `input.md`:** Open `input.md` in a text editor and add your desired Markdown content.
3.  **Open `index.html`:** Double-click `index.html` in your file explorer, or open it with your web browser.

The `input.md` content will automatically be fetched and rendered on the page.

## Technologies Used

*   **HTML5:** For the core structure of the web page.
*   **Tailwind CSS:** A utility-first CSS framework for rapid and responsive UI development.
*   **Marked.js:** A full-featured markdown parser and compiler written in JavaScript.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more details.
