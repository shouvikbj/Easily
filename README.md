# Job Portal Project (Easily)

[Demo](https://easily-wudl.onrender.com)

This is a job portal website developed using Node.js and Express.js. The project allows recruiters to post and manage job listings and provides a user-friendly platform for job seekers to find and apply for suitable roles.

## Table of Contents

- [Overview](#overview)
- [Folder Structure](#folder-structure)
- [File Descriptions](#file-descriptions)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Additional Functionality](#additional-functionality)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Job Portal Project aims to create a platform where recruiters can post job listings and manage applicants, while job seekers can browse job listings and apply for positions. The project follows an MVC architecture using Express.js for server-side routing and EJS for server-side templating.

## Folder Structure

The project follows a structured folder organization:

- Easily/
  - |- views/ # Contains EJS templates for rendering views
  - |- controllers/ # Controllers handling business logic
  - |- models/ # Models defining data structures and operations
  - |- middleware/ # Middleware functions for request processing
  - |- routes/ # Express routes for defining API endpoints
  - |- public/ # Contains static assets like CSS and JavaScript files
  - |- index.js # Main entry point of the application


## File Descriptions

- **views/**: Contains EJS templates for rendering different views of the application.
  - `main.ejs`: Common layout view including header, main content, and footer.
  - `index.ejs`: Landing page with a brief overview of the job portal.
  - `login.ejs`, `register.ejs`: Views for user authentication and registration.
  - `jobListings.ejs`: Page displaying all available job postings.
  - `jobDetails.ejs`: Detailed information about a specific job.
  - `applyJob.ejs`: Form for job seekers to apply for a job.

- **controllers/**: Contains controller files responsible for handling business logic.
  - `userController.js`: Handles user authentication and registration.
  - `jobController.js`: Manages job listings and applicants.

- **models/**: Defines data structures and operations.
  - `userModel.js`: Handles user-related data operations.
  - `jobModel.js`: Manages job listings and applicants data.

- **middleware/**: Contains middleware functions for request processing.
  - `authMiddleware.js`: Middleware for user authentication.
  - `multerMiddleware.js`: Middleware for handling file uploads.
  - `emailMiddleware.js`: Middleware for sending confirmation emails.

- **routes/**: Defines Express routes for API endpoints.
  - `userRoutes.js`: Routes for user authentication and registration.
  - `jobRoutes.js`: Routes for job listings and applicants.

- **public/**: Contains static assets like CSS and JavaScript files used in the frontend.

- **index.js**: Main entry point of the application where server setup and configuration occur.

## Setup and Installation

To run the project locally, follow these steps:

1. Clone the repository: `git clone https://github.com/shouvikbj/Easily.git`
2. Install dependencies: `npm install`
3. Configure environment variables if necessary.
4. Start the server: `node index.js`
5. Visit `http://localhost:PORT` in your browser to access the application.

## Usage

Once the server is running, users can access the job portal through the provided routes and views. Recruiters can create, update, and manage job postings, while job seekers can browse job listings and apply for positions.

## Additional Functionality

Additional features can be implemented to enhance the project further:
- Implement job search functionality.
- Implement resource-based authorization for job management.
- Display user's last visit date and time.
- Add confirmation dialogs for update and delete operations.
- Implement common validation middleware for form validation.
- Implement pagination for job listings and applicant lists.

## Contributing

Contributions to the project are welcome! Feel free to open issues or submit pull requests to help improve the project.

## License

This project is licensed under the [MIT License](LICENSE).
