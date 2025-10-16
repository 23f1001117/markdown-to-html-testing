# Markdown to HTML Viewer

This is a simple, single-page web application designed to render Markdown files (`.md`) into clean, readable HTML directly in your browser. It leverages `marked.js` for Markdown parsing and `Tailwind CSS` for a responsive and modern design.

## Features

- Converts `input.md` to HTML on page load.
- Renders the HTML with a responsive design using Tailwind CSS.
- Easy to deploy – just open `index.html` in a web browser.

## Getting Started

To use this application, ensure you have the following files in the same directory:

- `index.html`: The main application file.
- `input.md`: Your Markdown content file that will be converted and displayed.
- (Optional) `LICENSE`: The license file.

### Usage

1. **Place your Markdown file:** Make sure your Markdown content is saved as `input.md` in the same directory as `index.html`.
2. **Open `index.html`:** Double-click `index.html` or open it with your web browser.

The page will automatically fetch `input.md`, convert its content to HTML, and display it.

## Technologies Used

- **HTML5:** For the basic structure of the web page.
- **Tailwind CSS:** A utility-first CSS framework for styling and responsive design.
- **Marked.js:** A fast and powerful Markdown parser and compiler to HTML.

## Customization

- To change the displayed Markdown file, simply rename your desired `.md` file to `input.md` or modify the `fetch('input.md')` call in `index.html` to point to a different file name.
- You can customize the styling further by modifying the `<style>` block in `index.html` or by adding/changing Tailwind CSS classes.

## License

This project is open-source and available under the [MIT License](LICENSE).