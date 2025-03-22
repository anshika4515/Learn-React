
# React Installation with Bun and Vite

This guide will help you set up a React application using **Bun** as the package manager and **Vite** for fast development.

## Step 1: Download Node.js

Before proceeding, make sure you have **Node.js** installed.

## Step 2: Install Bun

To install Bun, run the following command:

```
npm i -g bun
```

## Step 3: Create the React Project with Bun

```
bun create vite
```

## Step 4: Start the React Project with Bun 

```
bun run dev
```


# Project Structure

**node_modules:**
This folder contains all the necessary libraries and dependencies for your React application.

**public:**
The public folder contains all the static files like images, videos, fonts, etc. These assets are served directly from the server.

**src:**
The src folder contains all the source code of your React application. The main entry point for your application is located here.

**main.jsx:** This is the entry point for your React application, where you typically render your root component.


# Naming Conventions in React

Here are some common naming conventions to follow when building React applications:

**Components:** Use PascalCase for component names (e.g., Header, NavBar).

**Files:** Use camelCase for file names (e.g., myComponent.jsx, mainPage.jsx).

**State Variables:** Use camelCase for state variables (e.g., const [userInfo, setUserInfo] = useState()).

**Props:** Use camelCase for props (e.g., name, onClick).

**Hooks:** Name custom hooks with the use prefix (e.g., useFetchData, useFormValidation).
