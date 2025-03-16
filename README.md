# Team Tracker

A comprehensive team collaboration platform designed to streamline work tracking, task management, and team organization with enhanced productivity features.

## Features

- Full authentication system with user registration and login
- Team verticals management
- Team member management with vertical assignments
- Task management with regular and custom deadlines
- Priority levels for tasks
- Light/dark mode theme support

## Tech Stack

- Frontend: React.js with Tailwind CSS and shadcn/ui
- Backend: Node.js with Express
- Database: PostgreSQL with Drizzle ORM
- Authentication: Passport.js with session-based auth

## Development

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

The application will be available at http://localhost:5000

## Environment Variables

The following environment variables are required:

- `DATABASE_URL`: PostgreSQL database connection string
- `SESSION_SECRET`: Secret key for session management

## Deployment

This project is configured for deployment on Replit.
