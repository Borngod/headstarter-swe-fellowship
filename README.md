# Headstarter SWE Fellowship Projects

Welcome to our collaborative projects for the Headstarter SWE Fellowship! This repository contains two main projects: a Random Quote Machine (frontend) and a URL Shortener (backend).

## Table of Contents

- [Introduction](#introduction)
- [Team Members](#team-members)
- [Project Structure](#project-structure)
- [Project Details](#project-details)
  - [Random Quote Machine](#random-quote-machine)
  - [URL Shortener](#url-shortener)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This repository is a part of our preparation for the Headstarter SWE Fellowship. We have divided our team into two groups to work on two different projects from freeCodeCamp:
1. **Random Quote Machine** - A frontend project
2. **URL Shortener** - A backend project

## Team Members

- **Frontend Team**
  - Hilda
  - Baby Eugenia

- **Backend Team**
  - Bernard
  - Aaron

## Project Structure

```
.
├── frontend
│   └── random-quote-machine
│       ├── public
│       ├── src
│       ├── package.json
│       ├── README.md
│       └── ...
└── backend
    └── url-shortener
        ├── src
        ├── package.json
        ├── README.md
        └── ...
```

## Project Details

### Random Quote Machine

The Random Quote Machine is a frontend project where users can get random quotes and tweet them. 

#### Technologies
- React
- HTML/CSS
- JavaScript

#### Tasks
- Fetching random quotes from an API
- Displaying quotes in a user-friendly interface
- Allowing users to share quotes on Twitter

### URL Shortener

The URL Shortener is a backend project that allows users to shorten long URLs and redirect them.

#### Technologies
- Node.js
- Express
- MongoDB

#### Tasks
- Creating endpoints for shortening URLs
- Storing shortened URLs in a database
- Redirecting users to the original URL when accessing the short URL

## Getting Started

To get started with any of the projects, follow the instructions below.

### Prerequisites

- Node.js
- npm (Node Package Manager)
- MongoDB (for the backend project)

### Installation

#### Frontend (Random Quote Machine)

1. **Navigate to the frontend directory:**

    ```bash
    cd frontend/random-quote-machine
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Run the project:**

    ```bash
    npm start
    ```

#### Backend (URL Shortener)

1. **Navigate to the backend directory:**

    ```bash
    cd backend/url-shortener
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Run the project:**

    ```bash
    npm start
    ```
## Workflow

### Branching

1. **Create a new branch for your feature or bugfix:**

    ```bash
    git checkout -b feature-name
    ```

2. **Regularly pull from the main branch to keep your branch updated:**

    ```bash
    git checkout main
    git pull origin main
    git checkout feature-name
    git merge main
    ```

### Pull Requests

1. **Commit your changes and push to your branch:**

    ```bash
    git add .
    git commit -m "Description of changes"
    git push origin feature-name
    ```

2. **Create a pull request to merge your changes into the main branch.**

### Merge Conflicts

1. **If there are merge conflicts, resolve them locally:**

    ```bash
    git checkout feature-name
    git merge main
    ```

2. **Resolve conflicts in your editor, then commit and push:**

    ```bash
    git add .
    git commit -m "Resolved merge conflicts"
    git push origin feature-name
    ```

3. **Update your pull request once conflicts are resolved.**
## Contributing

We follow a collaborative approach and encourage team members to contribute effectively. Please adhere to the following guidelines:

1. **Fork the repository.**
2. **Create a new branch** for your feature or bugfix.
3. **Commit your changes** with descriptive messages.
4. **Push to your branch** and create a pull request.

For detailed guidelines, refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please contact:

- Hilda (Frontend) - [Email](mailto:hilda@example.com)
- Baby Eugenia (Frontend) - [Email](mailto:babyeugenia@example.com)
- Bernard (Backend) - [Email](mailto:bernard@example.com)
- Aaron (Backend) - [Email](mailto:aaron@example.com)

