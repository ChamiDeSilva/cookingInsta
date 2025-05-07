# CookingApp

A social learning platform that helps users share posts, manage learning plans, and receive notifications.

## Project Structure

The project is divided into two main components:
- **Backend**: Spring Boot application with JWT authentication, JPA, and REST controllers
- **Frontend**: React application with routing, auth context, and service integration

## Team Division

### Part 1: Core & Authentication
- Backend: Security, User Management, Config
- Frontend: Auth components, Context setup
- Project setup and coordination

### Part 2: Posts Module
- Backend: Post controllers, services, repositories, models
- Frontend: Post components, services
- Note: Post Feed is the primary content of the application that users see when clicking on the ChamiApp brand

### Part 3: Learning Plans Module
- Backend: Learning plan controllers, services, repositories, models
- Frontend: Learning plan components, services

### Part 4: Notifications & Common Components
- Backend: Notification controllers, services, repositories
- Frontend: Notification components, common components, styling

## Development Guidelines

1. Clone the repository
2. Create a branch for your assigned module: `git checkout -b feature/[your-module]`
3. Work on your assigned components
4. Regularly commit changes with descriptive messages
5. Push changes to your branch
6. Create pull requests when your module is ready to be merged

## Getting Started

### Backend
1. Open the backend directory in your IDE
2. Run the application using Maven or your IDE's Spring Boot tools
3. The API will be available at `http://localhost:8080`

### Frontend
1. Navigate to the frontend directory
2. Run `npm install` to install dependencies
3. Run `npm run dev` to start the development server
4. Access the application at `http://localhost:5173`
