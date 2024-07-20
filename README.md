# Real-Time Tracking Application

A real-time tracking application built using Node.js, Express, Socket.io, and Leaflet.js. This application demonstrates real-time updates on a map interface, perfect for tracking moving objects or displaying live location data.

## Features

- **Real-Time Updates:** Leveraging Socket.io for real-time communication.
- **Interactive Maps:** Using Leaflet.js for displaying and interacting with maps.
- **Modular Structure:** Clean and maintainable code with a modular project structure.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/codewithbalaji/Realtime_Tracker.git
   cd real-time-tracking-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the server:**

   ```bash
   node app.js
   ```

4. **Open your browser** and navigate to `http://localhost:3000`.

## Usage

Once the server is running, open your browser and navigate to `http://localhost:3000` to view the real-time tracking map. The map will update in real-time as location data is received.

## Project Structure

```
real-time-tracking-app/
├── public/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
├── views/
│   └── index.ejs
├── app.js
├── package.json
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
