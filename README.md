# PassworsSecretProject
# Website Authentication

This repository contains code for a simple website authentication system using Node.js and Express. To see how the final website should work, follow the instructions below.

## Prerequisites
Make sure you have Node.js and npm installed on your machine.

## Installation
1. Clone this repository to your local machine.
2. Open a terminal in the project directory.
3. Run the following command to install dependencies:
   ```bash
   npm install
## Usage
To start the application, run:
```bash
node solution.js

1. Open your web browser and navigate to http://localhost:3000.
2. You will be prompted to enter a password. The default password is set to "Hola".
3. Upon entering the correct password, you should be redirected to a secret page.

## Modifying Password

To modify the password, open the solution.js file and update the password variable at the beginning of the file.

### Important Note
This is a basic authentication system and should not be used for production purposes.
The password is currently stored in-memory and will be reset whenever the server restarts.
Security considerations and additional features should be implemented for a robust authentication system.
Feel free to explore and modify the code according to your needs. If you encounter any issues or have suggestions, please open an issue or create a pull request. Happy coding!
