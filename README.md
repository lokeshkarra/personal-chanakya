# 💰 Personal Chanakya – Your AI-Powered Financial Companion

## 🧠 Introduction

**Personal Chanakya** is an intelligent, AI-native financial assistant that goes beyond simply answering questions — it understands your entire financial ecosystem. Designed to redefine personal finance management, this system uses cutting-edge technologies to provide real-time, context-aware guidance.

### 🔍 Key Features

- 🤖 **AI-Powered Insights**: Built using **Fi’s Model Context Protocol (MCP)** and **Google’s Gemini AI** for personalized guidance.
- 📊 **Smart Analysis**: Tracks trends, detects financial risks, and simulates life events like job changes or major purchases.
- 🔐 **Privacy First**: User-owned, secure, and privacy-conscious financial data and insights.
- 🌐 **Cross-Platform**: Works seamlessly across devices and platforms.
- 💬 **Human-Like Conversations**: Interacts naturally with users, providing contextual, intelligent responses.

---

## 📁 Project Structure

personal-chanakya/
├── backend # Node.js backend with AI integration
└── frontend # React frontend for user interaction

---

## 🚀 Getting Started

### 📦 Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v16 or above)
- npm (Node Package Manager)
- go 1.23

---

## ⚙️ Backend Setup

> The backend runs on **port 8080**

1. Navigate to the backend folder:

    ```bash
    cd backend
    ```

2. Install the dependencies:

    ```bash
    go mod tidy
    ```

3. Start the backend server:

    ```bash
    FI_MCP_PORT=8080 go run .
    ```

The server will start on [http://localhost:8080](http://localhost:8080)

---

## 🌐 Frontend Setup

1. Navigate to the frontend folder:

    ```bash
    cd ../frontend
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Start the React development server:

    ```bash
    npm run dev
    ```

The frontend will be available on [http://localhost:3000](http://localhost:9002)

---

## 🧰 Tech Stack

| Layer        | Technology                     |
|--------------|--------------------------------|
| Backend      | go                             |
| AI Platform  | Google Gemini-2 Flash          |
| Protocol     | Fi Model Context Protocol (MCP)|
| Frontend     | NextJS, Tailwind CSS           |
| Communication| REST APIs                      |
| Security     | Context-aware, User-controlled |


---

## 🙌 Contributing

We welcome contributions! Feel free to fork the repo, submit issues, or open pull requests.

---

## 📬 Contact

For any inquiries or collaboration ideas, please reach out via GitHub Issues or Pull Requests.

