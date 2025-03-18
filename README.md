# Discord-like App (Frontend Only)

This project is a frontend-only recreation of a simplified Discord-like application, built using HTML, CSS (with a focus on modern CSS features like custom properties, flexbox, and grid), and minimal, well structured, accessible HTML.


## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    ```
    Replace `<repository_url>` with the actual URL of your GitHub repository.

2.  **Open `index.html` in your browser:**

    Since this is a frontend-only project, you can simply open the `index.html` file directly in your web browser.  No server setup is required.

## Project Structure

*   **`index.html`:**  The main HTML file containing the structure of the application.
*   **`style.css`:**  The CSS file containing all the styles for the application.

## Customization

The `style.css` file uses CSS custom properties (variables) extensively.  This makes it very easy to customize the appearance of the application.  You can change colors, fonts, spacing, and other styles by modifying the values of the variables defined at the top of the `style.css` file, within the `:root` selector.

For example, to change the primary color, you would modify the `--color-primary` variable:

```css
:root {
    --color-primary: #5865f2; /* Original Discord purple */
    /* Change to a different color: */
    --color-primary: #7289da;  /* A slightly different purple */
}
Use code with caution.
