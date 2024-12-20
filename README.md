# ECommerce-Sales-Chatbot

An AI-powered chatbot designed to enhance the e-commerce shopping experience by facilitating efficient product search, exploration, and purchase processes.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technology Stack](#technology-stack)
4. [Setup Instructions](#setup-instructions)
5. [Usage Guide](#usage-guide)
6. [API Documentation](#api-documentation)

## Project Overview

This E-Commerce Sales Chatbot is designed to revolutionize online shopping experiences by providing an interactive, AI-driven interface for customers. It allows users to search for products, apply filters, and make purchases directly through a chat interface, combining the convenience of messaging with the functionality of an e-commerce platform.

## Features

- User Authentication (Login/Register)
- Natural Language Product Search
- Real-time Chat Interface
- Product Filtering (Category and Price Range)
- Integrated Purchase Functionality
- Chat History Storage and Retrieval
- Responsive Design (Desktop, Tablet, Mobile)

## Technology Stack

### Frontend
- Next.js (React Framework)
- TypeScript
- Tailwind CSS
- shadcn/ui Components

### Backend
- Flask (Python Web Framework)
- SQLite Database
- Flask-CORS for handling Cross-Origin Resource Sharing

## Setup Instructions

### Prerequisites
- Python 3.8+
- Node.js 14+
- npm or yarn

### Backend Setup
Navigate to the backend directory:
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
python setup_db.py

### Setup the frontend
cd frontend
npm install


### Start the backend server:
python app.py

### Start the frontend development server:
npm run dev


## Project Structure
E-Commerce-Sales-Chatbot/
├── backend/           # Flask server and database
├── frontend-next/    # Next.js frontend application
├── docs/            # Project documentation
└── README.md        # Project overview and setup guide



-Open http://localhost:3000 in your browser

## Usage

1. Register or log in to start a chat session
2. Use natural language to search for products
3. Apply filters to refine search results
4. Purchase products directly through the chat interface


