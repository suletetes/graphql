# GraphQL Learning Repository

A comprehensive learning path for mastering GraphQL, organized into 13 progressive sections covering fundamental to advanced concepts.

## Learning Path

### 1. Fundamentals
- **Location**: `2 - Fundamentals/hello-world-main/`
- **Content**: Basic GraphQL setup with client-server architecture
- **Technologies**: Node.js, Express, GraphQL server

### 2. Schema Design
- **Location**: `3 - Schema/job-board-end-section-02/`
- **Content**: GraphQL schema design principles
- **Features**: Type definitions, queries, and basic resolvers

### 3. Queries
- **Location**: `4 - Queries/job-board-end-section-03/`
- **Content**: Advanced query techniques
- **Features**: Nested queries, query optimization

### 4. Error Handling
- **Location**: `5 - Errors/job-board-end-section-04/`
- **Content**: GraphQL error handling patterns
- **Features**: Custom error types, error formatting

### 5. Mutations
- **Location**: `6 - Mutations/job-board-end-section-05/`
- **Content**: Data modification operations
- **Features**: Create, update, delete operations

### 6. Authentication
- **Location**: `7 - Authentication/job-board-end-section-06/`
- **Content**: Authentication and authorization
- **Features**: JWT tokens, protected routes

### 7. Caching with Apollo Client
- **Location**: `8 - Caching with Apollo Client/job-board-end-section-07/`
- **Content**: Client-side caching strategies
- **Features**: Apollo Client cache management

### 8. Apollo React Integration
- **Location**: `9 - Apollo React Integration/job-board-end-section-08/`
- **Content**: React integration with GraphQL
- **Features**: React hooks, component integration

### 9. Data Loaders
- **Location**: `10 - Data Loaders/job-board-end-section-09/`
- **Content**: N+1 query problem solving
- **Features**: DataLoader implementation, batch loading

### 10. Pagination
- **Location**: `11 - Pagination/job-board-end-section-10/`
- **Content**: Pagination strategies
- **Features**: Cursor-based pagination, offset pagination

### 11. Subscriptions
- **Location**: `12 - Subscriptions/chat-main/`
- **Content**: Real-time data with subscriptions
- **Features**: WebSocket connections, real-time updates

### 12. TypeScript Code Generation
- **Location**: `13 - TypeScript Code Generation/job-board-typescript/`
- **Content**: Type-safe GraphQL development
- **Features**: GraphQL Code Generator, TypeScript integration

## Project Structure

Each section follows a consistent structure:

```
section-name/
├── client/          # Frontend application
│   ├── package.json
│   ├── src/
│   └── public/
└── server/          # GraphQL backend
    ├── package.json
    ├── schema.graphql
    ├── resolvers.js
    ├── auth.js
    ├── server.js
    ├── data/        # Sample data
    ├── db/          # Database files
    └── scripts/     # Utility scripts
```

## Technologies Used

- **Backend**: Node.js, Express, GraphQL Yoga/Apollo Server
- **Frontend**: React, Apollo Client
- **Database**: Various (SQLite, JSON files, in-memory)
- **Authentication**: JWT
- **Real-time**: WebSocket subscriptions
- **Type Safety**: TypeScript, GraphQL Code Generator

## Getting Started

1. Navigate to any section folder
2. Install dependencies:
   ```bash
   cd server && npm install
   cd ../client && npm install
   ```
3. Start the development servers:
   ```bash
   # Server
   cd server && npm start
   
   # Client
   cd client && npm start
   ```

## Learning Objectives

- Understand GraphQL schema design and type system
- Master query and mutation operations
- Implement authentication and authorization
- Handle errors effectively
- Optimize performance with caching and data loaders
- Implement real-time features with subscriptions
- Develop type-safe applications with TypeScript
- Integrate GraphQL with React applications

## Prerequisites

- Basic knowledge of JavaScript/TypeScript
- Familiarity with Node.js and npm
- Understanding of REST APIs (helpful but not required)

## Progress Tracking

The repository is organized sequentially, with each section building upon the previous one. Start with Section 2 (Fundamentals) and progress through to Section 13 (TypeScript Code Generation) for a complete learning experience.

## Additional Resources

- Review package.json files for dependencies and scripts
- Examine the schema.graphql files for GraphQL type definitions
- Study resolvers.js for business logic implementation

Happy learning! 🚀
