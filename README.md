# Blog_Website

This is a blogging application inspired by Medium. The project is built from scratch using a modern tech stack and deployed on Cloudflare Workers for the backend and Vercel for the frontend.

## Features

- **User Authentication (JWT)**: Secure authentication system using JSON Web Tokens.
- **Skeleton Loading**: Enhances the user experience during data fetching.
- **Connection Pooling with Prisma**: Efficient database interactions with connection pooling.
- **Type Inference and Validation with Zod**: Ensures type safety and input validation.

## Tech Stack

### Frontend

- **React**: A JavaScript library for building user interfaces.
- **Vite**: A fast and modern build tool that enhances the development experience.
- **Skeleton Loading**: Improves the user experience with skeleton screens during data fetches.

### Backend

- **Cloudflare Workers**: Serverless functions for handling the backend logic.
- **TypeScript**: A strongly typed programming language that builds on JavaScript.
- **Prisma**: An ORM for interacting with the PostgreSQL database with connection pooling.
- **PostgreSQL**: A relational database used for storing app data.
- **Zod**: A TypeScript-first schema validation and type inference library.
- **JWT**: For secure user authentication with JSON Web Tokens.

## Getting Started

Follow these steps to set up the project locally.

### Prerequisites

- Node.js
- PostgreSQL

### Installation

1. Clone the repository:
   ```bash
   git clone [YOUR_REPO_URL]
   ```

2. Navigate to the project directory:
   ```bash
   cd [PROJECT_DIRECTORY]
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

### Configuration

1. Set up your environment variables. Create a `.env` file in the root directory and add the following:
   ```bash
   DATABASE_URL=your_postgres_connection_string
   JWT_SECRET=your_jwt_secret
   ```

2. Configure Cloudflare Workers and Vercel for deployment (refer to their respective documentation for detailed steps).

### Running the Application

1. Start the backend (Cloudflare Workers) and frontend (Vercel):
   - **Backend**: 
     ```bash
     npm run start:backend
     ```
   - **Frontend**: 
     ```bash
     npm run dev
     ```

2. Open `http://localhost:3000` to view the application in your browser.

## Deployment

### Backend

Deploy the backend using Cloudflare Workers. Refer to the Cloudflare Workers documentation for detailed deployment instructions.

### Frontend

Deploy the frontend on Vercel. Refer to the Vercel documentation for detailed deployment instructions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.
