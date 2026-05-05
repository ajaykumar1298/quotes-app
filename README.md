📚 Quotes App (React + Axios)
A simple and modern Quotes App built using React.js and Axios, which fetches quotes from a public API and displays them in a responsive card layout with pagination.

🚀 Features
-Fetch quotes from API
-Pagination (Next / Previous)
-Loading state handling
-Beautiful UI with Tailwind CSS
-Fully responsive design
-Smooth hover animations

🛠️ Tech Stack
-Frontend: React.js (Hooks)
-HTTP Client: Axios
-Styling: Tailwind CSS
-API: FreeAPI Quotes API

📂 Project Structure
src/
│── App.jsx
│── main.jsx
│── index.css

⚙️ Installation & Setup
1️.Clone the repository
git clone https://github.com/your-username/quotes-app.git
cd quotes-app

2.cd quotes-app
npm install

3.Run the project
npm run dev

🔗 API Endpoint
https://api.freeapi.app/api/v1/public/quotes?page=1

🔄 Pagination Logic
-Uses page state to track current page
-API updates data based on page number
-Buttons disabled when:
    -No previous page
    -No next page
    -While loading

🧠 Concepts Used
-React Hooks (useState, useEffect)
-API handling with Axios
-Conditional rendering
-Optional chaining (?.)
-Component-based UI

📌 Future Improvements
-Search quotes
-Favorite quotes
-Category filter
-Dark/Light mode toggle

👨‍💻 Author
Ajay Kumar

⭐ Support
If you like this project, give it a ⭐ on GitHub!