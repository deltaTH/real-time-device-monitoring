# Realtime Device Track

## Overview

Realtime Device Track is a web application that allows users to track devices in real-time. The application leverages Express.js for the server, EJS for templating, and Socket.io for real-time communication.

## Features

- Real-time device tracking
- Responsive user interface
- Easy to set up and use

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/deltaTH/realtime-device-track.git
    ```
2. Navigate to the project directory:
    ```sh
    cd realtime-device-track
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    node app.js
    ```
2. Open your browser and navigate to `http://localhost:3000` to view the application.

## Project Structure

realtime-device-track/
│
├── app.js # Main application file
├── package.json # Project metadata and dependencies
├── views/ # EJS templates
│ ├── index.ejs # Main view template
│ └── ...
├── public/ # Static assets (CSS, JS, images)
│ ├── css/
│ ├── js/
│ └── ...
└── ...


## Dependencies

- [Express](https://www.npmjs.com/package/express) - Fast, unopinionated, minimalist web framework for Node.js
- [EJS](https://www.npmjs.com/package/ejs) - Embedded JavaScript templates
- [Socket.io](https://www.npmjs.com/package/socket.io) - Enables real-time, bidirectional, and event-based communication

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## Author

[Abhay Singh](https://github.com/deltaTH)
