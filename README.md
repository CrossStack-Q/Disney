
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Install latest version of npm

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the project
   ```sh
   git clone https://github.com/Halmesn/.git
   ```
2. Go to project directory and Install NPM packages
   ```sh
   npm install
   ```
3. Create a .env.local file
4. Request an API key from TMDB and add it to .env.local file
   ```sh
   NEXT_PUBLIC_TMDB_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```
5. Create a database at MongoDB and add connection url to .env.local file
   ```sh
   MONGODB_DATABASE=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```
6. Add a next-auth host url to .env.local file
   ```sh
   NEXTAUTH_URL=http://localhost:3000
   ```
7. Create a trial account at your database, adjust the email address in AuthForm onTrialClick function and add it's password to .env.local file
   ```sh
   NEXT_PUBLIC_TRIAL_ACCOUNT_PASSWORD=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
   ```
8. Start the application
   ```sh
   npm next start
   ```
