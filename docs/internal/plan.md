## Plan for CSS Organization and Maintainability

1.  **Extract CSS:** Extract the CSS content from the `<style>` block within `docs/index.html`.
2.  **Create New CSS File:** Create a new file named `src/css/style.css` and populate it with the extracted CSS.
3.  **Remove Old CSS:** Delete the `<style>` block from `docs/index.html`.
4.  **Link New CSS:** Add a `<link>` tag to `docs/index.html` to reference the newly created `src/css/style.css` file.