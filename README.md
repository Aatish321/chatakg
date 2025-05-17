# AKG-GPT: AI Assistant Web App

🚀 A simple, sleek, and powerful AI assistant interface powered by Google Gemini and hosted on Vercel.

> **Live Demo**: [akg-gpt-6kq7.vercel.app](https://akg-gpt-6kq7.vercel.app/)

---

## 🌐 Overview

This project uses the [Assistant UI](https://www.assistant-ui.com/) template to create a modern frontend for interacting with a custom GPT powered by Google AI Studio. It's deployed and live using [Vercel](https://vercel.com/), making it accessible from anywhere.

---

## 🧰 Tech Stack

- **Frontend**: React (Next.js) via [Assistant UI](https://www.assistant-ui.com/docs/getting-started)
- **LLM API**: [Google AI Studio Gemini API](https://aistudio.google.com/apikey)
- **Deployment**: [Vercel](https://vercel.com/)

---

## 🔧 Setup Instructions

1. Clone the Repository

git clone https://github.com/yourusername/akg-gpt.git

cd akg-gpt



2. Install Dependencies
npm install
or
yarn install



3. Configure Environment Variables
Create a .env.local file in the root directory and add your Google API key:
GOOGLE_API_KEY=your_google_ai_studio_api_key
Generate your API key from: https://aistudio.google.com/apikey



4. Run the Development Server
npm run dev
or
yarn dev
The app will be available at: http://localhost:3000



## 🚀 Deploying to Vercel
Push your code to a GitHub repository.

Go to https://vercel.com and import your repo.

Add the environment variable GOOGLE_API_KEY in the project settings.

Click Deploy.

Your app will be live at:
https://your-vercel-project-name.vercel.app/

## ✨ Features
Chat interface powered by Google Gemini

Clean, minimalist UI

Fully responsive design

Easy customization via Assistant UI
