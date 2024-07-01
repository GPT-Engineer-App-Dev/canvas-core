# MyApp

This is a minimal web application built with React, Shadcn-UI, and Tailwind CSS. It serves as a starting point for building more complex applications.

## Features

- Home Page with a welcome message and brief description.
- Navigation Bar with links to the Home page and a placeholder for future pages.
- Footer with placeholder text.
- Basic styling using Tailwind CSS.
- Responsive layout.

## File Structure

- `src/`
  - `components/`
    - `layouts/`
      - `navbar.jsx` - Navigation bar layout.
  - `pages/`
    - `Index.jsx` - Home page.
  - `App.jsx` - Main application component.
  - `index.css` - Tailwind CSS styles.
  - `main.jsx` - Entry point for the React application.

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the application:**

   ```bash
   npm run dev
   ```

4. **Open your browser:**

   Navigate to `http://localhost:5173` to see the application in action.

## Modifying the Application

- **Adding new pages:**
  - Create a new file in the `src/pages/` directory.
  - Add a new route in `src/App.jsx`.

- **Updating the navigation bar:**
  - Modify the `src/components/layouts/navbar.jsx` file to add or remove links.

- **Styling:**
  - Use Tailwind CSS classes to style your components.
  - Modify the `src/index.css` file to add global styles.

## License

This project is licensed under the MIT License.