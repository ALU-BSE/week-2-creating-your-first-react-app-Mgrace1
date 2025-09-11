My First React App 

This project was created as part of the Guided Learning Activity: Creating Your First React App with TypeScript and Vite.
The goal is to build a simple React application that displays a heading and a paragraph using a custom component styled with CSS.

 Project Setup
Prerequisites

Node.js
 (v16 or later recommended)

npm (comes with Node.js)

A code editor such as VS Code

Steps to Run the Project

Clone the repository

git clone https://github.com/your-username/my-first-react-app.git
cd my-first-react-app


Install dependencies

npm install


Run the development server

npm run dev


Open your browser and go to:
 http://localhost:5173/

 Project Structure
my-first-react-app/
├── index.html
├── package.json
├── tsconfig.json
├── vite.config.ts
├── src/
│   ├── App.tsx
│   ├── App.css
│   ├── main.tsx
│   ├── index.css
│   ├── MyComponent.tsx
│   ├── MyComponent.css
│   └── vite-env.d.ts

🖼 Features

 Built with React + TypeScript + Vite

 Custom component (MyComponent)

 Styled with CSS (MyComponent.css and App.css)

 Fast Hot Module Replacement (HMR)

 Component Example

MyComponent.tsx

import React from 'react';
import './MyComponent.css';

const MyComponent: React.FC = () => {
  return (
    <div className="my-component">
      <h1>Hello from MyComponent!</h1>
      <p>This is a paragraph of text within my component.</p>
    </div>
  );
};

export default MyComponent;

 Styling Example

MyComponent.css

.my-component {
  background-color: lightblue;
  padding: 20px;
  border: 1px solid blue;
  border-radius: 5px;
  text-align: center;
}

.my-component h1 {
  color: navy;
}

.my-component p {
  font-size: 16px;
}



 Resources

Vite Documentation

React Documentation

TypeScript Documentation
