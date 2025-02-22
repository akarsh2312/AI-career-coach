# AI Career Coach

AI Career Coach is a web application designed to help users navigate their career paths by providing personalized insights and recommendations. The application leverages AI to analyze user data and offer tailored advice.

## Features

- User authentication and onboarding
- Personalized career insights and recommendations
- Skill assessments and tracking
- Resume and cover letter management
- Industry insights and trends

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- PostgreSQL database

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/ai-career-coach.git
   cd ai-career-coach

2. Install the dependencies:

    ```sh
    npm install

3. Set up the environment variables:
    Create a .env file in the root directory and add the following variables:

    ```sh
    DATABASE_URL=your_database_url
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
    CLERK_SECRET_KEY=your_clerk_secret_key
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
    GEMINI_API_KEY=your_gemini_api_key

4. Run Prisma migrations to set up the database schema:

    ```sh
    npx prisma migrate dev

5. Start the development server:

    ```sh
    npx run dev

The application will be available at http://localhost:3000.

### Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.



### Acknowledgements
Clerk for user authentication
Prisma for database ORM
Next.js for the React framework