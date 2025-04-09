# Basic Company Career Page

## Career Management Project

🚀 **Project Overview**

A simple web application for managing career opportunities, featuring:

-   Frontend built with HTML, CSS, AngularJS 1.8.3
-   Backend served via Netlify serverless functions

🛠️ **Technology Stack**

-   **Frontend:** HTML, CSS, AngularJS 1.8.3
-   **Backend:** Serverless API (Netlify Functions)
-   **Deployment:**
    -   Frontend: Hosted on Netlify Frontend
    -   API: Hosted on Netlify Serverless Function

✨ **Features**

-   Add new career opportunities
-   Edit existing careers
-   Delete careers
-   View career listings

📂 **Project Structure**

├── frontend/
│   ├── index.html and other html files
│   ├── styles.css and other css files
│   └── app.js and other js files
└── netlify/
└── functions/
└── career.js


🌐 **Live Links**

-   **Frontend:** [https://sensational-tanuki-c3ead4.netlify.app/](https://sensational-tanuki-c3ead4.netlify.app/)
-   **API Endpoint:** [https://manualwebsite.netlify.app/.netlify/functions/career](https://manualwebsite.netlify.app/.netlify/functions/career)

🔎 **How It Works**

-   Frontend interacts with serverless API using HTTP requests (GET, POST, PUT, DELETE).
-   Data is fetched from or updated to the serverless function hosted on Netlify.

🚀 **Deployment Strategy**

-   Frontend deployed separately on Netlify via `netlify deploy --prod`.
-   Serverless API deployed under `netlify/functions` directory with its own endpoint URL.

📈 **Scalability Plan**

The project can scale easily by:

-   Migrating API to a more robust backend (Node.js/Express or AWS Lambda).
-   Replacing static JSON data with a persistent database (MongoDB/Firebase).
-   Moving frontend to a modern framework (React/Angular) in future iterations.

🧪 **Unit Tests**

Basic unit tests have been added to ensure the reliability of critical components.

-   **Frontend:** We've included basic unit tests for AngularJS components using Jasmine and Karma. These tests verify the functionality of our controllers and services, ensuring they behave as expected.

-   **Backend:** Unit tests have been added to the Netlify serverless function to test the API endpoints. These tests verify that the CRUD operations (Create, Read, Update, Delete) are working correctly and handle various scenarios.

-   To run the frontend tests, navigate to the frontend directory and run `npm test`. To run the backend tests, navigate to the netlify/functions directory and run `npm test`.

⚙️ **CI/CD Configuration**

A basic CI/CD pipeline has been set up using Netlify's built-in CI/CD features.

-   **Automated Builds:** Netlify automatically builds and deploys the frontend and backend whenever changes are pushed to the repository.
-   **Testing:** The pipeline includes steps to run unit tests before deployment, ensuring that only tested and working code is deployed.
-   **Deployment:** Upon successful test execution, Netlify deploys the updated code to the live site.

To further improve the CI/CD pipeline, consider adding:

-   Automated linting and code formatting checks.
-   End-to-end testing using tools like Cypress or Protractor.
-   Integration with a version control system (e.g., GitHub, GitLab) for automated deployments on push or merge.
-   Deployment to staging environments for pre-production testing.
