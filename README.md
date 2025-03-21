# FullStack-Assignment-Pradeep-B-

Career Management Project

🚀 Project Overview

A simple web application for managing career opportunities, featuring:

Frontend built with HTML, CSS, AngularJS

Backend served via Netlify serverless functions

🛠 Technology Stack

Frontend: HTML, CSS, AngularJS 1.8.3

Backend: Serverless API (Netlify Functions)

Deployment:

Frontend: Hosted on Netlify Frontend

API: Hosted on Netlify Serverless Function

✨ Features

Add new career opportunities

Edit existing careers

Delete careers

View career listings

📂 Project Structure

├── frontend/
│   ├── index.html and other html fuiles
│   ├── styles.css and other css files 
│   └── app.js and other js files 
└── netlify/
    └── functions/
        └── career.js

🌐 Live Links

Frontend: https://sensational-tanuki-c3ead4.netlify.app/

API Endpoint: https://manualwebsite.netlify.app/.netlify/functions/career

🔎 How It Works

Frontend interacts with serverless API using HTTP requests (GET, POST, PUT, DELETE)

Data is fetched from or updated to the serverless function hosted on Netlify

🚀 Deployment Strategy

Frontend deployed separately on Netlify via netlify deploy --prod

Serverless API deployed under netlify/functions directory with its own endpoint URL

📈 Scalability Plan

The project can scale easily by:

Migrating API to a more robust backend (Node.js/Express or AWS Lambda)

Replacing static JSON data with a persistent database (MongoDB/Firebase)

Moving frontend to a modern framework (React/Angular) in future iterations



