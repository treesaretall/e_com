# E-commerce Backend Application

[![treesaretall](https://img.shields.io/badge/github-treesaretall-orange)](https://github.com/treesaretall)

This is a backend application for an e-commerce site built using Express.js and Sequelize, allowing you to interact with a MySQL database.

To see the functionality of this application, please refer to the following walkthrough video: [link to walkthrough video](https://drive.google.com/file/d/1cFHULk3NIL4mtyvfRfmZatfo3pCxM51U/view).

## Installation

To install and run this application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/treesaretall/e-com.git
   ```

2. Navigate to the project directory:

   ```bash
   cd e-com
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Set up the database:

   - Create a `.env` file in the root directory of the project.
   - Add the following lines to the `.env` file, replacing the placeholders with your MySQL credentials:

     ```plaintext
     DB_NAME=your_database_name
     DB_USER=your_mysql_username
     DB_PASSWORD=your_mysql_password
     ```

5. Initialize the database:

   ```bash
   npm run db:init
   ```

6. Start the application:

   ```bash
   npm start
   ```

7. You can now access the API endpoints using an API development tool such as Insomnia or Postman.

## Technologies Used

- Express.js
- Sequelize
- MySQL

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please create a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
