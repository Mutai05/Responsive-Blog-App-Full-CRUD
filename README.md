# Responsive-Blog-App-Full-CRUD

Responsive Blog Application Web with Admin Panel - Full CRUD PHP nad MySQL

# Blog Application with PHP and MySQL

This is a simple blog application with full CRUD (Create, Read, Update, Delete) functionality. It allows users to create, view, edit, and delete blog posts.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Database Setup](#database-setup)
  - [PHP Configuration](#php-configuration)
  - [CRUD Operations](#crud-operations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Create, view, edit, and delete blog posts.
- Responsive design for a seamless user experience on various devices.
- Simple and easy-to-understand PHP and MySQL implementation.
- Suitable as a foundation for building more complex blogging systems.

## Prerequisites

Prerequisites:

- Web server with PHP and MySQL installed.
- Basic understanding of HTML, CSS, PHP, and MySQL.

## Getting Started

Steps to set up and run the blog application:

### Database Setup

1. Create a MySQL database named `myblog`.
2. Execute the SQL script in `config.php` to create the `posts` table.

### PHP Configuration

1. Open `config.php` and replace the placeholders with your actual database credentials.
2. Ensure your web server has read and write permissions for the project files.

### CRUD Operations

- **Listing Posts:** Open `index.php` to view the list of blog posts.
- **Creating a Post:** Open `create.php` to add a new blog post.
- **Editing a Post:** Open `edit.php?id=<post_id>` to edit an existing blog post.
- **Deleting a Post:** Open `delete.php?id=<post_id>` to delete a blog post.

## Usage

1. Start your web server.
2. Access the blog application in your web browser.
3. Use the provided forms to create, edit, or delete blog posts.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Contributions are welcome and appreciated.

## License

This project is licensed under the [MIT License](LICENSE).
