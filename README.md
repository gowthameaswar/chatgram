
---

# 📱 Chatgram

Chatgram is a social media application that allows users to connect, share posts, comment, like, and interact with each other in real-time.

## 📋 Table of Contents

- [📱 Chatgram](#-chatgram)
  - [📋 Table of Contents](#-table-of-contents)
  - [🚀 Features](#-features)
  - [🛠️ Installation and Usage](#️-installation-and-usage)
    - [1. Clone the Repository](#1-clone-the-repository)
    - [2. Install Dependencies](#2-install-dependencies)
    - [3. Configure Environment Variables](#3-configure-environment-variables)
    - [4. Run the Server](#4-run-the-server)
    - [5. Start React's Development Server](#5-start-reacts-development-server)
  - [🤝 Contributing](#-contributing)
  - [📝 License](#-license)

## 🚀 Features

- Create, read, update, and delete posts
- Like and unlike posts
- Create, reply to, read, update, and delete nested comments
- Markdown for posts and comments
- Sign up and login using JWT for authentication
- Private messaging users in real-time using socket.io
- View profiles of users and browse through their posts, liked posts, and comments
- Infinite scrolling
- Sort posts by attributes such as like count, comment count, and date created
- Profanity filtering and posting/commenting cooldowns
- Update bio which can be viewed by other users
- Search for posts by their title
- View the users who liked a particular post
- Fully responsive layout

## 🛠️ Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/gowthameaswar/chatgram.git
```

### 2. Install Dependencies

```bash
cd chatgram
npm install
cd client
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root directory:

```bash
touch .env
```

Configure environment variables in your `.env` file:

```
MONGO_URI=<YOUR_MONGO_URI> 
TOKEN_KEY=<YOUR_TOKEN_KEY>
PORT=4000
```

- To acquire your `MONGO_URI`, create a cluster for free at [MongoDB](https://www.mongodb.com/).
- The `TOKEN_KEY` is a secret key of your choosing. You can generate one at [RandomKeygen](https://randomkeygen.com/).

### 4. Run the Server

```bash
npm run server
```

### 5. Start React's Development Server

Start a new terminal and run React's development server:

```bash
cd chatgram
cd client
npm start
```

Now, you should be able to access Chatgram by navigating to `http://localhost:3000` in your web browser.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any features, bug fixes, or enhancements.

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
