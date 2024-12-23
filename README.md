# User Management Dashboard

A simple web application for managing user details. This application demonstrates essential CRUD operations (Create, Read, Update, Delete) using a mock backend API provided by [JSONPlaceholder](https://jsonplaceholder.typicode.com/).

## 🎯 Objective

To build a responsive, user-friendly dashboard where users can:
- View a list of users with their details.
- Add new users.
- Edit existing user details.
- Delete users.

## 🛠️ Features

- **User List**: Display users with fields like ID, First Name, Last Name, Email, and Department.
- **Add User**: Create new users via a form.
- **Edit User**: Update user details with an intuitive form.
- **Delete User**: Remove a user with confirmation.
- **Error Handling**: Inform users of any issues with API requests.
- **Bonus Features**:
  - Responsive UI for mobile and desktop.
  - Pagination or infinite scrolling for a better user experience.
  - Client-side form validation.

## 🚀 Tech Stack

- **Frontend**: React (or any preferred JavaScript framework/library)
- **HTTP Requests**: Axios or Fetch API
- **Mock Backend API**: [JSONPlaceholder](https://jsonplaceholder.typicode.com/)
- **Styling**: CSS/SCSS/Bootstrap/Tailwind (flexible choice)

## 📦 Project Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/TejaYeshamoni/usersdashboard-Ajackus
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the application**:
   ```bash
   npm start
   ```

## 📚 API Reference

This project interacts with the JSONPlaceholder API:

- **Fetch Users**: `GET /users`
- **Add User**: `POST /users`
- **Edit User**: `PUT /users/:id`
- **Delete User**: `DELETE /users/:id`

_Note: JSONPlaceholder simulates successful responses but doesn't persist changes._

## 🧑‍💻 Functionality Details

### View Users
- Fetches a list of users from the `/users` endpoint.
- Displays ID, First Name, Last Name, Email, and Department in a tabular format.

### Add User
- Opens a form for new user input.
- Posts the data to the `/users` endpoint.

### Edit User
- Fetches existing user details.
- Updates the data via a `PUT` request to `/users/:id`.

### Delete User
- Sends a `DELETE` request to `/users/:id`.

### Error Handling
- Alerts users when API requests fail.
- Handles common errors like network issues or invalid data.


## ✨ Bonus Features

- Pagination or infinite scrolling for the user list.
- Form validations (e.g., required fields, email format checks).
- Fully responsive design for all devices.

## 📘 Assumptions

- The `/users` API endpoint is a mock service and doesn't persist changes.
- Basic user details include `ID`, `First Name`, `Last Name`, `Email`, and `Department`.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 Acknowledgments

- [JSONPlaceholder](https://jsonplaceholder.typicode.com/) for providing the mock API.
- [React](https://reactjs.org/) for the amazing UI framework.
- [Bootstrap](https://getbootstrap.com/) for responsive styling.
