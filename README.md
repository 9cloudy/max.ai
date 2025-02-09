# Max.AI

Max.AI is an AI-powered assistant built with **Next.js** and **PostgreSQL**, designed to provide interactive chat capabilities similar to ChatGPT. It supports chat history saving and authentication via **SMTP**.

## Features

- **AI-powered chat**: Engage in conversations with an intelligent assistant.
- **Chat history storage**: Save and retrieve past conversations.
- **Authentication via SMTP**: Secure login and user authentication.
- **PostgreSQL database**: Reliable data storage and management.
- **Built with Next.js**: Fast and efficient web framework for a smooth user experience.

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/9cloudy/max.ai.git
   cd max.ai
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env.local` file in the root directory and configure the following variables:
   ```env
       DATABASE_URL=""
       GEMINI_API_KEY=""
       ADMIN_EMAIL=""
       ADMIN_PASSKEY=""
       ADMIN_JWT_SECRET = ""
   ```

4. **Run database migrations:**
   ```sh
   npx prisma migrate dev
   ```

5. **Start the development server:**
   ```sh
   npm run dev
   ```
   The application will be available at `http://localhost:3000`.

## Deployment

To deploy Max.AI, use a cloud hosting provider that supports Next.js and PostgreSQL, such as **Vercel** or **Railway**.

## Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.
