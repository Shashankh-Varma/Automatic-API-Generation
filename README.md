LoopBack 4 API Application
This application was generated using the LoopBack 4 CLI. It is a modern, TypeScript-based backend service designed for scalability and maintainability.

🚀 Getting Started
Prerequisites
Node.js (LTS version recommended)

NPM (installed with Node)

Installation
By default, dependencies are installed during generation. If you change package.json, run:

Bash
npm install
To install only the exact versions resolved in package-lock.json:

Bash
npm ci
Running the App
Bash
npm start
Once started, you can access the application at: http://127.0.0.1:3000

🛠 Project Commands
Build & Development
npm run build: Incrementally build the project.

npm run rebuild: Force a full build by cleaning up cached artifacts.

node .: Run the application while skipping the build step.

Code Quality
npm run lint: Check for code style and formatting issues.

npm run lint:fix: Automatically fix linting and style issues.

npm test: Run the automated test suite.

Database & Documentation
npm run migrate: Sync your database schemas with your defined models.

npm run openapi-spec: Generate an OpenAPI (Swagger) specification file.

Containerization
npm run docker:build: Build a Docker image for the application.

npm run docker:run: Run the application inside a Docker container.

📂 Project Structure
src/models: Defines the data shape and business entities.

src/repositories: Handles data access and connects models to data sources.

src/controllers: Implements the REST API and contains the business logic.

src/datasources: Configurations for database or external service connections.

📖 Learn More
To continue adding features, such as new controllers or custom middleware, please check out the LoopBack 4 documentation.