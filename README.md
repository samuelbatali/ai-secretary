# Ai Secretary

Ai Secretary is a project designed to assist with various secretarial tasks using AI technologies. This project is built using TypeScript and Vite, and it leverages the OpenAI API for its AI functionalities.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Build](#build)
- [Scripts](#scripts)
- [License](#license)

## Installation

To get started with the Ai Secretary project, you need to have Node.js and npm installed on your machine. Then, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/ai-secretary.git
    cd ai-secretary
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

To run the project in development mode, use the following command:
```sh
npm run dev
```

This will start a local development server and you can view the project in your browser at http://localhost:3000.

## Development

The project is set up with TypeScript and Vite. The main entry point for the application is src/main.ts. Styles are managed in src/style.css.

## Project Structure

- src/: Contains the source code for the project.
    - main.ts: The main entry point for the application.
    - style.css: The main stylesheet for the application.
    - vite-env.d.ts: TypeScript declaration file for Vite.
- index.html: The main HTML file for the project.
- .env: Environment variables file (not included in version control).
- tsconfig.json: TypeScript configuration file.
- package.json: Project configuration and dependencies.
- package-lock.json: Lockfile for npm dependencies.

## Build
To build the project for production, use the following command:

```sh
npm run build
```
This will compile the TypeScript code and bundle the project using Vite.

## Scripts

- dev: Starts the development server.
- build: Compiles the TypeScript code and bundles the project for production.
- preview: Previews the production build.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.