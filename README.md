# Express Web App with Business Hours Restriction

## Description

Simple web application using Express and EJS with three pages:
- Home
- Services
- Contact

Includes a custom middleware to restrict access to business hours (Monday to Friday, 9am to 5pm).

## Features

- Navigation bar on each page
- CSS styling
- Middleware to allow access only during business hours
- EJS templating engine

## Installation

1. Clone the repo
2. Run `npm install`
3. Start the server with `node app.js`

## Usage

Access the app at `http://localhost:3000` during business hours.
Outside these hours, a message indicates the service is unavailable.

## License

MIT
