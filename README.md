# Gen-AI

A simple Generative AI application built using Node.js, and Google's Gemini API.

## Prerequisites

- Node.js installed on your system
- Google Gemini API Key

## Installation

### 1. Initialize the Project
npm init -y

### 2. Install Dependencies
npm install express cors dotenv @google/genai

### 3. Configure Environment Variables

Create a `.env` file in the project root directory and add the following:

GEMINI_API_KEY=YOUR_NEW_API_KEY

Replace `YOUR_NEW_API_KEY` with your actual Gemini API key.

### 4. Update package.json

Add the following property to your `package.json` file:
{
  "type": "module"
}

## Running the Application

Start the backend server using:

node DSA.js

Expected output:
Server running on http://localhost:3000

## Launch the Frontend

Open the `index.html` file in your browser by double-clicking it.

## Project Structure

Gen-AI/
│
├── DSA.js
├── index.html
├── package.json
├── .env
└── node_modules/
```

## Technologies Used

- Node.js
- Google Gemini API
- CORS
- Dotenv
- HTML, CSS, JavaScript

## Notes

- Ensure the backend server is running before opening the frontend.
- Verify that the Gemini API key is correctly configured in the `.env` file.
- If you make changes to environment variables, restart the server.

## Author

Developed as part of a Generative AI learning project.# Gen-AI

Run
npm init -y
npm i @google/genai
npm install express cors dotenv @google/genai

create .env and add below code
GEMINI_API_KEY=YOUR_NEW_API_KEY

In package.json
replace value of type to module
"type":"module"

Then start backend

node DSA.js
Output:
Server running on http://localhost:3000

and then double click on index.html
