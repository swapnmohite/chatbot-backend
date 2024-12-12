# AI Chatbot with Spring Boot and Next.js

A chatbot application using Spring AI with Ollama integration and Next.js frontend.

## Prerequisites

- Java 21
- Node.js 18+
- Ollama
- Model: llama2:latest

## Project Structure
```
.
├── src/                    # Spring Boot backend
└── frontend/               # Next.js frontend (submodule)
```

## Setup & Running

### 1. Backend (Spring Boot)

```bash
# Install Ollama
curl https://ollama.ai/install.sh | sh

# Pull the model
ollama pull llama3.2:latest

# Run Spring Boot
./mvnw spring-boot:run
```

### 2. Frontend (Next.js)

```bash
# Navigate to frontend
cd chatbot

# Install dependencies
npm install

# Run development server
npm run dev
```

Access the application at `http://localhost:3000`

## Features

- Real-time chat interface
- Streaming responses
- Code highlighting
- Markdown support

## Tech Stack

- Backend: Spring Boot 3.3.5, Spring AI
- Frontend: Next.js 14, Tailwind CSS, ShadCN
- LLM: Ollama with llama3.2
