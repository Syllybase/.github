# Syllybase

Welcome to Syllybase, a comprehensive syllabus management application. This repository contains three main directories:

- `next_app`: A Next.js app for the frontend. It uses Firebase for authentication and data storage, and connects to the Flask API for data retrieval.
- `flask_app`: A Flask API that serves as the backend. It fetches data from a Firebase database and Redis cache.
- `docs`: Contains documentation for the project. Inside the `docs` directory, there's a subdirectory `databaseDesign` that contains the data dictionary for the database.

## Requirements

1. Node.js and npm installed for the `next_app`.
2. Python 3.6 (or higher) and pip installed for the `flask_app`.
3. Firebase project created and configured for the application.
4. Redis installed and configured for the `flask_app`.

## Setup

1. Clone the repository.
2. Follow the instructions in the README files of `next_app`, `flask_app` and `docs` directories for setting up each part of the application.

## Directories

- `next_app`: Navigate to [next_app/README.md](next_app/README.md) for a detailed guide on setting up and running the Next.js application.

- `flask_app`: Navigate to [flask_app/README.md](flask_app/README.md) for instructions on setting up and running the Flask API.

- `docs`: Inside the `docs` directory, you will find various documentation related to the project. The `databaseDesign` directory contains a data dictionary for the Firebase database used in the project. Navigate to [docs/databaseDesign/README.md](docs/databaseDesign/README.md) to read more.

## Contributing

We welcome contributions to the project. Please refer to each directory's specific contributing guidelines.

## License

This project is licensed under the MIT License. For more information, see the `LICENSE` file in each directory.

## Support

If you need any help, feel free to reach out or create an issue in the repository.

This README acts as a starting point for navigating the Syllybase application. Be sure to thoroughly read the README file in each directory for a better understanding of that part of the application.