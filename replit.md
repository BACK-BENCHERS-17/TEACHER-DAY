# Overview

This is a Teachers' Day celebration website built as a fun, interactive experience for teachers. The application is a playful tribute created by "BACK ✘ BENCHERS" featuring animated elements, quizzes, emotional messages in Hinglish, and engaging user interactions. The website includes multiple pages with confetti effects, runaway buttons, quiz questions, and heartfelt appreciation messages designed to entertain and honor teachers.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Framework**: React 18 with TypeScript using Vite as the build tool
- **Routing**: Wouter for client-side routing with multiple themed pages
- **Styling**: Tailwind CSS with custom CSS variables and shadcn/ui component library
- **UI Components**: Radix UI primitives with custom styling (accordion, dialog, button, etc.)
- **State Management**: React Query (@tanstack/react-query) for server state management
- **Animations**: Custom CSS animations and effects for confetti, dancing elements, and interactive components

## Backend Architecture
- **Server**: Express.js with TypeScript
- **Development Setup**: Vite middleware integration for hot module replacement
- **Request Handling**: JSON and URL-encoded body parsing with custom logging middleware
- **Error Handling**: Centralized error handling middleware with status code management

## Data Storage Solutions
- **Database**: PostgreSQL with Drizzle ORM for type-safe database operations
- **Database Provider**: Neon Database (@neondatabase/serverless)
- **Schema Management**: Drizzle Kit for migrations and schema management
- **In-Memory Storage**: Fallback MemStorage implementation for development/testing
- **Schema**: User table with username/password fields using UUID primary keys

## External Dependencies
- **Database**: PostgreSQL via Neon Database serverless driver
- **UI Library**: Radix UI components for accessible, unstyled primitives
- **Form Handling**: React Hook Form with Zod validation via @hookform/resolvers
- **Date Utilities**: date-fns for date manipulation
- **Utility Libraries**: clsx and tailwind-merge for conditional styling
- **Development Tools**: Replit-specific plugins for development environment integration

## Key Features
- Interactive pages with animated elements and sound effects simulation
- Multi-page quiz system with runaway buttons and popup messages
- Confetti effects and floating animations
- Responsive design with mobile-first approach
- Bilingual content (English/Hindi) with emotional messaging
- Custom gradient backgrounds and visual effects
- Teacher appreciation theme with playful interactions

The architecture prioritizes user experience with smooth animations, interactive elements, and a playful design aesthetic suitable for a Teachers' Day celebration website.