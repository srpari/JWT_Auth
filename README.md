Create a `.env` file in the root directory and add your JWT secret:
JWT_SECRET=your_jwt_secret_here

- `npm run dev`: Start the development server with nodemon
## Dependencies

- express: Web framework for Node.js
- jsonwebtoken: JWT implementation
- dotenv: Environment variable management
- nodemon: Development server with auto-reload

## API Endpoints

- `POST /login`: Authenticate user and receive JWT token
- Protected routes require a valid JWT token in the Authorization header
