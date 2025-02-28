Exam Result Viewer
Overview
The Exam Result Viewer is a simple web application that allows students to check their exam results by entering their mobile number and exam number. The application fetches exam results from Google Sheets and displays the details in a user-friendly interface.

Features
✅ Search results by mobile number & exam number
✅ Fetch exam results from Google Sheets (CSV format)
✅ Display student's name, father's name, mother's name, score, and exam number
✅ Options to Print, Download PDF, and Generate Certificate
✅ Fully responsive & user-friendly design
✅ Deployable on Render for free hosting

Technology Stack
Frontend: HTML, CSS, JavaScript
Backend: Node.js, Express.js
Database: Google Sheets (as a CSV data source)
Deployment: Hosted on Render
How It Works
Enter Mobile Number & Exam Number
Click 'Search' to fetch data from Google Sheets
If a match is found, display the student's result
Options to Print, Download PDF, or Generate a Certificate
Setup & Deployment
1. Clone the Repository
sh
Copy
Edit
git clone https://github.com/YOUR_USERNAME/exam-result-viewer.git
cd exam-result-viewer
2. Install Dependencies
sh
Copy
Edit
npm install
3. Run the Server
sh
Copy
Edit
npm start
Now open http://localhost:3000/ in your browser.

4. Deploy on Render
Push the code to GitHub
Go to Render.com > Create New Web Service
Connect your GitHub repository
Set Build Command: npm install
Set Start Command: node server.js
Click Deploy & get the live link 🎉

License
This project is open-source under the MIT License.
