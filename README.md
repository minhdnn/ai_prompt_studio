🧠 AI Prompt Studio (OpenAI/Gemini Web App)
A modern, responsive, and user-friendly web application that helps users generate high-quality AI outputs by customizing context, tone, role, language, and more — powered by OpenAI GPT-4o and Google Gemini 1.5 Flash.

✨ Features
🔁 Supports both OpenAI and Google Gemini APIs

📚 Smart contextual configuration: tone, channel, role, industry, etc.

📝 Flexible task selection: improve, rewrite, translate, summarize, and more

🌐 Multilingual output: English, Vietnamese, Spanish, French, Japanese, Korean...

📷 Image attachment for vision-enabled models

🧩 Custom variables for better contextual precision

📤 Import/Export JSON configs for user variables

🌗 Dark mode support

🔊 Text-to-speech (Read aloud feature)

🧠 MathJax support for LaTeX rendering in AI output

🧪 Live Markdown preview

🚀 Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/ai-prompt-studio.git
2. Open Aipromptstudio.html in your browser
No server or build step required. This is a pure front-end static web app.

3. Set your API keys
Edit the file and replace:

js
Copy
Edit
const OPENAI_API_KEY = "INSERT_YOUR_OPENAI_API_HERE";
const GEMINI_API_KEY = "INSERT_YOUR_GEMINI_API_HERE";
⚠️ Warning: Do NOT expose real keys in public repositories. Use server-side proxy for production.

📂 File Structure
bash
Copy
Edit
.
├── Aipromptstudio.html    # Main app file
└── README.md              # This file
🛠 Technologies Used
Tailwind CSS

FontAwesome Icons

Marked.js – Markdown parsing

MathJax – LaTeX rendering

Vanilla JS (No framework)

🔐 Security Note
This project is intended for local or personal usage.

For production, implement a secure backend proxy to handle API keys safely.

🙌 Credits
Developed by Minh Do (2025)

Icons by FontAwesome

AI Models via OpenAI and Google Gemini

📄 License
MIT License (You can modify and use freely with attribution)
