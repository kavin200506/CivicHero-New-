# Quick Setup: Firestore Database

## 🚀 Fast Setup (3 Steps):

### 1. Create Database
Go to: https://console.firebase.google.com/project/civicissue-aae6d/firestore

Click **"Create database"** → Choose **"Start in test mode"** → Select location → **Enable**

### 2. Set Security Rules
1. Go to **Rules** tab
2. Copy the rules from `firestore-rules-simple.txt` (for development)
   OR `firestore-rules.txt` (for production)
3. Paste in the Rules editor
4. Click **"Publish"**

### 3. Enable Services
Make sure these are enabled:
- ✅ **Authentication** (Email/Password)
- ✅ **Firestore Database** (just created)
- ✅ **Storage** (for images)

---

## 📋 Recommended Rules (Development):

Use `firestore-rules-simple.txt` for now - it allows all authenticated users to read/write.

For production, use `firestore-rules.txt` which has proper access controls.

---

## ✅ That's It!

Once created, your app will automatically:
- Create collections when needed
- Store data correctly
- Work with authentication

**No manual collection creation required!**


