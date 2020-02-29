Locus (Backend)
=========

## Getting Started

1. Create the `.env` by using `.env.example` as a reference: `cp .env.example .env`
   For the environment variables, you will need:
   - Postgres SQL, you can run it locally or set up any cloud Postgres database
   - Clarifai API key, get one at https://www.clarifai.com/
2. Install dependencies: `npm i`
3. To reset database: `npm run db:reset`
4. Run the server: `npm run local`
5. Visit `http://localhost:8080/`

## Dependencies

- "bcrypt": "^3.0.8",
- "body-parser": "^1.19.0",
    - "chalk": "^2.4.2",
    - "clarifai": "^2.9.1",
    - "dotenv": "^2.0.0",
    - "express": "^4.17.1",
    - "heroku": "^7.38.1",
    - "morgan": "^1.9.1",
    - "pg": "^6.4.2",
    - "pg-native": "^3.0.0",
    - "socket.io": "^2.3.0"
