# 🔐 Authentication – Sign In / Sign Up with Firebase

A simple web-based authentication system using **Firebase Authentication**. Users can register (Sign Up) and log in (Sign In) securely using their email and password.

## 👥 Contributors

- **Nikhil Shimpy** – [@NikhilShimpy](https://github.com/NikhilShimpy)  
- **Harsh Vardhan** – [@Harsh147v](https://github.com/Harsh147v)
  
---

## 🚀 Features

- Firebase Authentication (Email & Password)
- Clean and simple UI for Sign In/Sign Up
- Frontend using HTML, CSS, JavaScript
- Firebase project setup and config guide included

---

## 📂 Project Structure

authentication/
  ├── index.html # UI for Sign In / Sign Up
  ├── style.css # Styling the page
  ├── main.js # JavaScript + Firebase integration
  └── README.md # Project documentation
---

## ⚙️ Firebase Setup – Step-by-Step

### 1️⃣ Create a Firebase Project

1. Go to [https://console.firebase.google.com](https://console.firebase.google.com)
2. Click **"Add project"**
3. Enter a project name (e.g., `AuthApp`)
4. Disable Google Analytics (optional) and click **"Create project"**

---

### 2️⃣ Add Firebase to Your Web App

1. In Firebase Console, go to **Project Overview**
2. Click **</>** (Web icon) to register your app
3. Name it (e.g., `auth-web`)
4. Firebase will generate your **Firebase SDK config** — copy this.

---

### 3️⃣ Enable Firebase Authentication

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Navigate to **Build > Authentication**
3. Click **Get Started**
4. Go to the **Sign-in method** tab
5. Enable **Email/Password**
6. Click **Save**

---
Example:
```js
const firebaseApp = firebase.initializeApp({
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "XXXXXX",
  appId: "YOUR_APP_ID"
});
```
---

## 🧑‍💻 Developers

Want to contribute? Here's how to get started:

```bash
# Clone the repo
git clone [https://github.com/NikhilShimpy/Authentication.git]
cd Authentication

# Open index.html / click on View Live in vs code 

# Run the website
```
---

## 📌 Contributing

We welcome contributions to improve this project! Follow the steps below to get started:

---

### 🔃 1. Fork This Repository

- Click the **Fork** button on the top right of the [GitHub repository](https://github.com/yourusername/authentication) page.
- This creates a copy of the repository under your GitHub account.

---

### 📥 2. Clone Your Fork

```bash
git clone https://github.com/your-username/authentication.git
cd authentication
```
---

### 💻 3. Create a New Branch

```
git checkout -b your-feature-branch 
```
- Use a meaningful branch name like fix-login-error or add-ui-enhancement.

---

### ✍️ 4. Make Your Changes
- Edit the code (e.g., main.js, style.css, etc.)
- Test the changes by opening index.html in your browser

---

###✅ 5. Commit and Push Changes
```
git add .
git commit -m "Describe your changes"
git push origin your-feature-branch
```

---

###🚀 6. Create a Pull Request

- Go to your forked repository on GitHub
- Click "Compare & pull request"
- Add a title and description of your changes
- Submit the pull request (PR)

---

###🛠️ Guidelines

- Follow consistent naming and code style
- Keep commits clean and descriptive
- Test before submitting
- You can also raise an issue if you want to discuss a bug or feature before coding
