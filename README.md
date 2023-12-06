# go-rest

Reference repo for a REST API service written in Go. Demonstrates a basic setup using the Gin framework.

## Prerequisites

Before you begin, ensure you have the following installed:

- Go (v1.15 or later)
- Git

>To check the version of Go installed, run the `go version` command:

## Installation

To set up the project on your local machine, follow these steps:

### Install Dependencies

The project uses Go Modules for managing dependencies. To install all the necessary dependencies, run:

```shell
go mod tidy
```

This command will download and install all the required packages.

## Run the application

To run the application, navigate to the `/cmd/api` directory and use the `go run` command:

```shell
cd cmd/api
go run main.go
```

The server should start, and you will see a message indicating that it's listening on a port (default is `:8080`).

## Testing the API

Once the server is running, you can test the API endpoints. For example, to test the `/ping` endpoint:

```shell
curl http://localhost:8080/ping
```

You should see a response like:

```json
{"message":"pong"}
```
