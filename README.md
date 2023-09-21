# Simple Todo List Web Application

This is a simple todo list web application built for learning purposes. Users can create and manage tasks they need to complete. Additionally, it includes the ability to create custom task lists based on specific categories or contexts.

## Technologies Used

- Node.js
- Express.js
- Mongoose (MongoDB)
- EJS (Embedded JavaScript) for templating

## Project Description

The project serves as an introduction to building web applications with Node.js and Express. It demonstrates how to set up routes, handle user input, and interact with a MongoDB database using Mongoose.

### Features

1. **Task Management**: Users can create, update, and delete tasks.
2. **Custom Lists**: Users can create custom task lists based on specific categories or contexts, e.g., work, personal, shopping, etc.
3. **API Endpoint**: The application provides an API endpoint (`/customListName`) to create and manage custom task lists programmatically.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/pranavdharrao/ToDO-v1.git
   cd todo-list-project
   ```

2. Install dependencies using npm:

   ```bash
   npm install
   ```

3. Create a `.env` file in the project root directory and set your MongoDB connection URL. Example:

   ```env
   MONGODB_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<dbname>
   ```

4. Start the application:

   ```bash
   npm start
   ```

   The application will be available at `http://localhost:3000`.

## Usage

1. Open your web browser and navigate to `http://localhost:3000`.
2. You can start adding tasks to your default task list.
3. To create a custom task list, use the following URL format: `http://localhost:3000/<customListName>`, where `<customListName>` can be any name you choose.

## Contributing

Feel free to contribute to this project by creating issues or submitting pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was developed for educational purposes and is inspired by various tutorials and resources on web development.

---
