# Project TODOs

This document outlines potential improvements and tasks for the NFT Weingarten Football Training Planner project, categorized for clarity.

## Coding Style Improvements

- [ ] **Modularity and Separation of Concerns (JavaScript)**: Split the monolithic JavaScript block into separate, logically grouped files (e.g., `theme.js`, `navigation.js`, `charts.js`, `drills.js`, `gameplayTips.js`, `modals.js`, `gemini.js`).
- [ ] **HTML Semantics and Accessibility**: Review and enhance HTML with more semantic tags (e.g., `<article>`, `<aside>`) and ARIA attributes for improved accessibility. Ensure consistent heading hierarchy.
- [x] **CSS Organization and Maintainability**: Move custom CSS from the `<style>` block into a separate `.css` file (e.g., `style.css` or `custom.css`). Consider consolidating rules or leveraging more Tailwind utilities.
- [ ] **JavaScript Best Practices**:
    - [ ] Implement more robust error handling with specific user feedback for API calls and other operations.
    - [ ] Investigate and implement performance optimizations like lazy loading for images or non-critical sections.
    - [ ] Centralize magic strings, numbers, and configurations into a dedicated constants or config file.

## Platform Improvements

- [ ] **Frontend Framework Adoption**: Migrate the project to a modern JavaScript frontend framework (e.g., React, Vue, Svelte) to leverage component-based architecture, state management, and declarative UI.
- [ ] **Build Tool Integration**: Introduce a build tool (e.g., Vite, Webpack, Parcel) to automate bundling, transpilation, minification, and enable features like Hot Module Replacement (HMR) for development.
- [ ] **TypeScript Integration**: Convert JavaScript files to TypeScript to add static typing, improve code quality, readability, and developer experience.
- [ ] **Backend/Serverless Functions for AI Integration**: For enhanced security and control, consider proxying Gemini API calls through a simple backend or serverless function (e.g., AWS Lambda, Google Cloud Functions, Vercel Functions) to avoid exposing the API key directly on the client-side.
- [ ] **Testing Frameworks**: Implement unit tests (e.g., Jest, Vitest) for JavaScript functions and end-to-end tests (e.g., Cypress, Playwright) for overall application functionality.