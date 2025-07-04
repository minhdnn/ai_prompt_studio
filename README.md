
# 🧠 AI Prompt Studio (Web Version)

**AI Prompt Studio** is a single-page web application designed to help you create, refine, and optimize prompts for interacting with cutting-edge AI models like **OpenAI GPT-4o** and **Google Gemini 1.5 Flash**. The app supports markdown, LaTeX, image input, and various customization options for different use cases.

---

## 🚀 Key Features

- 🧠 Compatible with OpenAI GPT-4o and Google Gemini 1.5
- 📌 Clean and intuitive 3-column layout: Input → Task → Output
- ✍️ Extensive customization: tone, role, industry, communication channel, language, length, and more
- 📎 Image prompt support for analysis and description
- 🧩 Manage custom context variables
- 💾 Save user settings via localStorage
- 🔈 Built-in text-to-speech output
- 🌙 Dark mode support
- 📄 Quick start guide and sample prompts included

---

## 🛠️ Installation & Usage

### 1. Clone or Download the Project

Download the repository or clone it using Git:

```bash
git clone https://github.com/your-repo/ai-prompt-studio.git
```

### 2. Open the HTML File in a Browser

On macOS or Linux:

```bash
open Ai_Prompt_Studio.html
```

Or simply drag and drop `Ai_Prompt_Studio.html` into your preferred browser (Chrome, Firefox, Edge, Safari, etc.).

---

### 3. Set Up Your API Keys

Open `Ai_Prompt_Studio.html` in a code editor (VSCode, Sublime Text, Notepad++, etc.) and locate the following lines:

```js
const OPENAI_API_KEY = "INSERT_YOUR_OPENAI_API_HERE";
const GEMINI_API_KEY = "INSERT_YOUR_GEMINI_API_HERE";
```

Replace the placeholders with your actual API keys:

- 🔑 OpenAI API Key: [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)
- 🔑 Google Gemini API Key: [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)

> ⚠️ **Warning:** Never upload your API keys to public repositories. Use environment variables or a secure backend if deploying online.

---

## 💡 Example Use Cases

### 📌 Improve Writing Style

- **Input:** `The report is good. I need more time.`
- **Task:** Improve Text  
- **Tone:** Professional  
- **Recipient:** Manager  
- **Output:** A professionally worded email requesting an extension, with a clear subject and body.

### 🌐 Translate Text

- **Input:** `Hôm nay trời đẹp quá!`  
- **Task:** Translate Text  
- **Language:** English  
- **Output:** `The weather is so beautiful today!`

---

## 📋 Supported Tasks

- Improve Text  
- Rewrite Text  
- Change Tone  
- Correct Grammar (Minimal Changes)  
- Summarize  
- Expand Text or Ideas  
- Translate  
- Dictionary Lookup  
- English Learning  
- Free Prompt

---

## 📦 Technologies Used

- [Tailwind CSS](https://cdn.tailwindcss.com)  
- [Font Awesome](https://cdnjs.com)  
- [marked.js](https://cdn.jsdelivr.net/npm/marked)  
- [MathJax](https://cdn.jsdelivr.net/npm/mathjax)

All dependencies are loaded via CDN—no backend or additional installation required.

---

## 📄 License
Developed by **Minh Do – 2025**
