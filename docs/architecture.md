# System Architecture

The system follows a modular architecture consisting of frontend, backend, NLP processing, and database components.

## Architecture Flow

User → Frontend → Backend → NLP Processing → Decision Engine → Response Generation → User

## Components

### 1. Frontend (React)
- Provides chat interface
- Sends user messages to backend
- Displays chatbot responses

### 2. Backend (Node.js + Express)
- Handles API requests
- Manages user sessions
- Coordinates NLP and logic processing

### 3. NLP Module
- Detects user intent
- Processes input text

### 4. Decision Engine
- Applies rule-based logic
- Analyzes financial data

### 5. Database (MongoDB)
- Stores user financial profiles
- Maintains conversation data

### 6. Response Generator
- Generates final chatbot reply
- Uses templates or NLP models (HuggingFace)