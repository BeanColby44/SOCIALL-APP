# Colby's SocialApp — React Native

<div align="center">
  <img src="assets/buildericon.png" alt="Colby's SocialApp" width="80" />

  <h3>Social Networking Mobile Application</h3>

  <p>A modern social networking experience built with React Native.</p>

  [![React Native](https://img.shields.io/badge/React_Native-Mobile_App-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactnative.dev/)
  [![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
  [![VS Code](https://img.shields.io/badge/VS_Code-Development-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)

</div>

---

## Overview

**Colby's SocialApp** is a React Native mobile application designed to provide an interactive social networking experience.

The application includes user authentication, profile management, social posts, comments, messaging, and notifications.

### Technology Stack

- **Mobile Framework:** React Native
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Development Environment:** Visual Studio Code
- **Development Tools:** Expo, npm
- **API Integration:** REST APIs

---

## Features

### Authentication & User Management
- Secure authentication using JWT.
- Password recovery functionality.
- User profile management and editing.
- Follow and unfollow other users.

### Social Networking
- Create, edit, and delete posts.
- Like and unlike posts.
- Add and delete comments.
- Discover and connect with users.
- View user profiles and activity.

### Messaging & Notifications
- Private messaging between users.
- Chat conversation management.
- Notifications for incoming messages.

---

## Application Screenshots

<div align="center">

### Authentication, Home & Profile

<img src="./screenshots/1.jpg" width="240" alt="Signup Screen" />
<img src="./screenshots/2.jpg" width="240" alt="Home Screen" />
<img src="./screenshots/3.jpg" width="240" alt="Profile Screen" />

### Posts, Statistics & User Discovery

<img src="./screenshots/4.jpg" width="240" alt="User Posts" />
<img src="./screenshots/5.jpg" width="240" alt="User Statistics" />
<img src="./screenshots/6.jpg" width="240" alt="Find People" />

### Messaging & Comments

<img src="./screenshots/7.jpg" width="240" alt="Chat List" />
<img src="./screenshots/8.jpg" width="240" alt="Chat Screen" />
<img src="./screenshots/9.jpg" width="240" alt="Comments Screen" />

### Post Creation & Notifications

<img src="./screenshots/10.jpg" width="240" alt="Create Post" />
<img src="./screenshots/11.jpg" width="240" alt="Message Notifications" />

</div>

---

## Getting Started

### Prerequisites

Before running the application, make sure you have:

- Node.js and npm
- Git
- Expo-compatible development environment
- Android emulator or iOS simulator
- A running backend API

### 1. Clone the Repository

```bash
git clone https://github.com/BeanColby44/SocialApp-React-Native.git
```

### 2. Navigate to the Project Directory

```bash
cd SocialApp-React-Native
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a file named `env.js` in the project root directory.

```javascript
const vars = {
  apiUrl: "YOUR_BACKEND_API_URL",
  defaultImageUri: "YOUR_BACKEND_API_URL/static/images/defaultprofile.jpg"
};

export default vars;
```

Replace `YOUR_BACKEND_API_URL` with your own backend server address.

### 5. Start the Application

```bash
npm start
```

Run the application using the options supported by your installed Expo version.

For more information, refer to the [React Native documentation](https://reactnative.dev/docs/getting-started).

---

## Project Structure

The application includes the following core functionality:

- User authentication
- Profile management
- Social feed
- Post management
- Likes and comments
- User discovery
- Private messaging
- Notifications
- Backend API integration

---

## Developer

**Colby Lee Bean**

Software Engineer | Full-Stack & Mobile Development

**GitHub:** [BeanColby44](https://github.com/BeanColby44)

**Email:** colby.bean@outlook.com

---

<div align="center">

**Developed and maintained by Colby Lee Bean**

[GitHub Profile](https://github.com/BeanColby44)

</div>