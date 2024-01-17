# jvec--assessment-frontend
# Contact Manager Web Application

Welcome to the Jvec Contact Manager web application! This application allows users to manage their contacts efficiently. The application is divided into a backend RESTful API and a frontend built with ReactJS, utilizing TypeScript and Redux for state management.

## Backend

### Technologies Used

- Node.js with TypeScript
- Express.js
- MongoDB as the database
- JWT for authentication
- Mongoose for MongoDB object modeling
- Bcrypt for password hashing
- Cors for handling Cross-Origin Resource Sharing

### Installation and Setup

1. Install Node.js and npm (Node Package Manager) on your machine.

2. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

3. Install backend dependencies:

   ```bash
   cd backend
   npm install
   ```

4. Start the backend server:

   ```bash
   npm start
   ```

   The backend server will run on http://localhost:3001.

## Frontend

### Technologies Used

- ReactJS with TypeScript
- Redux for state management
- Axios for handling HTTP requests
- Bootstrap 5 for styling

### Installation and Setup

1. Install frontend dependencies:

   ```bash
   cd frontend
   npm install
   ```

2. Start the React app:

   ```bash
   npm start
   ```

   The React app will run on http://localhost:3000.

## Application Usage

1. Open your web browser and navigate to http://localhost:3000 to access the web app.

2. Explore different features of the application, including signup, login, managing contacts, and logging out.

## Additional Information

- The backend uses a MongoDB database. Make sure you have MongoDB installed and running on your machine.

- Adjust MongoDB connection details in the backend (`backend/src/app.ts`) if necessary.

- Backend API routes are prefixed with `/api`.

- API documentation (Swagger or similar) can be added for better understanding.

Feel free to customize and extend the application based on your requirements. If you encounter any issues or have questions, please refer to the documentation or open an issue on the repository.

---
