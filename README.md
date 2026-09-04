# IntelliBot Builder 

**IntelliBot Builder** is an AI-powered no-code platform that allows users to create personalized AI chatbots without writing code. Users can define their chatbot's **role, behavior, tone, and persona**, and interact with the generated chatbot through a simple web interface.

The project integrates the **Google Gemini API** with customizable prompts to generate domain-specific conversational responses.

##  Features

* **No-Code Chatbot Creation** – Create a customized AI chatbot without writing code.
* **Custom AI Persona** – Define the chatbot's role, personality, tone, and behavior.
* **Generative AI Integration** – Uses the Google Gemini API to generate conversational responses.
* **Customizable Prompts** – Dynamically builds prompts based on the user's chatbot configuration.
* **Interactive Chat Interface** – Communicate with the created chatbot through a web-based interface.
* **Responsive UI** – Designed to provide a simple and user-friendly chatbot creation experience.

##  Tech Stack

**Frontend**

* React.js
* Vite
* HTML
* CSS
* JavaScript

**AI / API**

* Google Gemini API
* Generative AI
* Prompt Engineering

**Development Tools**

* Git
* GitHub
* VS Code

##  How It Works

```text
User
  ↓
Defines Chatbot Role, Tone & Persona
  ↓
Chatbot Configuration
  ↓
Custom Prompt Generation
  ↓
Google Gemini API
  ↓
AI-Generated Response
  ↓
Interactive Chat Interface
```

##  Project Structure

```text
Intellibot-builder/
│
├── public/
│
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
│   └── ...
│
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
```

##  Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/khushigupta070405/Intellibot-builder.git
```

### 2. Navigate to the project

```bash
cd Intellibot-builder
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure the Gemini API

Create a `.env` file in the project root and add your Gemini API key:

```env
VITE_GEMINI_API_KEY=your_api_key_here
```

> **Note:** Never commit your API key or `.env` file to GitHub.

### 5. Start the development server

```bash
npm run dev
```

The application will be available at the local development URL shown in your terminal.

##  Future Improvements

* User authentication and account management
* Save and manage multiple custom chatbots
* Chat history and conversation persistence
* Additional AI model integrations
* Custom knowledge-base integration
* Deployment with production-grade backend services
* Improved chatbot customization and analytics

##  Project Objective

The goal of IntelliBot Builder is to make **AI chatbot creation accessible to users without programming knowledge** by combining a simple configuration interface with generative AI capabilities.

##  Author

**Khushi Gupta**

GitHub: [khushigupta070405](https://github.com/khushigupta070405)
Linkedin: [Khushi Gupta](https://www.linkedin.com/in/khushi-gupta-745k/)
