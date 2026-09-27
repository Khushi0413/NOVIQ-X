🔵 NOVIQ X

A sleek, minimal AI chat interface designed to connect directly to an AI agent through an OpenAI-compatible or Anthropic API. NOVIQ X provides a clean, dark interface with a dynamic, animated orb, conversation history, a configurable agent identity, and session-based connection settings.

✨ Features

🔵 Minimal AI interface — clean, modern dark UI centered around a dynamic animated orb

💬 Real-time chat — send messages and receive AI responses in a conversational layout

⚡ Typing indicator — animated dots appear while the AI is generating a response

🔌 API connection settings — configure the Base URL, API key, model, and API format

🤖 Custom agent name — give your AI agent a custom identity such as NOVIQ, Nova, or another name

🔄 Conversation reset — clear the current chat and return to the welcome screen

🧠 Conversation history — previous messages are maintained during the active conversation

🔐 Session-only API key — the API key is kept in memory for the current session and is not saved to local storage

💾 Saved preferences — Base URL, model, format, and agent name are stored locally on the device

🔀 Multiple API formats — supports OpenAI-compatible /chat/completions and Anthropic /v1/messages

📱 Responsive design — optimized for desktop and smaller mobile screens

🌌 Animated visual design — glowing orb, gradients, transitions, and glass-style chat panels

🖥️ Interface

The interface includes:

Top navigation bar — NOVIQ branding, reset button, and settings

Welcome screen — personalized greeting and animated AI orb

Chat area — separate user, assistant, and error message bubbles

Message composer — gradient input pill with send button

Connection settings dialog — configuration panel for connecting your AI model

⚙️ Configuration

Open Settings and provide:

Base URL — the API endpoint you want NOVIQ to connect to

API Key — authentication key for the selected API

Model — the model name to use

Agent Name — the name NOVIQ should use when identifying itself

Format — choose between:

OpenAI-compatible /chat/completions

Anthropic /v1/messages

The API key remains in memory for the current browser session, while the other configuration preferences are saved locally on the device.

🧠 How It Works

User
  ↓
NOVIQ Chat Interface
  ↓
Message History
  ↓
Selected API Format
  ├── OpenAI-compatible → /chat/completions
  └── Anthropic → /v1/messages
  ↓
AI Model
  ↓
NOVIQ Response

When a message is submitted, NOVIQ adds it to the conversation history, displays a typing indicator, sends the conversation to the configured API, and then displays the returned response in the chat.

🛠️ Tech Stack

HTML5 — page structure and interface markup

CSS3 — responsive layout, gradients, animations, glass-style panels, and UI styling

JavaScript (Vanilla) — application logic, DOM manipulation, chat state, API requests, and settings

Fetch API — communication with OpenAI-compatible and Anthropic endpoints

LocalStorage — persistence of non-secret configuration preferences

📁 Project Structure

NOVIQ/
│
├── index.html
└── README.md

The current implementation is contained in a single HTML file with its CSS and JavaScript included directly in the page.

🚀 Getting Started

Download or clone the project.

Open the HTML file in a modern web browser.

Open Settings.

Enter your API connection details.

Save the configuration.

Start chatting with your AI agent.

🔐 Security Note

NOVIQ keeps the API key in JavaScript memory for the active session and does not save it to localStorage. However, API requests are made directly from the browser, so you should only use API credentials and endpoints you trust.

🎯 Project Goal

NOVIQ is designed as a lightweight foundation for building a personal AI-agent interface. Its modular connection settings make it possible to connect the same frontend to different compatible AI backends without changing the main chat interface.

👨‍💻 Author

Built as an AI-agent interface project using HTML, CSS, and JavaScript.

⭐ NOVIQ — A simple interface for your n
