# 🚀 How to Clone and Run This Project

This guide will help you set up and run the project locally.

### 1. Install Node.js
1. Download and install Node.js from [https://nodejs.org/](https://nodejs.org/).
2. After installation, open **Command Prompt (Windows)** or **Terminal (Mac/Linux)** and run the following commands to verify installation:
   ```bash
   node -v
   npm -v
You should see version numbers for both Node.js and npm.

### 2. Clone the Repository
Open Command Prompt or Terminal.

Navigate to the folder where you want to clone the project.

Run the following command:

```bash

git clone <repository-url>
Replace <repository-url> with the URL of this repository.
```

Navigate into the project directory:


```bash

cd <project-folder-name>
```

### 3. Install Project Dependencies
Inside the project folder, run the following command:

```bash

npm install
```

This will download all the dependencies required to run the app.


### 4. Set Up Firebase Environment Variables
Ask the project owner for the .env file, or create a new .env file in the project root directory.


Add the following lines to the .env file:

env
```
REACT_APP_API_KEY=<your-api-key>
REACT_APP_AUTH_DOMAIN=<your-auth-domain>
REACT_APP_PROJECT_ID=<your-project-id>
REACT_APP_STORAGE_BUCKET=<your-storage-bucket>
REACT_APP_MESSAGING_SENDER_ID=<your-messaging-sender-id>
REACT_APP_APP_ID=<your-app-id>
Replace <your-api-key> and other placeholders with your own Firebase project details.
```

 ### 5. Start the App
In the project folder, run:

```bash

npm start
```
Your browser will open automatically at http://localhost:3000.


You should see the app running!


### 6. Troubleshooting
- If you see errors, check the following:

- Node.js and npm are installed correctly.

- You are in the correct project folder.

- The .env file exists and contains the correct values.

- If you need help, copy the error message and:

- Search online for a solution.

- That’s it! 🎉 Enjoy using the app!

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
