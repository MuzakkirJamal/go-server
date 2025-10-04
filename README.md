# Go Server with Static Frontend

## Description
A lightweight full-stack web application built with **Go (Golang)** for the backend and **HTML/CSS** for the frontend.  
The project serves static pages, handles form submissions, and demonstrates basic routing and HTTP request handling — perfect for learning full-stack development in Go without any external frameworks or databases.

---

## Features
- Serve static HTML pages (`index.html`, `form.html`) using Go’s `http.FileServer`.
- Handle POST requests from HTML forms and display submitted data.
- Basic routing for `/`, `/form`, and `/hello`.
- Clean, minimal CSS styling for a professional look.
- Can be compiled into a single executable (`.exe`) for Windows.

---

## Folder Structure
go-server/
├── main.go
├── go.mod (optional)
├── static/
│ ├── index.html
│ ├── form.html
│ └── style.css
└── README.md

---


## How to Run

1. **Clone the repo**:

    ```bash
    git clone https://github.com/your-username/go-server.git
    cd go-server
    ```

2. **Run directly with Go**:

    ```bash
    go run main.go
    ```

3. **Or build an executable**:

    ```bash
    go build -o go-server.exe
    ./go-server.exe
    ```

4. Open your browser at [http://localhost:8080/](http://localhost:8080/)

---

## Future Improvements
- Add a **success page** after form submission.
- Add **JavaScript validation** for the form.
- Deploy to a cloud service like **Heroku, Render, or Railway**.

---









