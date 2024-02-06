# Customizable Sidebar Component

This repository contains the code for a customizable sidebar component built using React.js. The sidebar component is designed to be highly flexible and can be managed dynamically using an array of objects representing sidebar items. It supports an infinite number of child elements and automatically adjusts its behavior based on the provided data structure.

## Features

- Dynamic Management
- Infinite Nesting
- Automatic Behavior
- Customizable Styling
- Responsive Design

## Tech Stack

- Frontend:
  - React.js
  - React Router
  - Styled Components

## Setup Instructions

1. **Clone the Repository**: Use `git clone` to clone this repository to your local machine.
   ```bash
   git clone https://github.com/naumanch969/customizable-sidebar.git
   ```

2. **Install Dependencies**:
   - Navigate to the cloned repository directory:
     ```bash
     cd customizable-sidebar
     ```
   - Install the required dependencies:
     ```bash
     npm install
     ```

3. **Start the Development Server**:
   - After installing dependencies, start the development server:
     ```bash
     npm start
     ```
   - The sidebar component will be accessible at `http://localhost:3000` in your web browser.

4. **Customize Sidebar Data**:
   - Open the `src/data/sidebarData.js` file and customize the sidebar menu items as needed.
   - Each sidebar item is represented by an object in the array, with properties such as `label`, `icon`, `link`, and `children` for nested items.

---

Feel free to explore, test, and customize this customizable sidebar component according to your requirements. If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Happy coding! 🚀
