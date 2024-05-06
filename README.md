# \[PuttProLeague\] Mini Golf League Management System

## Description

This project is a management system for organizing and conducting mini golf leagues where players compete individually. The performance of players is evaluated based on the number of strokes below par. The system offers public views of league tables and schedules, as well as administrative functionalities for managing player entries and game results.

## Technologies

- **Frontend**:
  - **SvelteKit**: A modern framework for building fast and reactive web applications.
  - **Tailwind CSS**: A utility-first CSS framework for custom design without heavy lifting.
  - **Apollo Client**: Comprehensive state management library for JavaScript, ideal for integrating with GraphQL.
  - **Houdini**: A powerful addition to GraphQL, allowing for auto-generated hooks and local state management to synchronize with your GraphQL cache seamlessly.

- **Backend**:
  - **Node.js** with **Express**: A flexible JavaScript web application framework.
  - **GraphQL**: A query language for your API and a runtime for fulfilling those queries with your data.
  - **Apollo Server**: A community-driven GraphQL server that integrates well with Express.

- **Database**:
  - **PostgreSQL**: A robust open-source relational database.

- **Webserver** (optional for production environment):
  - **Nginx** or **Apache**: Both are robust options for hosting web applications.

## Local Setup

### Prerequisites

Ensure the following software is installed on your system:

- Node.js
- PostgreSQL
- Git

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/entchen66/PuttProLeague.git
   cd PuttProLeague
   ```

2. Install the necessary Node.js packages:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory of the project and configure the required environment variables:
   ```
   DB_HOST=localhost
   DB_USER=myuser
   DB_PASS=mypassword
   DB_NAME=minigolflgdb
   ```

4. Initialize the database and populate it with initial data (optional):
   ```bash
   npm run db:init
   ```

5. Start the server:
   ```bash
   npm start
   ```

## Usage

After starting the server, you can access the web application by navigating to `http://localhost:3000` in your browser.

## Contributing

To contribute to this project, please follow the usual fork-and-pull Git workflow:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and push them to your fork.
4. Create a pull request to the original repository.

## License

This project is licensed under the MIT License. Details can be found in the LICENSE file.
