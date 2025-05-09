<invoke name="artifacts">
<parameter name="command">create</parameter>
<parameter name="id">readme_file</parameter>
<parameter name="type">text/markdown</parameter>
<parameter name="title">README.md</parameter>
<parameter name="content"># GearShare - Gear Borrowing Application

A Progressive Web App (PWA) for managing gear lending and borrowing between users.

## 📋 Overview

GearShare is a platform that allows users to:
- Register their gear items
- Lend gear to other users
- Borrow gear from others
- Track lending/borrowing history

The application works seamlessly across both desktop and mobile devices, with Google account authentication for secure user management.

## 🛠️ Technology Stack

### Frontend
- **Framework**: React.js with TypeScript
- **UI Library**: Material-UI / Tailwind CSS
- **State Management**: Redux Toolkit / React Context API
- **PWA Features**: Workbox

### Backend
- **Firebase Ecosystem**:
  - Firebase Authentication (Google sign-in)
  - Firestore (NoSQL database)
  - Firebase Storage (for gear images)
  - Firebase Hosting
  - Firebase Cloud Functions

## 🏗️ Project Structure