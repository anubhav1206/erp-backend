# TCET ERP System

The TCET ERP System is a project designed to streamline and automate daily operations at TCET. It aims to provide a comprehensive solution for managing various aspects of college operations, including admissions, registration, student records, financial aid, course scheduling, and fees. The ERP system consists of multiple integrated modules that support these functions.

## Technology Stack

The backend of the TCET ERP System is developed using Node.js and Express framework. The choice of Node.js and Express is based on their versatility and ability to handle a modular project like this. The database used is MongoDB, a NoSQL database that complements the modular nature of the project.

## Installation

To start working on the TCET ERP System, follow the steps below:

1. Clone the repository: Begin by cloning the repository to your local machine using the `git clone` command and specifying the repository's URL.

2. Set up MongoDB: Create a MongoDB Atlas database and obtain the connection URI. Save the connection URI as `DB_URL` in your `.env` file.

3. Generate token secret: Use the following command to generate a token secret required for JWT authentication and save it as `TOKEN_SECRET` in your `.env` file:

```
node -e "console.log(require('crypto').randomBytes(256).toString('base64'));
```

4. Install dependencies: Navigate to the root directory of the project and install the required dependencies by running `npm install`. The dependencies are listed in the `package.json` file.

5. Run the server: Start the server by running `npm run serverstart` or `npm run serverstartWin` depending on your operating system.

## Contributing

If you would like to contribute to the TCET ERP System, please follow the guidelines below:

1. Choose an issue or feature: Identify an existing issue or propose a new feature that you would like to work on. If necessary, create a new issue in the repository.

2. Fork the repository: Fork the repository to create your copy of the project in your GitHub account.

3. Clone the repository: Clone the forked repository to your local machine using the `git clone` command.

4. Create a new branch: Before making any changes, create a new branch in your local repository to isolate your changes from the main branch.

5. Make your changes: Implement the necessary changes or additions in your branch, following the project's coding style and conventions.

6. Test your changes: Thoroughly test your changes to ensure they function as intended and do not introduce new issues.

7. Commit your changes: Commit your changes to your local branch using the `git commit` command with an appropriate commit message.

8. Push your changes: Push your local branch to your forked repository on GitHub using the `git push` command.

9. Open a pull request: Open a pull request in the original repository to propose merging your changes. Provide a clear description of your changes and their benefits. Be prepared to address any feedback or change requests from the project maintainers.

Please note that collaboration and communication with the project maintainers and other contributors are crucial to ensure your changes align with the project's goals and direction.

Feel free to refactor this README file as necessary to keep it up to date and informative.
