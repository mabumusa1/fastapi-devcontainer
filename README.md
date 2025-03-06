# Sample FastAPI Application

This project is a sample FastAPI application that serves a simple "Hello, World!" message at the root endpoint. It uses dev containers and .vscode for development.

## Getting Started

To start developing with this project, ensure you have Docker and Visual Studio Code installed. Open the project in Visual Studio Code and use the dev container feature to set up the development environment.

## Using Dev Containers

1. Open the project in Visual Studio Code.
2. When prompted, reopen the project in a dev container. If not prompted, press `F1` and select `Remote-Containers: Reopen in Container`.
3. The dev container will set up the necessary environment for you to start developing.

## Running the Application

1. Open the integrated terminal in Visual Studio Code.
2. Run the application using the following command:
   ```sh
   uvicorn main:app --reload
   ```
3. The application will be available at `http://localhost:8000`.

## Debugging the Application

1. Open the project in Visual Studio Code.
2. Ensure the dev container is running.
3. Set breakpoints in your code where needed.
4. Press `F5` to start the debugger. The application will run in debug mode, and you can inspect variables, step through code, and more.

## Endpoints

- `GET /`: Returns a JSON message `{"message": "Hello, World!"}`.
