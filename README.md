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
   pnpm install
   ```
3. Start the backend server:
   ```sh
   pnpm start
   ```

## Frontend

The frontend is located in the [frontend](http://_vscodecontentref_/18) directory and consists of the following files:

- [index.html](http://_vscodecontentref_/19): Main HTML file.
- [manifest.json](http://_vscodecontentref_/20): Web app manifest.
- [robots.txt](http://_vscodecontentref_/21): Robots.txt file.
- [App.js](http://_vscodecontentref_/22): Main React component.
- [index.js](http://_vscodecontentref_/23): Entry point for the React application.
- [reportWebVitals.js](http://_vscodecontentref_/24): Performance reporting.
- [setupTests.js](http://_vscodecontentref_/25): Setup for testing.

### Running the Frontend

1. Navigate to the [frontend](http://_vscodecontentref_/26) directory:
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

- [CORS_ORIGIN](http://_vscodecontentref_/27): Allowed origins for CORS.
- [PORT](http://_vscodecontentref_/28): Port for the backend server.

## WebSocket Communication

The WebSocket server is set up in [app-ws.js](http://_vscodecontentref_/29) and handles connections, messages, and errors. The frontend uses the `react-use-websocket` library to connect to the WebSocket server and receive messages.

## License

This project is licensed under the ISC License.
