# Auth Secret Keeper

Auth Secret Keeper is a web application that provides authentication using both local and Google strategies. It securely stores user credentials and secrets in a Postgres database. After logging in, users are redirected to a secret keeper page where they can manage their personal secrets.

## Features

- **Local Authentication:** Users can register and log in using a username and password.
- **Google Authentication:** Users can log in using their Google account.
- **Session Management:** Secure session handling using express-session.
- **Secret Keeper:** Store and manage personal secrets associated with user accounts.
- **Environment Variables:** Configuration using environment variables for security and flexibility.
- **Postgres Integration:** Persistent storage of user credentials and secrets.

## Installation

### Install dependencies

```bash
npm install

### Start the application

```bash
npm start
```
### Technologies
- **Node.js and Express for server-side logic
- **Passport.js for authentication
- **Postgres for database operations
- **EJS for templating and rendering views
- **dotenv for environment variable management
- **bcryptjs for password hashing

