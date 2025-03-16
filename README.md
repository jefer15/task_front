# Task Management App (Frontend)

This is the frontend for the Task Management application built with Angular. The application allows users to manage tasks efficiently by performing CRUD operations.

## Prerequisites

Before running the project, ensure you have the following installed:

- **Node.js** (v18.x or later)
- **Angular CLI** (v15.1.2)

## Getting Started

Follow these steps to set up the project locally:

### 1. Clone the Repository
```sh
git clone -b develop https://github.com/jefer15/task_front.git
cd task-front
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Start the Development Server
```sh
npm start
```
This will run the app on `http://localhost:4200/`.

## Build the Project
To generate a production build, run:
```sh
npm run build
```
The build files will be generated in the `dist/` folder.

## Branching Strategy
The main development happens on the `develop` branch. Please ensure to create feature branches from `develop` before making changes.

## Additional Scripts
- `npm run test` - Runs unit tests
- `npm run watch` - Watches for file changes and rebuilds automatically

## Technologies Used
- Angular 15
- Angular Material
- RxJS
- SweetAlert2
- TailwindCSS

## License
This project is licensed under the MIT License.

