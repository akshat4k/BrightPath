🌟 BrightPath – Your AI Resume Generator & Analyzer BrightPath is an intelligent, AI-powered web application designed to revolutionize how you build and evaluate resumes. Whether you're a fresher or a seasoned professional, BrightPath helps you craft compelling, ATS-optimized resumes and get detailed feedback — all in one place.

📚 Table of Contents Features

Tech Stack

Installation

Project Structure

✨ Features 🔹 AI Resume Builder Create professional resumes with customizable templates optimized for Applicant Tracking Systems (ATS). Just fill out an intuitive form, and let the AI take care of the formatting.

🔹 Resume Evaluation Already have a resume? Upload it (PDF or DOCX) and receive a smart score out of 100. Get feedback on grammar, formatting, keyword optimization, and structure.

🔹 Live Preview Watch your resume update in real-time with a responsive, mobile-friendly interface.

🔹 Export Options Download your resume in both PDF and DOCX formats with just a click.

🔹 Secure & Scalable Your data stays safe with JWT authentication, HTTPS, and encryption protocols.

🔹 User-Friendly Interface Smooth, minimal UI designed for ease of navigation across devices.

🛠 Tech Stack Frontend: ReactJS, Tailwind CSS, React Router Backend: Node.js with Express or Python with Flask AI/NLP: spaCy, BERT, TextStat, PyPDF2, python-docx Database: MongoDB + Mongoose Exporting: jsPDF, Puppeteer Testing: React Testing Library, Postman, Mocha/Chai, PyTest Security: JWT, bcrypt, HTTPS

🚀 Usage 📝 Create an Account Sign up or log in to get started.

📄 Build Your Resume Input personal, educational, and professional details. Select a template and view real-time updates. ✅ Export in PDF or DOCX when done!

📤 Evaluate Existing Resume Upload your current resume. Get:

A smart score (out of 100)

AI feedback on grammar, formatting, and keyword usage

Suggestions for improvement 🔁 Apply improvements and re-analyze if needed!

📊 Deep Insights View detailed category-wise breakdowns and input job descriptions for targeted keyword suggestions.

📁 Project Structure bash Copy Edit brightpath-ai-resume/ ├── frontend/ │ └── src/ │ ├── components/ # Form, templates, etc. │ ├── pages/ # Login, dashboard │ ├── assets/ # Images, styles │ └── App.js ├── backend/ │ ├── routes/ # API endpoints │ ├── models/ # Mongoose schemas │ ├── nlp/ # AI resume analysis scripts │ └── server.js/app.py ├── docs/ # Project documentation ├── tests/ # Unit & integration tests ├── .env.example └── README.md
