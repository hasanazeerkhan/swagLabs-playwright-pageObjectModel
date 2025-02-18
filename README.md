Swag Labs Playwright Page Object Model

This repository contains an automated testing framework for the Swag Labs application using Playwright and the Page Object Model (POM) design pattern. The project demonstrates how to structure tests for maintainability and scalability.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Running Tests](#running-tests)
- [Contributing](#contributing)

## Features

- Automated testing of the Swag Labs application.
- Utilizes Playwright for cross-browser testing.
- Implements the Page Object Model for better test organization.
- Supports multiple browsers: Chromium, Firefox, and WebKit.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/) (version 12 or later)
- npm (comes with Node.js)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hasanazeerkhan/swagLabs-playwright-pageObjectModel.git
   cd swagLabs-playwright-pageObjectModel
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Install Playwright browsers:

   ```bash
   npx playwright install
   ```

## Usage

To run the tests, use the following command:

```bash
npx playwright test
```

You can also run tests in a specific browser by using:

```bash
npx playwright test --browser=firefox
```

## Folder Structure

The project follows a structured folder organization:

```
swagLabs-playwright-pageObjectModel/
├── tests/                # Contains test files
├── pages/                # Contains page object files
├── utils/                # Contains utility functions
├── playwright.config.js   # Playwright configuration file
└── package.json          # Project metadata and dependencies
```

## Running Tests

To run all tests, simply execute:

```bash
npx playwright test
```

To run a specific test file, use:

```bash
npx playwright test tests/example.spec.js
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.
