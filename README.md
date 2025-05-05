# Api-Ti

A RESTful API built with Node.js and Express.js to support the backend operations of Tecno Importaciones. This API handles product data management, user authentication, and provides endpoints for frontend integration.

## 🚀 Features

- **Product Management**: Create, read, update, and delete product information.
- **User Authentication**: Secure user registration and login using JWT.
- **Data Validation**: Ensures data integrity through comprehensive validation.
- **CORS Support**: Enables cross-origin requests for frontend integration.
- **Error Handling**: Robust error handling for consistent API behavior.

## 🛠️ Technologies Used

- Node.js
- Express.js
- MongoDB + Mongoose
- JSON Web Tokens (JWT)
- Body-parser
- CORS

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jeann1809/Api-Ti.git

2. Navigate to the project directory:
   ```bash
   cd Api-Ti
   
3. Install dependencies:
   ```bash
   npm install
   
4. Create a .env file in the root directory with the following content:
   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret


5. Start the server:
   ```bash
   npm start

## 📬 API Endpoints

| Method | Endpoint           | Description                |
| ------ | ------------------ | -------------------------- |
| POST   | /api/register      | Register a new user        |
| POST   | /api/login         | Login and receive a token  |
| GET    | /api/products      | Get all products           |
| GET    | /api/products/\:id | Get a specific product     |
| POST   | /api/products      | Create a new product       |
| PUT    | /api/products/\:id | Update an existing product |
| DELETE | /api/products/\:id | Delete a product           |

Note: Some routes are protected and require a valid JWT in the Authorization header.

## 📄 License
This project is licensed under the MIT License.

## This backend API powers the Tecno Importaciones application by providing secure and scalable services for product and user management.
