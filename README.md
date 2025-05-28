# 💖 Plan With Love App

**Live Demo:** [abhi17bgp.github.io/Plan-with-Love-App](https://abhi17bgp.github.io/Plan-with-Love-App/)

---

## Project Description

Plan With Love is a beautiful and user-friendly **React** application designed to help users organize and plan special events or moments with their loved ones. The app allows adding, editing, and deleting personalized plans with smooth navigation powered by React Router.

Data is stored locally in the browser (using `localStorage`), enabling persistence without the need for backend services or user authentication.

---

## ✨ Features

- 💌 Add, edit, and delete personalized plans/events
- 🔄 Smooth navigation with React Router for different views (Home, Add Plan, Edit Plan)
- 🗂️ Uses browser `localStorage` for saving and loading plans persistently
- 🎨 Clean and modern UI styled using CSS Modules
- 📱 Responsive design suitable for all screen sizes
- 🎨 Uses React Icons for intuitive button and UI icons

---

## 🛠️ Tech Stack

| Technology     | Purpose                                  |
|----------------|------------------------------------------|
| React          | Frontend UI and component architecture   |
| React Router   | Client-side routing and navigation       |
| CSS Modules    | Scoped and modular CSS styling            |
| React Icons    | Icons used throughout the app             |
| localStorage   | Data persistence in the browser          |
| GitHub Pages   | Hosting the live app                      |

---

## 📦 How It Works

1. On load, the app fetches stored plans from `localStorage`.
2. User navigates between pages:
   - **Home:** View all saved plans.
   - **Add Plan:** Create a new plan with title and description.
   - **Edit Plan:** Update existing plan details.
3. User inputs are saved to `localStorage` to persist data.
4. Navigation is handled seamlessly with React Router.

---

## 📁 File Structure

plan-with-love-app/
├── public/ # Public assets like index.html
├── src/
│ ├── components/ # Reusable React components
│ ├── pages/ # Page components for routing (Home, Add, Edit)
│ ├── styles/ # CSS Modules for styling
│ ├── App.js # Main React app and routes setup
│ └── index.js # ReactDOM render
├── package.json # Project metadata and dependencies
└── README.md # Project documentation

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/abhi17bgp/Plan-with-Love-App.git
2. Navigate into the project directory: cd Plan-with-Love-App
3. Install dependencies: npm install
4.Start the development server: npm start
5.Open http://localhost:3000 to view the app in your browser.
   
