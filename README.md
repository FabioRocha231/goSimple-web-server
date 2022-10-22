## About the project
This project is a simple web server create to absorb the content and studies from golang programming language

### API docs

* `http://localhost:8080/` is the entry point of this web server.
* `http://localhost:8080/hello` is a simple `hello world` response.
* `http://localhost:8080/form.html` is a simple form to send a name and a address.
* `http://localhost:8080/form` is the form method that receives the form data from `http:localhost:8080/form.html`.

## Getting started

to run this project you need to clone this repository and use the `go run main.go` command in your CL shell

### Layout

```tree
├── static
│   ├── index.html
│   └── form.html
├── main.go
└── README.md
```

A brief description of the layout:

* `main.go` the api entry point
