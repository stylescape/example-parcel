# Stylescape Parcel Example

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/stylescape/example-parcel)

This example demonstrates how to integrate [Stylescape](https://github.com/stylescape/stylescape) with [Parcel](https://parceljs.org/), a zero-configuration web application bundler.

## About Stylescape

Stylescape is a comprehensive design system and CSS framework that provides a complete toolkit for building modern, accessible, and responsive web interfaces. It includes layout systems, interactive components, and utility classes.

## Installation

```sh
git clone https://github.com/stylescape/example-parcel.git
cd example-parcel
npm install
```

## Usage

### Development Server

```sh
npm start
```

This starts the Parcel development server with hot module replacement.

### Production Build

```sh
npm run build
```

Builds optimized assets for production.

## Project Structure

```
example-parcel/
├── src/
│   ├── index.html      # Main HTML entry point
│   ├── js/             # JavaScript source files
│   └── scss/           # Sass stylesheets
└── package.json        # Dependencies and scripts
```

## Features Demonstrated

- Importing Stylescape via npm
- Zero-config Sass compilation
- Automatic JavaScript bundling
- Fast development server with HMR

## Learn More

- [Stylescape Documentation](https://github.com/stylescape/stylescape)
- [Parcel Documentation](https://parceljs.org/)

## License

MIT
