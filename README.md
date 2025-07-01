# Device CRM API

This project provides a simple API for managing devices in a CRM (Customer Relationship Management) system.

## Features
- CRUD operations for devices
- Data storage using a local JSON file (`db.json`)
- Easy to run and extend

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository or download the source code.
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the API
Start the server with:
```bash
npm start
```

The API will be available at `http://localhost:3000` (or the port specified in your configuration).

### API Endpoints
- `GET /devices` - List all devices
- `GET /devices/:id` - Get a device by ID
- `POST /devices` - Add a new device
- `PUT /devices/:id` - Update a device
- `DELETE /devices/:id` - Delete a device

## Project Structure
- `db.json` - Local JSON database
- `package.json` - Project metadata and scripts
- `README.md` - Project documentation

## License
MIT
