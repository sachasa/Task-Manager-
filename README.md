# Task Manager Web Application

A simple yet complete web-based task management application built with HTML, CSS, and JavaScript. This project demonstrates fundamental web development concepts while providing practical functionality.

![Task Manager App Screenshot](https://via.placeholder.com/800x450?text=Task+Manager+App)

## Features

- ✅ Create, read, update, and delete tasks (CRUD operations)
- ✅ Mark tasks as completed/pending with visual indicators
- ✅ Task statistics dashboard showing total, completed, and pending tasks
- ✅ Responsive design works on mobile and desktop
- ✅ Clean, intuitive user interface
- ✅ No frameworks - built with vanilla JavaScript
- ✅ Node.js/Express backend with MongoDB database

## Live Demo

[View the live demo](#) (Coming soon)

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Icons**: Font Awesome

## Installation and Setup

### Prerequisites

- Node.js (v14+ recommended)
- MongoDB (local installation or MongoDB Atlas account)

### Setup Instructions

1. Clone the repository
   ```
   git clone https://github.com/yourusername/task-manager.git
   cd task-manager
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/task-manager
   ```
   Note: Update the MONGODB_URI if you're using MongoDB Atlas

4. Start the application
   ```
   npm run dev
   ```

5. Open your browser and visit `http://localhost:3000`

## Project Structure

```
task-manager/
├── public/               # Static files
│   ├── index.html        # Main HTML page
│   ├── css/
│   │   └── style.css     # CSS styles
│   └── js/
│       └── main.js       # Frontend JavaScript
├── server.js             # Express server & API routes
├── package.json          # Project dependencies
└── .env                  # Environment variables
```

## API Endpoints

| Method | Endpoint      | Description             |
|--------|---------------|-------------------------|
| GET    | /api/tasks    | Get all tasks           |
| POST   | /api/tasks    | Create a new task       |
| PUT    | /api/tasks/:id | Update a specific task  |
| DELETE | /api/tasks/:id | Delete a specific task  |

## Future Enhancements

- User authentication and authorization
- Task categories/tags
- Due dates and reminders
- Filtering and searching tasks
- Task priorities

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Font Awesome](https://fontawesome.com/)
