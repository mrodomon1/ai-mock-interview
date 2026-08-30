# AI Mock Interview Platform 🚀

A full-stack AI-powered application designed to help candidates prepare for job interviews by generating personalized, role-specific interview questions based on their resumes.

## ✨ Features
- **Smart Resume Parsing**: Upload your PDF resume, and the system instantly extracts key skills, experiences, and qualifications.
- **AI-Generated Interviews**: Powered by Google Gemini AI, it asks highly relevant technical and behavioral questions tailored to the job description.
- **Secure User Authentication**: Robust login and signup system built with JWT and Bcrypt.
- **Modern UI**: Clean, responsive frontend built with React.js and Vite.

## 🛠️ Tech Stack
- **Frontend**: React.js, Vite, React Router, SCSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **AI Integration**: Google Gemini AI
- **Utilities**: Puppeteer (Web Automation), Multer (File Uploads), PDF-Parse

## 🚀 How to Run Locally

### Prerequisites
- Node.js installed on your machine
- MongoDB Atlas account (or local MongoDB)
- Google Gemini API Key

### Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd Backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the Backend folder with the following keys:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   GOOGLE_GENAI_API_KEY=your_gemini_api_key
   ```
4. Start the server:
   ```bash
   npm run dev
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Vite dev server:
   ```bash
   npm run dev
   ```
4. Open `http://localhost:5173` in your browser.

## 👤 Author
Developed by **Rahul Kumar**
