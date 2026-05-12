# Go Todo List App

A simple Todo List web application built using Go and the built-in `net/http` package.

This project was created while learning the fundamentals of Go web development, including:

- Creating HTTP servers
- Routing using `http.HandleFunc`
- Writing responses to the browser
- Working with slices
- Serving multiple endpoints

The application currently displays a welcome message and a list of tasks directly in the browser.

---

# Features

- Simple HTTP web server
- Home route (`/`)
- Tasks route (`/show-tasks`)
- In-memory task storage using slices
- Beginner-friendly project structure

---

# Technologies Used

- Go (Golang)
- net/http package
- fmt package

---

# Project Structure

```bash
.
├── main.go
└── README.md
```

---

# Code Overview

## Task Storage

The tasks are currently stored in a slice:

```go
var taskItems = []string{
    "Watch Go crash course",
    "Watch Nana's Golang Full Course",
    "Reward myself with a donut",
}
```

---

## Available Routes

| Route | Description |
|---|---|
| `/` | Displays a welcome message |
| `/show-tasks` | Displays all todo tasks |

---

# Getting Started

## Prerequisites

Before running the project, make sure you have installed:

- Go (Golang)

Download Go from the official website:

https://go.dev/

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/go-todo-app.git
```

## Navigate to the Project Folder

```bash
cd golang-todo-app

```

---

# Running the Application

Start the server using:

```bash
go run main.go
```

The server will start on:

```bash
http://localhost:8080
```

---

# Testing the Routes

## Home Route

Open:

```bash
http://localhost:8080/
```

Expected output:

```text
Hello user. Welcome to our Todolist App!
```

---

## Show Tasks Route

Open:

```bash
http://localhost:8080/show-tasks
```

Expected output:

```text
Watch Go crash course
Watch Nana's Golang Full Course
Reward myself with a donut
```

---

# Tutorial Followed

This project was built while following the Go tutorial by freeCodeCamp and Nana Janashia:

https://youtu.be/XCZWyN9ZbEQ

---

# What I Learned

Through this project, I learned:

- How to create a basic HTTP server in Go
- How routing works using `http.HandleFunc`
- How to send responses to the browser
- How slices can store application data
- Basic backend development concepts in Go

---

# License

This project is for learning purposes.
