🧠 React Login Form with State Management
📌 Overview

This project demonstrates a simple login form built using React with the useState hook for local state management.
It handles real-time input updates, basic form validation, and logs user credentials to the console upon submission.

⚙️ Features

Real-time state updates using useState

Input fields for Username and Password

Basic form validation (checks for empty fields)

Console logging of input data

Clean and responsive UI with Tailwind CSS

🏗️ Tech Stack

React.js

JavaScript (ES6)

Tailwind CSS (for styling)

Vite (for fast development setup)

🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/react-login-form.git
cd react-login-form

2️⃣ Install dependencies
npm install

3️⃣ Run the project
npm run dev

4️⃣ Open in browser

Visit 👉 http://localhost:5173

🧩 File Structure
react-login-form/
│
├── src/
│   ├── components/
│   │   └── LoginForm.jsx
│   ├── App.jsx
│   └── main.jsx
│
├── index.html
├── package.json
└── README.md

💡 Usage

Enter a username and password.

Click Login.

If any field is empty → shows a validation message.

Otherwise → logs username and password to browser console.

🧾 Example Console Output
Username: ayushrana
Password: 12345

🧰 Future Enhancements

Add form reset functionality

Integrate API for authentication

Display user dashboard after successful login
