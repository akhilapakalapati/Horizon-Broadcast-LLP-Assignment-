# Horizon Broadcast

Horizon Broadcast is a React application designed to provide a seamless and interactive experience for users to explore different categories such as Home, Movies, TV Shows, Sports, and Live content. The application features multi-language support and a dynamic user interface that updates based on the selected language.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Dynamic Language Support:** Switch between multiple languages including English, French, German, Russian, Spanish, and Chinese.
- **Responsive Design:** Full-screen images and layout adjustments based on selected language.
- **Navigation:** Clear and intuitive menu navigation to access Home, Movies, TV Shows, Sports, and Live sections.
- **Settings Management:** Change language preferences through a dedicated settings component.

## Installation

To get started with the Horizon Broadcast project, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/horizon-broadcast.git
   cd horizon-broadcast
   ```

2. **Install Dependencies**

   Ensure you have [Node.js](https://nodejs.org/) installed. Then run:

   ```bash
   npm install
   ```

## Usage

1. **Start the Development Server**

   ```bash
   npm start
   ```

   This command will start the development server and open the application in your default web browser.

2. **Build the Project**

   To create a production build of the project, run:

   ```bash
   npm run build
   ```

   The build artifacts will be generated in the `build/` directory.

## Project Structure

Here's a brief overview of the project's directory structure:

```
horizon-broadcast/
├── public/
│   ├── index.html
│   └── images/                     # Store your full-screen images here
│       ├── home.jpg
│       ├── movies.jpg
│       ├── tvShows.jpg
│       ├── sports.jpg
│       └── live.jpg
├── src/
│   ├── components/
│   │   ├── Menu.js                 # Menu component
│   │   ├── Settings.js             # Settings component
│   │   └── Menu.css                # CSS for Menu component
│   ├── pages/                      # Pages for individual menu items
│   │   ├── Home.js
│   │   ├── Movies.js
│   │   ├── TVShows.js
│   │   ├── Sports.js
│   │   └── Live.js
│   ├── App.js                      # Main application component
│   ├── App.css                     # Global CSS for the application
│   ├── index.js                    # Entry point for React
│   └── index.css                   # Global CSS reset and common styles
├── .gitignore
├── package.json
└── README.md
```

## Contributing

Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue in the [GitHub repository](https://github.com/your-username/horizon-broadcast).


