# 🤖 AI Chatbot

An interactive AI chatbot built using **HTML, CSS, and JavaScript** that integrates with the **Google Gemini API** to generate real-time responses. The app features typing animation, file upload support, chat history, and dark/light theme toggle, all in a clean and responsive UI.

🔗 **Live Demo:** https://prachu25.github.io/chatbot/

📂 **GitHub Repository:** https://github.com/prachu25/chatbot

> ⚠️ Note: This project uses a free Gemini API key hosted on GitHub Pages. Responses may stop working once the free usage limit is reached.

---

## 🚀 Features

* 💬 Real-time AI conversation using Gemini API
* ⌨️ Typing animation effect for bot responses
* 📎 File upload support (images & documents)
* 🌙 Dark / Light theme toggle
* 🧠 Smart suggestions for quick prompts
* 🛑 Stop response generation button
* 🗑️ Delete chat history option
* 📱 Fully responsive UI

---

## 🛠️ Tech Stack

**Frontend:**

* HTML5
* CSS3
* JavaScript (Vanilla JS)

**API:**

* Google Gemini API (Generative Language)

**Deployment:**

* GitHub Pages

---

## 📂 Project Structure

```
chatbot-project/
│
├── index.html        # Main UI structure
├── style.css         # Styling & themes
├── script.js         # Chat logic & API integration
├── gemini.svg        # Bot avatar icon

```

---

## ⚙️ How It Works

1. User enters a message in the input box
2. JavaScript sends a request to the Gemini API
3. API processes the prompt and returns a response
4. Bot reply is displayed with a typing animation
5. Chat history is stored in memory for context

---

## 🔑 API Setup

This project uses the Google Gemini API.

Inside `script.js`:

```
const API_KEY = "YOUR_API_KEY";
```

Replace with your own API key from Google AI Studio.

> ⚠️ Important: Since this is a frontend-only project, the API key is visible in the browser. For production apps, always use a backend to secure API keys.

---

## 💻 Run Locally

1. Clone the repository:

```
git clone https://github.com/prachu25/chatbot.git

```

2. Open the folder:

```
cd chatbot
```

3. Run the project:

* Double-click `index.html`
  OR
* Use VS Code Live Server

---

## 🌐 Deployment

This project is deployed using **GitHub Pages**.

To deploy:

1. Push code to GitHub
2. Go to Repository → Settings → Pages
3. Select main branch → Save

Your site will be live at:

```
https://yourusername.github.io/your-repo-name/
```

---

## ⚠️ Limitations

* Uses free Gemini API tier
* Responses may stop after usage quota is reached
* API key is exposed in frontend (not suitable for production)

---

##  Future Enhancements

* Backend integration to secure API key
* Chat history saved in local storage/database
* Voice input support
* Better conversation UI
* Streaming responses

---

##  Author

**Prachi Gorde**

* GitHub: https://github.com/prachu25

---

##  If you like this project

Give it a star on GitHub and share your feedback!
