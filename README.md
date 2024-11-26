# Hello MCP

This repository demonstrates a simple implementation of the Model-Controller-Presenter (MCP) architectural pattern. MCP is a variation of the MVC pattern that provides better separation of concerns and testability.

## Structure

- `model/`: Contains the data models and business logic
- `controller/`: Handles user input and coordinates between Model and Presenter
- `presenter/`: Formats data for display and manages view logic

## Getting Started

1. Clone the repository
2. Run `go mod tidy` to install dependencies
3. Run `go run main.go` to start the application

## Example Usage

The example implements a simple greeting system where:
- Model: Stores and manages user data
- Controller: Processes greeting requests
- Presenter: Formats greetings for display