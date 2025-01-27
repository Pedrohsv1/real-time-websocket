# Real-Time WebSocket Application

This project is a real-time web application that uses WebSockets for communication between the frontend and backend. The backend is built with Express and WebSocket, while the frontend is built with React.

## Project Structure

## Backend

The backend is located in the `websocket` directory and consists of the following files:

- `.env`: Environment variables for the backend.
- `app.js`: Express application setup with middleware.
- `app-ws.js`: WebSocket server setup and configuration.
- `index.js`: Entry point for the backend application.

### Running the Backend

1. Navigate to the `websocket` directory:
   ```sh
   cd websocket
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the backend server:
   ```sh
   npm start
   ```

## Frontend

The frontend is located in the [frontend]() directory and consists of the following files:

- [index.html](): Main HTML file.
- [manifest.json](): Web app manifest.
- [robots.txt](): Robots.txt file.
- [App.js](): Main React component.
- [index.js](): Entry point for the React application.
- [reportWebVitals.js](): Performance reporting.
- [setupTests.js](): Setup for testing.

### Running the Frontend

1. Navigate to the [frontend]() directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend development server:
   ```sh
   npm start
   ```

## Environment Variables

The backend uses the following environment variables:

- [CORS_ORIGIN](): Allowed origins for CORS.
- [PORT](): Port for the backend server.

## WebSocket Communication

The WebSocket server is set up in [app-ws.js]() and handles connections, messages, and errors. The frontend uses the `react-use-websocket` library to connect to the WebSocket server and receive messages.

## License

This project is licensed under the ISC License.
