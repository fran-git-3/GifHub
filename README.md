# GifHub

GifHub is a fun and interactive web application built with Angular that allows users to search, view, and share GIFs from various categories. It connects to the Giphy API to provide an endless collection of GIFs for entertainment and sharing.

## Features

- **Search for GIFs**: Search GIFs by keywords or categories.
- **View GIFs**: View GIFs in full-screen mode.
- **Share GIFs**: Share GIFs with others via social media or direct links.
- **Save Favorites**: Option to save favorite GIFs to a personal collection (if logged in).
- **Responsive UI**: Fast and responsive user interface with a mobile-friendly design.

## Technologies Used

- **Frontend**: Angular, HTML, CSS, TypeScript
- **API**: Giphy API (for retrieving GIFs)
- **State Management**: NgRx (optional, if using a global state)
- **Routing**: Angular Router (for navigating between different views)

## Installation

To run GifHub locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fran-git-3/GifHub.git
   
2. **Navigate into the project directory**:

cd GifHub

3. **Install the dependencies**:

npm install

4. **Set up the Giphy API key**:

    Create a .env file in the root directory (or use Angular's environment files).
    Add your Giphy API key:

    GIPHY_API_KEY=your_api_key_here

4. **Run the application**:

    You can start the app using either of these commands:

    ng serve

or

    npm start

Your app should now be running on http://localhost:4200.
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
