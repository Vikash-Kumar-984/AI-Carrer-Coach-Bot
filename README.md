# AI Career Coach Bot

A friendly and intelligent chatbot designed to provide personalized career advice, resume feedback, and interview preparation help, powered by the Google Gemini API.

**[➡️ View Live Demo](https://vikash-kumar-984.github.io/AI-Carrer-Coach-Bot/)** 

---

## ✨ Features

* **Conversational Interface:** A clean, modern, and user-friendly chat interface for natural interaction.
* **Intelligent Responses:** Leverages the Gemini API to provide insightful and relevant career advice.
* **Resume Critique:** Get instant feedback on your resume's clarity, impact, and formatting.
* **Interview Preparation:** Practice common behavioral and technical interview questions.
* **Career Exploration:** Discover key skills and trends for various job roles.
* **Cover Letter Assistance:** Get help drafting compelling cover letters tailored to specific jobs.
* **Copy & Clear:** Easily copy the AI's advice to your clipboard or clear the chat to start fresh.

## 🛠️ Tech Stack

* **Frontend:** HTML5, Tailwind CSS
* **AI:** Google Gemini API
* **JavaScript:** Vanilla JS for DOM manipulation and API calls

---

## 🚀 Setup and Local Development

To run this project on your local machine, follow these steps:

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/your-username/ai-career-coach-bot.git](https://github.com/your-username/ai-career-coach-bot.git)
    cd ai-career-coach-bot
    ```

2.  **Get Your API Key**
    * This project requires a Google Gemini API key to function.
    * Visit [Google AI Studio](https://aistudio.google.com/) to create your free API key.

3.  **Add the API Key**
    * Open the `index.html` file in a text editor.
    * Find the following line in the `<script>` section:
        ```javascript
        const apiKey = ""; // Replace with your key for local testing
        ```
    * Paste your API key between the quotes.

4.  **Run the Application**
    * Simply open the `index.html` file in your web browser. No local server is needed.

---

## ☁️ Deployment

This application is a single HTML file and can be deployed easily on several free platforms.

### Option 1: Netlify 

1.  Go to [Netlify Drop](https://app.netlify.com/drop).
2.  Drag and drop your `index.html` file into the upload area.
3.  Netlify will provide you with a live URL for your deployed site.

### Option 2: GitHub Pages

1.  Ensure your repository is named `your-username.github.io` for a root deployment, or something else for a sub-path deployment (e.g., `ai-career-coach`).
2.  Push your `index.html` file to the `main` branch.
3.  In your repository's **Settings**, go to the **Pages** tab.
4.  Select the `main` branch as the source and click **Save**.
5.  Your site will be available at `https://your-username.github.io/your-repo-name/`.

> **⚠️ Important Security Note:** The current setup exposes your API key in the client-side code. For a personal project, this is acceptable, but it is not secure for a production application. **It is highly recommended to add HTTP referrer restrictions to your API key in the Google Cloud Console to prevent misuse.**

## 🔮 Future Improvements

* **User Accounts:** Allow users to sign in and save their chat history.
* **File Uploads:** Enable users to upload their resume as a PDF or DOCX file for analysis.
* **Dark Mode:** Implement a toggle for a dark color scheme.
* **Streaming Responses:** Show the AI's response as it's being generated for a more interactive feel.

---
## ©️ Copyright and License

Copyright (c) 2025 Vikash Kumar. All Rights Reserved.

** Feel Free to connect me if any suggestions available. Thank You.


