Wisitrix AI

Wisitrix AI is an advanced AI-powered chatbot designed to provide intelligent and natural interactions. Built using state-of-the-art AI models, Wisitrix AI offers users seamless conversation experiences.

🚀 Features

Smart Conversations – Provides intelligent and context-aware responses.

Case-Insensitive Recognition – Works with both uppercase and lowercase input.

Predefined Responses – Instant answers for frequently asked questions.

AI-Powered Responses – Uses API-based AI models for dynamic conversation.

Special Character Handling – Filters out unnecessary characters for better understanding.


🛠️ Technologies Used

Frontend: HTML, CSS, JavaScript

AI Model: Mistral-7B (via OpenRouter API)

API: OpenRouter AI Chat API


📌 Installation & Setup

1. Clone the repository:

git clone https://github.com/yourusername/wisitrix-ai.git
cd wisitrix-ai


2. Open index.html in your browser to run Wisitrix AI.



⚙️ Configuration

To use the AI-powered responses, replace the API key in script.js:

const response = await fetch("https://openrouter.ai/api/v1/chat/completions", {
    method: "POST",
    headers: {
        "Authorization": "Bearer YOUR_API_KEY",
        "Content-Type": "application/json"
    },
    body: JSON.stringify({
        model: "mistralai/mistral-7b-instruct",
        messages: [{ role: "user", content: userMessage }]
    })
});

Replace YOUR_API_KEY with your actual OpenRouter API key.

🧠 How It Works

1. User Input Handling:

Converts input to lowercase.

Removes special characters.

Checks predefined responses.



2. AI API Interaction:

If no predefined response exists, it calls the OpenRouter API.

Fetches a dynamic response and displays it in the chat.



3. Smooth UI/UX:

Displays "Wisitrix AI is thinking..." while fetching responses.

Provides a user-friendly chat interface.




📌 Example Questions Wisitrix AI Can Answer

"Who is Nibil Krishna?"

"What is Wisitrix AI?"

"Who developed you?"

"Do you know about Wisitrix?"


🛡️ License

This project is licensed under the MIT License. Feel free to modify and contribute!

🌟 Contributing

Contributions are welcome! Fork the repo, create a new branch, and submit a pull request.

📬 Contact

For any questions or collaborations, reach out to Nibil Krishna.

