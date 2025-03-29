# WarrantyMe

## 📌 Overview
WarrantyMe is a full-stack web application that allows users to sign in with Google, create and edit text-based letters, and save them directly to their Google Drive using the Google Drive API. The application provides a simple and user-friendly word processor experience, enabling seamless document storage and retrieval.

## 🎯 Features

### 🔐 User Authentication (Google OAuth)
- Sign up and log in using Google authentication.
- Secure session management using JWT or session-based authentication.

### 📝 Letter Creation & Editing
- A simple text editor for writing and formatting letters.
- Ability to save drafts before uploading them to Google Drive.
- User-friendly and distraction-free UI.

### ☁️ Google Drive API Integration
- Save letters directly to Google Drive in Google Docs format.
- Retrieve and view saved letters from Google Drive.
- Ensure secure OAuth scopes and permissions to prevent unauthorized access.

### 🚀 Deployment
- Fully deployed front-end and back-end with public access.
- `.env.example` file provided for API keys and environment variables.

## 🛠️ Tech Stack

| Component     | Technology  |
|--------------|------------|
| Front-End    | React (Preferred) / Angular / Vue.js |
| Back-End     | Node.js with Express (Preferred) / Python with Flask/Django |
| Database     | PostgreSQL / MySQL / MongoDB (if needed) |
| Authentication | Google OAuth (Firebase Auth / Passport.js) |
| Storage API  | Google Drive API |
| Deployment   | Netlify / Vercel / Heroku / AWS / Azure / GCP |
| Version Control | GitHub / GitLab |

## 🏗️ Installation & Setup

### 📌 Prerequisites
Ensure you have the following installed on your system:
- Node.js (>=14.x)
- npm or yarn
- PostgreSQL / MySQL / MongoDB (if required)

### 📥 Clone the Repository
```sh
git clone https://github.com/Asmit13/WarrantyMe.git
cd WarrantyMe
```

### 🔧 Backend Setup
1. Navigate to the backend directory:
```sh
cd backend
```
2. Install dependencies:
```sh
npm install
```
3. Create a `.env` file and configure environment variables (refer to `.env.example`).
4. Start the backend server:
```sh
npm start
```

### 🎨 Frontend Setup
1. Navigate to the frontend directory:
```sh
cd frontend
```
2. Install dependencies:
```sh
npm install
```
3. Start the frontend server:
```sh
npm start
```

### 🔑 Google OAuth & API Setup
1. Create a Google Cloud Project.
2. Enable Google Drive API and configure OAuth credentials.
3. Update `.env` with Google Client ID, Secret, and necessary API keys.

## 🎁 Bonus Features (Optional)
- 📂 **Folder Organization:** Automatically create a "Letters" folder in Google Drive.
- ✨ **Rich Text Editing:** Support for bold, italic, lists, etc.
- 🔑 **Role-Based Access Control:** Implement admin and regular user roles.
- 🌐 **Real-Time Collaboration:** Google Docs-style editing using WebSockets.

## 🛠️ Deployment
- Deploy the frontend and backend on a cloud provider.
- Update `.env` variables for production.
- Ensure proper CORS handling for API requests.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes and push the branch.
4. Open a Pull Request.

## 📧 Contact
For any queries or issues, feel free to reach out:
- **Author:** Asmit Aditya Singh
- **GitHub:** [Asmit13](https://github.com/Asmit13)
- **Email:** asmitadsingh13@gmail.com

---

🚀 **Happy Coding!**

