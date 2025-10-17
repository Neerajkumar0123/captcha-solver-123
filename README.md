# Captcha Solver Interface

This project provides a simple, single-file responsive HTML application for interacting with image-based captchas. Built with Tailwind CSS, it offers a user-friendly interface to display a captcha image and allow users to input the perceived text.

## Features

-   **Responsive Design**: Optimized for various screen sizes using Tailwind CSS.
-   **Dynamic Image Loading**: Loads captcha images from a URL specified in the query string (`?url=...`) or defaults to a local `sample.png` file.
-   **User Input**: Provides an input field for users to type the captcha text.
-   **Client-Side Validation (Example)**: Includes a basic client-side validation logic against a hardcoded captcha text (based on `sample.png`) to demonstrate functionality. In a real-world scenario, this validation would typically involve a backend API or a more sophisticated OCR solution.

## How to Use

1.  **Save the files**: Ensure `index.html`, `README.md`, `LICENSE`, and any referenced image files (like `sample.png`) are in the same directory.
2.  **Open `index.html`**: Simply open `index.html` in your web browser.

### Loading Custom Captcha Images

To load a specific captcha image, append a `url` query parameter to the `index.html` URL.

**Example:**
`index.html?url=https://example.com/path/to/your/image.png`

If no `url` parameter is provided, the application will default to displaying `sample.png`.

## Development

This application is designed as a single-file solution using:
-   **HTML5**: For structure.
-   **Tailwind CSS (CDN)**: For utility-first styling and responsiveness.
-   **Vanilla JavaScript**: For dynamic content loading and interaction.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.