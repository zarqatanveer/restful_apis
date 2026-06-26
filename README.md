# RESTful CRUD Posts App

A simple **RESTful CRUD (Create, Read, Update, Delete)** application built using **Node.js**, **Express.js**, **EJS**, and **Method Override**.

This project demonstrates how REST APIs work by allowing users to create, view, edit, and delete posts. It was built as part of my backend development learning journey.

---

## Features

* Create a new post
* View all posts
* View a single post
* Edit an existing post
* Delete a post
* Responsive and clean user interface
* Server-side rendering using EJS
* RESTful routing with Express.js

---

## Technologies Used

* Node.js
* Express.js
* EJS
* HTML5
* CSS3
* JavaScript
* UUID
* Method Override

---

## REST API Routes

| Method | Route             | Description                   |
| ------ | ----------------- | ----------------------------- |
| GET    | `/posts`          | Display all posts             |
| GET    | `/posts/new`      | Display form to create a post |
| POST   | `/posts`          | Create a new post             |
| GET    | `/posts/:id`      | View a specific post          |
| GET    | `/posts/:id/edit` | Display edit form             |
| PATCH  | `/posts/:id`      | Update an existing post       |
| DELETE | `/posts/:id`      | Delete a post                 |

---

## Project Structure

```
RESTful-CRUD-App
│
├── public
│   └── style.css
│
├── views
│   ├── index.ejs
│   ├── show.ejs
│   ├── new.ejs
│   └── edit.ejs
│
├── index.js
├── package.json
├── package-lock.json
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/restful-crud-app.git
```

Move into the project directory

```bash
cd restful-crud-app
```

Install dependencies

```bash
npm install
```

Start the server

```bash
node index.js
```

or

```bash
nodemon index.js
```

Open your browser and visit

```
http://localhost:8080/posts
```

## Learning Outcomes

Through this project I learned:

* Express.js fundamentals
* RESTful API architecture
* CRUD operations
* Route parameters
* Express middleware
* Method Override
* Server-side rendering with EJS
* Handling forms in Express
* Using UUID for unique IDs

---

## Future Improvements

* Store posts in MongoDB
* User authentication
* Image uploads
* Search functionality
* Like and comment system
* Responsive mobile design
* Deployment using Render or Railway

---

## Author

**Zarqa Tanveer**

Aspiring Full Stack Web Developer

