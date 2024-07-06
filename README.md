Project Name
Overview
This project is a responsive and feature-rich web application built using React and Reactstrap. It includes a dynamic navbar with search and filter functionalities, a modal for detailed filter options, and a user dropdown menu. The application is designed to provide an intuitive and seamless user experience for navigating, searching, and filtering products.

Table of Contents
Features
Installation
Usage
Components
API Context
Contributing
License
Features
Responsive Navbar: A sticky navbar with logo, search input, notification icon, and user dropdown.
Search Functionality: A search input in the navbar that opens a modal for detailed search and filter options.
Filter Modal: A modal with inputs for search, quantity, and cost price filters.
User Dropdown Menu: Dropdown menu for user actions including profile, settings, and logout.
Context API Integration: Uses React Context API for managing global state.
Installation
Clone the repository:

sh
Copy code
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:

sh
Copy code
npm install
Start the development server:

sh
Copy code
npm start
Usage
After installing the dependencies and starting the development server, you can access the application at http://localhost:3000. The application includes a navbar with search and filter functionality, and a user dropdown menu.

Running Tests
To run the tests for this project, use the following command:

sh
Copy code
npm test
Components
Navbar Component
File: src/components/NavbarComponent.jsx
Description: The main navigation bar component with logo, search input, notification icon, and user dropdown menu.
Key Features:
Opens a modal for detailed search and filter options.
Handles navigation through the application.
Integrates with the global state using Context API.
Filter Modal
File: src/components/FilterModal.jsx
Description: A modal component that provides detailed filter options for searching products.
Key Features:
Contains inputs for search term, quantity, and cost price.
Submits the filter values to update the global state.
API Context
ApiContext
File: src/context/apiContext.js
Description: Context for managing global state related to products, search, and filters.
Key Functions:
setSearch: Updates the search term in the global state.
setFilters: Updates the filter values in the global state.
setSupplier: Manages supplier-related state (if applicable).
Contributing
We welcome contributions to this project! To contribute, please follow these steps:

Fork the repository.
Create a new branch for your feature or bugfix.
Commit your changes and push the branch to your fork.
Create a pull request with a detailed description of your changes.
Please ensure your code follows the project's coding standards and includes relevant tests.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Feel free to reach out if you have any questions or need further assistance! Thank you for contributing to this project.