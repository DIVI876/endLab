# endLab Project

## Overview
endLab is a web application built using TypeScript and Express. This project serves as a template for creating RESTful APIs with a structured approach, utilizing controllers and routes for better organization.

## Project Structure
```
endLab
├── src
│   ├── app.ts                # Entry point of the application
│   ├── controllers           # Contains the controllers for handling requests
│   │   └── index.ts          # Index controller for the root route
│   ├── routes                # Contains the route definitions
│   │   └── index.ts          # Route setup for the application
│   └── types                 # Type definitions for the application
│       └── index.ts          # Custom request and response interfaces
├── Dockerfile                 # Dockerfile for building the application image
├── docker.yaml                # Docker Compose configuration
├── .github
│   └── workflows
│       └── docker-deploy.yaml # GitHub Actions workflow for deployment
├── package.json               # NPM configuration and dependencies
├── tsconfig.json             # TypeScript configuration
└── README.md                 # Project documentation
```

## Getting Started

### Prerequisites
- Node.js (version X.X.X)
- npm (version X.X.X)
- Docker (version X.X.X)

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/DIVI876/endLab.git
   ```
2. Navigate to the project directory:
   ```
   cd endLab
   ```
3. Install dependencies:
   ```
   npm install
   ```

### Running the Application
To run the application locally, use the following command:
```
npm start
```

### Docker
To build and run the application using Docker, execute:
```
docker build -t endlab .
docker run -p 3000:3000 endlab
```

### Deployment
The project includes a GitHub Actions workflow for deploying the Docker container. Ensure that your repository settings are configured to allow GitHub Actions to run.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.