# Orama

Orama is a student-focused study planner and AI-powered productivity app. It helps users organize schedules, track deadlines, manage reminders, and plan study sessions with the support of an AI assistant that can add, list, and complete tasks.

## Team & Project Context

**Project Type:** Collaborative university group project (2025)

**Team:**
- Nompumelelo Nthulane (@nompumelelonthulane-a11y)
- Siyabulela (@SIYABULELA11)

This project was developed collaboratively as part of a university group assignment. This repository is shared here as a portfolio copy to highlight individual contributions while giving full credit to the team.

**My Specific Contributions:**
- Contributed to the frontend development of the Orama application using React and TypeScript
- Helped build and style key application pages and components
- Collaborated on the team's Git workflow, including feature branches and review processes
- Supported integration work and helped complete project tasks during the final stages of development

Individual commit history and code authorship can be reviewed in the original repository at github.com/SIYABULELA11/Orama.

## Overview

This project combines:

- A React + TypeScript frontend for scheduling and study management
- A Vite-based frontend workflow for rapid development
- An Express API for AI chat and task tools
- OpenAI integration for conversational planning support
- Accessibility-focused UI patterns for studying and productivity workflows

## Key Features

- Study planning dashboard
- My schedules management
- Upcoming deadlines tracking
- Reminders and task tracking
- AI assistant for study and scheduling tasks
- Accessibility and support pages
- User settings and profile management
- Responsive UI for desktop and mobile

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- React Router
- Express
- OpenAI API
- TanStack Query

## Project Structure

Key folders and files:

- .github/workflows - CI/CD deployment workflow
- server/chat.ts - Express AI server
- src/components - Reusable React components
- src/pages - Application pages (Study Planner, Reminders, AI Assistant, etc.)
- src/hooks - Custom React hooks
- src/lib - Utility functions
- src/App.tsx - Main application component
- package.json - Dependencies and scripts
- vite.config.ts - Vite configuration

## Getting Started

### Prerequisites

- Node.js 18+
- npm or Bun
- An OpenAI API key for AI features

### Installation

npm install

Or with Bun:

bun install

### Environment Variables

Create a .env file in the project root:

OPENAI_API_KEY=your_openai_api_key_here
PORT=8787

Note: The .env file is excluded from version control via .gitignore. Do not commit API keys to a public repository.

### Run the app

Start the frontend:

npm run dev

Start the AI server:

npm run server

### Production build

npm run build

Preview the production build:

npm run preview

## Available Scripts

- npm run dev - Starts the Vite development server
- npm run server - Runs the Express AI server
- npm run build - Builds the frontend for production
- npm run lint - Runs ESLint checks
- npm run preview - Serves the production build locally

## AI Assistant

The backend server in server/chat.ts exposes an AI chat endpoint and supports tools such as:

- add_task
- list_upcoming
- complete_task

This allows the assistant to help manage study tasks and reminders through natural language interaction.

## API Endpoints

The Express server includes:

- POST /api/ai/chat - Send chat messages to the OpenAI-powered assistant
- GET /api/tasks - Retrieve current in-memory tasks
- GET /api/health - Health check for the server

## Notes

- The app uses HashRouter, so routes are managed via URL fragments.
- The project is structured around a student productivity workflow with AI support focused on scheduling and task management.
- Some assets and screenshots are present in the repo for product demos and mockups.

## License

No explicit license file is currently present in the repository. This project should be considered unlicensed unless an additional license is added.
