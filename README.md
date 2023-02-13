# LightCode

## Introduction

LightCode is a powerful web-based development tool allowing multiple users to modify the same codebase in real-time. It is built with React.js, Node.js, Socket.IO, and Tailwind CSS technologies and you can experience its capabilities through the Live Demo at https://glowing-florentine-cf9253.netlify.app.

## Features

- Shared editing: Users can collaboratively modify the same codebase in real-time, observing each other's modifications.
- Colored syntax: The editor includes support for multiple programming languages, highlighting code with distinct colors.
- Immediate view: Modifications to the source are displayed live in a preview window.
- Multiple language support

## Installation

To install and run LightCode locally, follow these steps:

1. Clone the repository: `git clone https://github.com/rangola/LightCode`
2. Navigate to the project directory: `cd LightCode`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`

The application will be running at http://localhost:3000.

## Deployment

To deploy the Realtime Code Editor to a production environment, follow these steps:

1. Build the production bundle: `npm run build`
2. Set the `NODE_ENV` environment variable to `production`: `export NODE_ENV=production`
3. Start the production server: `npm run start:prod`

## Configuration

The Realtime Code Editor can be customized by creating a `.env` file in the root directory of the project and setting the following variables:

- `PORT`: The port number on which the server should listen (default: 3000).
- `SESSION_SECRET`: A secret used to encrypt session data.
- `HOST`: The hostname or IP address of the server (default: localhost).

## License

The Realtime Code Editor is licensed under the MIT License. See [LICENSE](LICENSE.md) for more information.
