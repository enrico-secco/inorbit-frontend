<div align="center">
    <img src="public/logo.png" alt="Inorbit Frontend Logo">
</div>

# Inorbit Frontend

A web application designed to help users set, track, and complete their weekly goals. The app provides a clean and intuitive interface for managing goals, tracking progress, and visualizing achievements.

## Features

- **Goal Management**: Create, update, and track weekly goals.
- **Progress Tracking**: Visualize your progress with a progress bar and percentage completion.
- **Pending Goals**: View and complete pending goals for the week.
- **Weekly Summary**: See a detailed breakdown of completed goals by day.
- **Responsive Design**: Optimized for various screen sizes.
- **Interactive UI**: Smooth and interactive user experience using modern UI components.

## Technologies and Libraries Used

- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A strongly typed programming language that builds on JavaScript.
- **Vite**: A fast build tool and development server.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **react-hook-form**: For managing forms and input validation.
- **zod**: For schema-based form validation and type-safe data parsing.
- **@tanstack/react-query**: For managing server state and caching API requests.
- **dayjs**: For date manipulation and formatting.

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Run the backend [inorbit-backend](https://github.com/enrico-secco/inorbit-backend/tree/main)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd inorbit-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Ensure the backend is running:
    - Clone the backend repository from [inorbit-backend](https://github.com/enrico-secco/inorbit-backend/tree/main):
      ```bash
      git clone https://github.com/enrico-secco/inorbit-backend.git
      cd inorbit-backend
      ```  
    - Follow the setup instructions in the backend repository's [README.md](https://github.com/enrico-secco/inorbit-backend/tree/main#readme) to start the backend server.

4. Start the development server for the frontend:
   ```bash
   npm run dev
   ```