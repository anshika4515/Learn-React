# React Installation with Bun and Vite

This guide will help you set up a React application using **Bun** as the package manager and **Vite** for fast development with Hot Module Replacement (HMR).

## Step 1: Download Node.js

Before proceeding, make sure you have **Node.js** installed. If you don't have it, you can download it from [Node.js official website](https://nodejs.org/).

## Step 2: Install Bun

Bun is a fast JavaScript runtime that can be used to develop React applications. To install Bun, run the following command:

```bash
npm i -g bun
This will globally install Bun on your system.

Step 3: Create the React Project with Bun
To create a new React project with Vite, use the following Bun command:

bash
Copy
bun create vite
Follow the prompts to set up your React project.

Step 4: Start the Development Server
Once the project is created, navigate to your project folder and run the following command to start the development server:

bash
Copy
bun run dev
This will start the Vite server and open your application in the browser.

Project Structure
node_modules
This folder contains all the necessary libraries and dependencies for your React application. It is automatically managed by Bun.

public
The public folder contains all the static files like images, videos, fonts, etc. These assets are served directly from the server.

src
The src folder contains all the source code of your React application. The main entry point for your application is located here.

main.jsx: This is the entry point for your React application, where you typically render your root component.

React + Vite Setup with Fast Refresh
In the Vite project setup, you can choose between two official plugins for Fast Refresh:

@vitejs/plugin-react: Uses Babel for Fast Refresh.

@vitejs/plugin-react-swc: Uses SWC for Fast Refresh.

You can choose either plugin based on your preference. The default plugin is @vitejs/plugin-react.

Expanding the ESLint Configuration
If you're developing a production application, we recommend using TypeScript and enabling type-aware lint rules. This helps ensure that your code is type-safe and adheres to best practices.

To set up TypeScript, check out the TS template, which integrates TypeScript and typescript-eslint for linting.

Naming Conventions in React
Here are some common naming conventions to follow when building React applications:

Components: Use PascalCase for component names (e.g., Header, NavBar).

Files: Use camelCase for file names (e.g., myComponent.jsx, mainPage.jsx).

State Variables: Use camelCase for state variables (e.g., const [userInfo, setUserInfo] = useState()).

Props: Use camelCase for props (e.g., name, onClick).

Hooks: Name custom hooks with the use prefix (e.g., useFetchData, useFormValidation).