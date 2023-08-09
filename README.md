# D&D 5th Edition DRS API Database

This repository contains the database structure and information for the API that provides access to the Brazilian Portuguese adaptation of the "Documento de referência do sistema" (DRS), which is an adaptation of the D&D 5th Edition System Reference Document (SRD). The API focuses on managing Character Sheets and provides endpoints to access these sheets.

## Table of Contents

- [Introduction](#introduction)
- [Documentation](#documentation)
- [Getting Started](#getting-started)
- [Database Structure](#database-structure)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The D&D 5th Edition DRS API Database serves as the backend support for the API, allowing users to access and manage Character Sheets based on the Brazilian Portuguese adaptation of the DRS. The API provides various endpoints to perform CRUD (Create, Read, Update, Delete) operations on Character Sheets.

## Documentation

For detailed information on how to use the API and interact with the database, please refer to the official API documentation. The documentation includes details about authentication, available endpoints, request/response formats, and usage examples.

//TODO:: In development...

## Getting Started

To set up the API and database locally, follow these steps:
//TODO:: 
1. Clone this repository: `git clone https://github.com/your-username/dnd-5e-drs-api-database.git`
2. Install the required dependencies for your chosen backend technology.
3. Configure the database connection settings in the configuration file.
4. Run the database migration scripts to create the required tables.
5. Start the API server.

## Database Structure

The database is designed to store information related to Character Sheets, including attributes, abilities, and other relevant data. The database schema includes tables such as:
//TODO:: 
- `characters`: Stores information about individual characters, such as name, race, class, and level.
- `abilities`: Stores abilities and traits associated with characters.
- `inventory`: Stores character inventory and equipment details.
- ... (additional tables as needed)

The relationships between these tables ensure efficient data storage and retrieval.

## API Endpoints

The API provides various endpoints to interact with Character Sheets:
//TODO:: 
- `GET /characters`: Retrieve a list of all characters.
- `GET /characters/{id}`: Retrieve details of a specific character.
- `POST /characters`: Create a new character.
- `PUT /characters/{id}`: Update details of a specific character.
- `DELETE /characters/{id}`: Delete a character.

Refer to the API documentation for a comprehensive list of available endpoints, request/response formats, and example usage.

## Contributing

Contributions to this project are welcome! If you find any issues or want to add enhancements, please open a pull request. Be sure to follow the project's coding standards and guidelines.

## License

This project is licensed under the [MIT License - Open Gaming License Version 1.0a]([LICENSE](https://opengamingfoundation.org/ogl.html)), which means you are free to use, modify, and distribute the code as long as you include the original license and attribution.
