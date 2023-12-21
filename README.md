# Country-capital Quiz Web Application

A Node.js and PostgreSQL-based web application for testing your knowledge about countries and their capitals.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Database Setup](#database-setup)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Rohanbasnet12/country-capital.git
    cd country-capital.git
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up the PostgreSQL database (see [Database Setup](#database-setup)).

4. Create a `.env` file in the root directory with the following content:

    ```env
    DB_HOST=your_postgresql_host
    DB_PORT=your_postgresql_port
    DB_USER=your_postgresql_user
    DB_PASSWORD=your_postgresql_password
    DB_NAME=your_database_name
    ```

5. Start the application:

    ```bash
    npm start
    ```

6. Open your web browser and go to http://localhost:3000 to view the application.

## Usage

- Visit the home page and start testing your knowledge about countries and their capitals.
- View your total score and restart the quiz to improve your knowledge.

## Database Setup

This application uses PostgreSQL as its database. Make sure you have PostgreSQL installed and running.

1. Create a new PostgreSQL database:

    ```bash
    createdb country_quiz_db
    ```

2. Run the database schema script:

    ```bash
    psql -d country_quiz_db -a -f db/schema.sql
    ```

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m 'Add a new feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
