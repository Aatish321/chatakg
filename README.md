# chatakg

# AKG-GPT: AI Assistant Web App

🚀 A simple, sleek, and powerful AI assistant interface powered by Google Gemini and hosted on Vercel.

> Live Demo: [akg-gpt-6kq7.vercel.app](https://akg-gpt-6kq7.vercel.app/)

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

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/akg-gpt.git
cd akg-gpt
2. Install Dependencies
bash
Copy
Edit
npm install
# or
yarn install
3. Configure Environment Variables
Create a .env.local file in the root directory and add your Google API key:

env
Copy
Edit
GOOGLE_API_KEY=your_google_ai_studio_api_key
You can generate the API key from: https://aistudio.google.com/apikey

Ensure your API key has access to Gemini Pro models.

4. Run the Development Server
bash
Copy
Edit
npm run dev
# or
yarn dev
The app will be running at http://localhost:3000

🚀 Deploying to Vercel
You can deploy this app directly with the Vercel CLI or the Vercel dashboard.

Push your code to a GitHub repository.

Go to https://vercel.com and import your repo.

Add the environment variable GOOGLE_API_KEY in the project settings.

Deploy!

Your app will be live at: https://your-vercel-project-name.vercel.app/

✨ Features
Chat interface powered by Google Gemini

Clean and modern UI

Responsive and mobile-friendly

Easy customization via Assistant UI

