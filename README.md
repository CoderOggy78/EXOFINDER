ExoFinder is a Firebase-powered web app designed to help users discover, explore, and analyze exoplanets and other celestial bodies using real-time astronomical data.
It’s built for science enthusiasts, students, and researchers passionate about space exploration and astrophysics.

🚀 Features

🔭 Exoplanet Database – Browse and search through a curated list of exoplanets fetched from public NASA APIs.

🌠 Planet Insights – View detailed statistics like orbital period, discovery method, radius, and temperature.

🪐 Favorites System – Save your favorite planets securely to your Firebase account.

☁️ Firebase Integration – Uses Firebase Authentication, Firestore Database, and Hosting.

💫 AI-Assisted Search (optional) – Intelligent recommendations based on your interest patterns.

🌍 Responsive Design – Fully optimized for desktop and mobile users.

🧠 Tech Stack
Category	Technology Used
Frontend	HTML, CSS, JavaScript (or React if used)
Backend / Database	Firebase Firestore
Authentication	Firebase Auth
Hosting	Firebase Hosting
APIs	NASA Exoplanet Archive / Custom API
Version Control	Git & GitHub
🔧 Setup Instructions
1. Clone the Repository
git clone https://github.com/<your-username>/ExoFinder.git
cd ExoFinder

2. Install Dependencies

If using npm or frameworks like React:

npm install

3. Setup Firebase

Go to Firebase Console

Create a new project named ExoFinder

Enable Firestore, Authentication (Email/Password or Google), and Hosting

Copy your Firebase config and paste it into your app (usually in firebaseConfig.js):

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "XXXXXX",
  appId: "YOUR_APP_ID"
};

4. Run Locally
npm start


or simply open index.html if it’s a static project.

5. Deploy to Firebase Hosting
firebase login
firebase init
firebase deploy

🧩 Folder Structure
ExoFinder/
│
├── public/                # Static assets
│   ├── index.html
│   └── styles/
│
├── src/                   # Main app source code
│   ├── firebaseConfig.js
│   ├── scripts/
│   ├── components/
│   └── assets/
│
├── package.json
├── README.md
└── firebase.json

🔐 Firebase Services Used

Firebase Authentication – Secure login system (Email/Google)

Cloud Firestore – Store and retrieve user data and favorite exoplanets

Firebase Hosting – Fast and reliable static site hosting

🧭 Future Enhancements

🌌 Integration with NASA Exoplanet API for real-time discoveries

📈 Add visual orbit charts using D3.js or Chart.js

🔔 Notifications for new exoplanet discoveries

🤖 AI-based exoplanet recommendation engine

🧬 Integration with Google Vertex AI for astrophysical predictions

👩‍🚀 Contributors
Name	Role	Description
Vishwanath Barve	Founder & Developer	Designed and developed the Firebase-backed ExoFinder web app
🛡️ License

This project is licensed under the MIT License — free to use, modify, and distribute with attribution.

🌟 Support

If you like ExoFinder, give it a ⭐ on GitHub and contribute to its mission — to make space exploration accessible to everyone!
