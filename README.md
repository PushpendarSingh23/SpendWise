# SpendWise

SpendWise is a full-stack personal finance management application for tracking income, expenses, receipts, and financial analytics. The application also integrates Google Gemini for OCR-based receipt processing and automated extraction of transaction details.

## Features

- JWT-based authentication
- Income and expense tracking
- Custom transaction categories
- Financial analytics and charts
- Receipt upload and OCR-based transaction extraction
- Google Gemini integration for receipt processing
- Paginated transaction APIs
- Account management and account deletion
- Responsive React frontend
- Node.js/Express REST backend

## Tech Stack

### Frontend
- React
- Vite
- React Router
- Axios
- Tailwind CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- Google Gemini API

### Tools & Infrastructure
- Git
- GitHub
- Postman
- Nodemon
- dotenv
- MongoDB Atlas
- Netlify
- Render

## Architecture

```text
React + Vite
      |
      | REST APIs
      v
Node.js + Express
      |
      v
MongoDB Atlas

Receipt Image
      |
      v
Gemini OCR Processing
      |
      v
Structured Transaction Data
