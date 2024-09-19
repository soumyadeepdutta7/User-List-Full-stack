# User Management App

A simple and responsive web-based user management application that allows you to add, view, delete, and export user data to CSV. The app is designed with an eye-pleasing dark gradient UI, mobile compatibility, and interactive elements such as hoverable buttons and modals.

## Features

- **Add Users**: Submit user information through a form and dynamically add it to the user table.
- **Delete Users**: Delete individual users from the table with a confirmation modal.
- **Select Users**: Select individual users or select all users with checkboxes.
- **Export Users**: Export selected users as a CSV file.
- **Persistent Storage**: User data is saved in `localStorage` and persists even after page reload.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [CSS Styles](#css-styles)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started with the Swimlane Task Manager locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/soumyadeepdutta7/swimlane.git

2. **Navigate to the Project Directory**:
   ```bash
   cd swimlane-ui

3. **Install Dependencies**:
   ```bash
   npm install

4. **Run the Application**:
   ```bash
   npm run dev


## Usage

1. Add a User: Fill out the sign-up form with first name, last name, and email, then click "Add User."
2. Select Users: Use the checkboxes in the table to select users. Click the "Select All" checkbox to select all users or deselect all.
3. Delete Users: Click the "DELETE" button next to a user to open the confirmation modal, then confirm to delete.
4. Export Users: Click the "EXPORT" button to download a CSV file of the selected users.



## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Redux**: State management library for handling application state.
- **CSS**: Styles for layout and design.
- **HTML**: Markup language for the structure of the web application.
- **Node.js**: JavaScript runtime for server-side operations (development environment).
- **npm**: Package manager for managing project dependencies.


## Live Demo

You can view a live demo of the application at the following link:

[Live Demo](https://swimlane-management-app.netlify.app/)

