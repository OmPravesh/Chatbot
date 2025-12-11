# React Chatbot Project

A simple and interactive chatbot UI built using **React**, **Vite**, and functional components.  
This project demonstrates how chat messages can be dynamically stored, displayed, and updated using React hooks (`useState`).

---

## Features

-  Displays chat history with "user" and "robot" roles  
-  Input box to send new messages  
-  Real-time message rendering  
-  Clean component structure (`ChatMessages`, `ChatInput`, `App`)  
-  Basic styling for a clean chat interface  
-  Vite-powered fast development environment  

---

##  How It Works

### `App.jsx`
- Stores all chat messages in React state (`useState`)
- Passes messages and message setter function to child components

### `ChatMessages.jsx`
- Renders a list of all chat messages with sender tags

### `ChatInput.jsx`
- Allows the user to send new messages
- Updates the chat list using `setChatMessages`

### `main.jsx`
- Renders the main `<App />` component to the page using ReactDOM

### `index.html`
- Loads the React application with the root `<div>` for mounting

---

##  File Structure

