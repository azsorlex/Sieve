# Sieve

## Getting started
While the application can be run simply by opening `index.html` in a browser, the latest version of Node.js is required to run the application in Electron and build installers. Download it here: https://nodejs.org/en/

In a terminal window within the project directory, run `npm install` to install the required packages. Run `npm update` to update installed packages.

Markup is found in `index.html`, scripts are found in `scripts/`, and styles are found in `styles.css`.

## Run
Run `npm start` to run the project.

## Distribution
Run `npm run dist` to create an installer for the current operating system. Installers can be created for Windows, macOS and Linux. Icons used in installers are found in `build/`. To just create a packaged app instead of an installer, run `npm run pack`. The outputs will be saved within `dist/`.
