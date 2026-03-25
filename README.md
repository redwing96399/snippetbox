# Snippetbox

A web application written in Go for creating, storing, and viewing text snippets. The project demonstrates core backend and web development concepts including HTTP routing, middleware, templating, and database integration.

---

## Features

- Create, view, and manage text snippets  
- Server-side rendered HTML templates  
- Structured routing and middleware handling  
- Form validation and error handling  
- Persistent storage using a relational database  
- Basic web security practices (e.g., CSRF protection, input validation)

---

## Tech Stack

- **Language:** Go  
- **Web:** net/http  
- **Templating:** html/template  
- **Database:** MySQL 
- **Other:** Middleware, sessions, form handling  

---

## Getting Started

### Prerequisites

- Go (>= 1.20)
- PostgreSQL

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/snippetbox.git
   cd snippetbox
   ```
2. Set up the Database:
```bash
CREATE DATABASE snippetbox;
```
3.Configure environment variables (or update config in code):
```bash
DB_DSN=postgres://user:password@localhost/snippetbox?sslmode=disable
```
4.Run migrations (if applicable)

5.Start the server:
```bash
go run ./cmd/web
```

6.Open your browser:
```bash
http://localhost:4000
```
