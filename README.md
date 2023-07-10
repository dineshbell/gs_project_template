## Getting started
The fastest way to get started with Godspeed is by following the [Godspeed documentation](https://docs.mindgrep.com/).

# Restaurant App

This is a Godspeed project for a restaurant application.

## Prerequisites

- Godspeed CLI (installation guide: [Guide to Install Godspeed CLI](1.0k))
- PostgreSQL database
- Docker

## Getting Started

To get started with the project, follow these steps:

1. Create a new Godspeed project using the Godspeed CLI:

2. During the project creation process, select PostgreSQL as the database option.

3. Open the project in Visual Studio Code (VSCode) by running the following command in the terminal:

4. Inside VSCode, click on "Open in Container" to run the project in a development container.

5. Once the container is running, open a terminal within VSCode.

6. Build the project by running the following command:

7. After the build is complete, start the development server by running the following command:

- The `datasources` directory contains the Prisma schema file for connecting to the PostgreSQL database.
- The `functions` directory contains the serverless functions for handling API requests.
- The `workflows` directory contains the workflow configurations.

## Usage

The project provides several REST API endpoints to interact with the restaurant data. Here are some examples:

- `GET /restaurant/:restaurantId`: Fetch a restaurant by its ID.
- `POST /restaurant`: Create a new restaurant.
- `PUT /restaurant`: Update an existing restaurant.
- `DELETE /restaurant/:restaurantId`: Delete an existing restaurant.
- `POST /restaurant/search`: Fetch restaurants of a particular city, including menu items based on the provided coupon code.

For more details on the available endpoints, refer to the project's documentation.

## License

This project is licensed under the [MIT License](LICENSE).
