
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
