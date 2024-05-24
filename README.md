// DESCRIBTION
Auth Secret Keeper is a web application that provides authentication using both local and Google strategies.
It securely stores user credentials and secrets in a Postgres database.
After logging in, users are redirected to a secret keeper page where they can manage their personal secrets.

//Features
Local Authentication: Users can register and log in using a username and password.
Google Authentication: Users can log in using their Google account.
Session Management: Secure session handling using express-session.
Secret Keeper: Store and manage personal secrets associated with user accounts.
Environment Variables: Configuration using environment variables for security and flexibility.
MongoDB Integration: Persistent storage of user credentials and secrets

//Install dependencies:
npm install

//Set up environment variables:

Create a .env file in the root directory and add the following:
PORT=3000
POSTGRES_URI=your_mongodb_connection_string
SESSION_SECRET=your_session_secret
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_CALLBACK_URL=http://localhost:3000/auth/google/callback

(Replace the placeholders with your actual values)

//Start the application:
npm start
The app will be running at http://localhost:3000.

//Technologies
Node.js and Express for server-side logic
Passport.js for authentication
MongoDB with Mongoose for database operations
EJS for templating and rendering views
dotenv for environment variable management
bcryptjs for password hashing



