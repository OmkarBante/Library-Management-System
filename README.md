# Library Management Web App

This is a web application for managing books, users, and the issue and return of books in a library. The application provides different user permissions for students, librarians, and admins.

## User Permissions

### Student

A student can:
- Register themselves on the app
- View their profile
- Search for books and view availability
- View the books they have borrowed
- See their issue history and total rent to be paid.

### Librarian

A librarian can:
- View their profile
- Search for books and view availability
- View, edit, or delete existing books
- Add new books
- Issue a book to a student
- Return a book issued earlier
- View all statistics of the library
- View the issue log and the profile of all students

### Admin

An admin can:
- View and edit their profile
- Search for books and view availability
- View, edit, or delete existing books
- Add new books
- Issue a book to a student
- Return a book issued earlier
- View all statistics of the library
- View the issue log and the profile of all students
- See detailed reports and statistics of total books issued, total users, total issues, and total revenue generated
- View the profile of all admins

### Note to Viewers

You can try logging in as an admin by entering the following credentials:
- Email: admin@iitism.ac.in
- Password: Admin1@iitism

You can also register yourself as a student and then log in to view the options available to a student.

## View Live App

This web app is hosted at https://library-6fpp.onrender.com/.

## Tech Stack Used

### The MERN Stack
- MongoDB: Document database used to store data as JSON
- Express.js: Back-end web application framework running on top of Node.js
- React: Front-end web app framework used
- Node.js: JavaScript runtime environment

### Middleware
- Redux: For flux architecture and fetching rapidly data
- Mongoose: For ODM for MongoDB.
