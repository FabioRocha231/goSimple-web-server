<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Golang Template Project](#golang-template-project)
  - [About the project](#about-the-project)
    - [API docs](#api-docs)
    - [Design](#design)
    - [Status](#status)
    - [See also](#see-also)
  - [Getting started](#getting-started)
    - [Layout](#layout)
  - [Notes](#notes)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Golang Template Project

## About the project

The template is used to create golang project. All golang projects must follow the conventions in the
template. Calling for exceptions must be brought up in the engineering team.

### API docs

`http://localhost:8080/` is the entry point of this web server
`http://localhost:8080/hello` is a simple `hello world` response
`http://localhost:8080/form.html` is a simple form to send a name and a address
`http://localhost:8080/form` is the form method that receives the form data from `http:localhost:8080/form.html`

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
