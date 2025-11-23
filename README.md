🚀 AI Component Generator
An AI-powered UI component generator built using ReactJS, Tailwind CSS, Monaco Editor & Gemini API

The AI Component Generator is a modern web application that lets users describe a UI component and automatically generates code using the Gemini AI API. Users can preview, edit, copy, and export the generated UI components in multiple frameworks like HTML + CSS, Tailwind CSS, Bootstrap, and more.

📽️ Project Summary (From Video Breakdown)
🔹 What This Project Does

Takes a user description (e.g., “Create a login form with gradient background”).

Lets the user choose a framework (HTML+CSS, Tailwind, Bootstrap, etc.).

Sends the request to Gemini AI API and generates real component code.

Displays the output inside an advanced Monaco Editor.

Shows a live preview inside an iframe.

Allows users to copy, download, or open the generated code.

🛠️ Tech Stack
Technology	Usage
ReactJS	Main frontend framework
Tailwind CSS	Styling and layout
Gemini AI API	Code generation
React Router	Navigation
React Icons	UI Icons
Monaco Editor	Code editor panel
React Loader Spinner	Loading animations
Toastify	Notifications
✨ Key Features
🧠 AI Powered Component Generation

Generate UI components from text prompts using Gemini API.

🎨 Multi-Framework Support

Choose frameworks such as:

HTML + CSS

HTML + Tailwind

HTML + Bootstrap

HTML + CSS + JS

Combined frameworks

📝 Integrated Monaco Editor

Syntax highlighting

VS-Dark theme

Editable output

👀 Live Preview

Real-time preview inside iframe

Option to open in a new tab

📋 Copy & Export

One-click copy

Download generated code as .txt

⚡ Modern UI Enhancements

Gradient buttons

Dark mode (partial)

Responsive layout

Smooth transitions

📦 Project Setup
npm install
npm run dev


Set your Gemini API key in .env:

VITE_GEMINI_API_KEY=your_api_key_here

📁 Folder Structure
project/
│── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│── public/
│── package.json
│── README.md
