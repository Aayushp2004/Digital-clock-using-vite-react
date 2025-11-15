React Vite Starter

A minimal and fast boilerplate to kickstart React development using Vite, featuring Hot Module Replacement (HMR), ESLint, and easy extensibility.

🚀 Features

⚡ Blazing fast development server powered by Vite

🔥 React with Hot Module Replacement (HMR)

🧹 ESLint pre-configured for high code quality

🔄 Supports Babel/OXC or SWC Fast Refresh plugins

🧩 Ready for TypeScript expansion

📁 Clean and simple project structure

📦 Prerequisites

Ensure you have the following installed:

Node.js (v14+ recommended)

npm or yarn

🛠️ Getting Started

Run these commands to start the project:

# Install dependencies
npm install

# Start the development server
npm run dev


Now open:
👉 http://localhost:5173

📂 Project Structure
project/
├── src/
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── public/
├── vite.config.js
└── package.json

🔌 Plugins

This starter supports both official React plugins:

@vitejs/plugin-react (Babel/OXC-based Fast Refresh)

@vitejs/plugin-react-swc (SWC-based Fast Refresh)

Choose either based on your performance preference.

npm create vite@latest my-app --template react-ts

⚙️ Customization

You can extend ESLint configuration, integrate the React Compiler, or adjust plugin settings based on your application's needs. Refer to the official Vite documentation for advanced options.
