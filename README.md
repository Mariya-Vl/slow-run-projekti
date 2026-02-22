# Slow Run – Academic Web Project

## Project overview
Slow Run is a web project created as part of an academic assignment.
The task was to build a website for an association using a simple content management approach and a database.

The project includes a public website and basic admin functionality for managing content.

---

## Project requirements
The project was developed according to the assignment guidelines and includes:
- Front page with desktop and mobile versions
- News page where content is loaded from a database
- Contact page with a form that saves data to the database
- Navigation menu for moving between pages
- Basic admin functionality for managing content
- Responsive layout

---

## Features
- Homepage with responsive layout
- News section with content stored in a database
- Contact form with data saved to the database
- Admin pages for managing articles and content
- Separate styles for desktop and mobile views

---

## Tech stack
- HTML
- CSS
- JavaScript
- PHP
- SQL (MySQL)

---

## Development notes
- The project uses a local database
- PHP is used for server-side logic and database interaction
- Content such as news and contact messages is stored in MySQL
- Styling is implemented with custom CSS, including responsive styles

---

## My Role and Contribution

Role: **Full-stack Developer**

I was responsible for a significant part of both backend and admin functionality, as well as deployment configuration and UI improvements.

Key contributions include:
- Created and configured the GitHub repository and project structure
- Set up the local development environment and database (MySQL)
- Implemented the News page (layout, styling, and responsive behavior)
- Developed most of the admin panel functionality, including:
  * adding new articles with image upload, validation, and automatic file naming
  * managing user messages (view, filter unread, mark as read, delete)
  * changing the homepage hero image with validation rules and preview
- Implemented form validation and improved file upload logic
- Configured Google Maps JavaScript API integration for the contact page
- Implemented automatic deployment to the school server using GitHub Actions and FTP workflow
- Created environment configuration files (.env, .gitignore, .htaccess, connection setup)
- Applied UI and styling improvements across multiple pages
- Prepared the final client instruction presentation for using the admin features

The project was completed as part of a collaborative academic assignment.

---

## Running the project locally
This project requires a local PHP environment and a MySQL database.

Recommended setup:
- XAMPP
- Import the database into MySQL
- Configure database settings in `.env` or `connection.php`
- Run the project via `localhost`

The project is intended for local development and is not deployed online.

---
### Homepage
![Homepage](screenshots/home.png)

### News page
![News](screenshots/uutiset.png)

### Contact form
![Contact](screenshots/yhteys.png)

### Mobile view
![Mobile](screenshots/mobile.png)

---

## Notes
This repository represents an academic project created for learning purposes.
It is not intended for production use.
