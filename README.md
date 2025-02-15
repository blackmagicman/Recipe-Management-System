# Recipe Management System

## Introduction

The Recipe Management System is a web-based application designed to help users manage and organize their recipes. Users can add, edit, delete, and search for recipes. The application also allows users to categorize their recipes and share them with others.

## Features

- **User Authentication:** Secure login and registration system.
- **Recipe CRUD Operations:** Create, read, update, and delete recipes.
- **Categorization:** Categorize recipes for better organization.
- **Search Functionality:** Search for recipes based on keywords.
- **Sharing:** Share recipes with other users.
- **Responsive Design:** Compatible with both desktop and mobile devices.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, React
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)

## Installation

To run the application locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/blackmagicman/Recipe-Management-System.git
   cd Recipe-Management-System
   ```

2. **Install the dependencies:**
   ```bash
   npm install
   ```

3. **Set up the environment variables:**
   Create a `.env` file in the root directory and add the following variables:
   ```
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the application:**
   ```bash
   npm start
   ```

5. **Open the application in your browser:**
   ```
   http://localhost:3000
   ```

## Usage

1. **Register an account:**
   Create a new account using your email and password.

2. **Log in:**
   Log in with your registered email and password.

3. **Add a new recipe:**
   Navigate to the "Add Recipe" section and fill in the details of your recipe.

4. **View and edit recipes:**
   Browse through your recipes, edit or delete them as needed.

5. **Search for recipes:**
   Use the search bar to find specific recipes by keywords.

6. **Share recipes:**
   Share your recipes with other users by providing them with a link.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository:**
   Click the "Fork" button at the top right corner of this page.

2. **Clone your forked repository:**
   ```bash
   git clone https://github.com/yourusername/Recipe-Management-System.git
   cd Recipe-Management-System
   ```

3. **Create a new branch:**
   ```bash
   git checkout -b feature-branch
   ```

4. **Make your changes:**
   Implement your changes and commit them with a descriptive message.

5. **Push your changes:**
   ```bash
   git push origin feature-branch
   ```

6. **Create a pull request:**
   Open a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or suggestions, please feel free to contact us at [your-email@example.com].

Happy cooking!
