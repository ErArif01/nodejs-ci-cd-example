# nodejs-ci-cd-example

# Node.js CI/CD Example

This is a simple Node.js project that demonstrates Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions and deployment to Heroku.

## Project Structure

- **`index.js`**: Contains a basic Node.js function.
- **`test.js`**: Jest test file for testing the Node.js function.
- **`package.json`**: Configuration file for Node.js project.
- **`.github/workflows/main.yml`**: GitHub Actions workflow for CI/CD.
- **`.gitignore`**: File to specify files and directories to be ignored by Git.
- **`Procfile`**: Configuration file for Heroku deployment.
- **`jest.config.js`**: Configuration file for Jest testing.

## CI/CD Workflow

The project is configured with a GitHub Actions workflow that does the following:

- On each push to the `main` branch:
  - Checks out the code.
  - Sets up Node.js and installs dependencies.
  - Runs tests using Jest.
  - If tests pass, deploys the application to Heroku.

## Local Development

To run the project locally, follow these steps:

1. Install Node.js dependencies:

   ```bash
   npm install
