# Refactored Project

An Angular application built with modern Angular standalone components and routing.

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
npm install
```

### Development Server

Run the development server:

```bash
npm start
```

Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Build

Build the project for production:

```bash
npm run build:prod
```

The build artifacts will be stored in the `dist/` directory.

### Running Tests

Execute the unit tests:

```bash
npm test
```

## Project Structure

```
src/
├── app/
│   ├── app.component.ts       # Root component
│   ├── app.component.html     # Root template
│   ├── app.component.scss     # Root styles
│   ├── app.routes.ts          # Application routes
│   └── app.config.ts          # Application configuration
├── main.ts                    # Application entry point
├── index.html                 # HTML template
└── styles.scss                # Global styles
```

## Built With

- [Angular](https://angular.io/) - The web framework
- [TypeScript](https://www.typescriptlang.org/) - Programming language
- [SCSS](https://sass-lang.com/) - CSS preprocessor

## License

This project is licensed under the MIT License.
