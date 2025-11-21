# Simple Web Calculator

A clean and responsive web-based calculator that performs basic arithmetic operations. Built with vanilla HTML, CSS, and JavaScript without any external frameworks or libraries, this project demonstrates fundamental web development principles while providing a practical tool for everyday calculations.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Roadmap](#roadmap)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Prerequisites

### Supported Browsers

This calculator works on modern web browsers with the following minimum versions:

- Google Chrome >= 90
- Mozilla Firefox >= 88
- Microsoft Edge >= 90

### Running the Application

This is a static HTML/CSS/JavaScript application that can be run in two ways:

#### Option 1: Direct File Opening

You can open the main HTML file directly in your browser by double-clicking it or using File > Open in your browser. This works for basic functionality, though some browsers may restrict certain features when loading files via the file:// protocol.

#### Option 2: Using a Simple HTTP Server (Recommended)

Running the application through an HTTP server is recommended for the best experience and full functionality. Choose one of the following methods based on what you have installed:

**Using Python 3:**

```bash
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

**Using Python 2:**

```bash
python -m SimpleHTTPServer 8000
```

Then open http://localhost:8000 in your browser.

**Using Node.js (http-server):**

If you don't have http-server installed, install it globally:

```bash
npm install -g http-server
```

Then run:

```bash
http-server -p 8080
```

Or use npx to run without installing:

```bash
npx http-server -p 8080
```

Then open http://localhost:8080 in your browser.

**Using PHP:**

```bash
php -S localhost:8000
```

Then open http://localhost:8000 in your browser.

## Installation

### 1. Clone the Repository

Clone this repository to your local machine using Git:

```bash
git clone https://github.com/sahanpinavida/tester05.git
cd tester05
```

Alternatively, you can download the repository as a ZIP file from GitHub and extract it to your desired location.

### 2. Launch the Calculator

Once you have the project files on your local machine, you can launch the calculator using one of the following methods:

#### Method A: Direct File Opening

1. Navigate to the project directory
2. Locate the `index.html` file
3. Open it in your web browser by:
   - Double-clicking the file, or
   - Right-clicking and selecting "Open with" and choosing your preferred browser, or
   - Dragging the file into an open browser window

This method is quick and simple for immediate testing and usage.

#### Method B: Using an HTTP Server (Recommended for Development)

1. Open a terminal or command prompt
2. Navigate to the project root directory (where `index.html` is located)
3. Start a simple HTTP server using one of the methods described in the [Prerequisites](#prerequisites) section
4. Open the provided localhost URL in your browser (e.g., http://localhost:8000)

This method is recommended because:

- It mirrors the production environment when deployed to GitHub Pages or static hosting
- It avoids potential browser security restrictions with the file:// protocol
- It provides a more accurate testing environment for web features

For detailed HTTP server setup instructions, see the [Running the Application](#running-the-application) section under Prerequisites.

## Usage

Detailed examples demonstrating addition, subtraction, multiplication, and division operations will be documented in this section.

## Contributing

Guidelines for contributing to this project, including workflow, coding standards, and commit conventions, will be outlined here.

## Roadmap

Information about planned features and version history will be available in this section.

## License

License information and badges will be displayed here.

## Acknowledgements

Credits and acknowledgements for contributors and resources used in this project.
