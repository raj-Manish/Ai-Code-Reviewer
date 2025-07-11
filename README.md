🧠 AI Code Reviewer
An intelligent, developer-friendly tool that reviews code using Google’s GenAI. It provides bug detection, quality ratings, optimization tips, and clean explanations — all in a responsive in-browser editor.

🚀 Features
✅ Automated Code Review using Google GenAI SDK

🐞 Bug Detection and best-practice-based Improvement Suggestions

✨ Quality Scoring: Better, Good, Normal, or Bad

📚 Clear Code Explanation step-by-step

💻 In-browser code editing with Monaco Editor and syntax highlighting

🌐 Responsive UI with Tailwind CSS and modern React libraries (react-select, react-markdown)

🔄 Asynchronous API Handling with smooth loading states and Markdown-rendered AI responses

🛠️ Tech Stack
React

Tailwind CSS

Monaco Editor

Google GenAI SDK (@google/genai)

react-select

react-markdown

RingLoader (react-spinners)

🧪 Getting Started
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/ai-code-reviewer.git
cd ai-code-reviewer
Install dependencies

bash
Copy
Edit
npm install
Create a .env file in the root and add your Google API key:

env
Copy
Edit
VITE_GENAI_API_KEY=your_api_key_here
Run the app

bash
Copy
Edit
npm run dev
