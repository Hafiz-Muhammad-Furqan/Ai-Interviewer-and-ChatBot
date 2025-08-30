# <div align="center">AI Interviewer And ChatBot Platform</div>

<p align="center">
  <strong>A Complete Solution for Job Interview Preparation</strong><br>
  Built with Firebase, Gemini API, and React.js
</p>

## 🚀 Live Demo

Experience the application live: [https://furqan-ai-interviewer-chatbot.netlify.app](https://furqan-ai-interviewer-chatbot.netlify.app)

## ✨ Features

- **AI-Powered Mock Interviews** - Get real-time, job-specific questions with performance analysis
- **Interactive Chatbot** - Voice-enabled conversations with text alternatives
- **User Authentication** - Secure signup/login powered by Firebase
- **History Tracking** - Review your past interviews and chatbot conversations
- **Responsive Design** - Works seamlessly on desktop and mobile devices

## 🛠️ Technologies Used

| Category    | Technologies                         |
| ----------- | ------------------------------------ |
| Frontend    | React.js, Tailwind CSS, React Router |
| Backend     | Firebase (Authentication, Firestore) |
| AI Services | Gemini API, Web Speech API           |
| Deployment  | Netlify                              |

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Firebase account
- Google Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hafiz-Muhammad-Furqan/Ai-Interviewer-and-ChatBot.git
   cd AI-Interviewer-and-ChatBot
   ```

<!-- ```` -->

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**

   - Rename `.env.sample` to `.env`
   - Fill in the required values:

   ```env
   VITE_GEMINIAPIKEY=YOUR_GEMINI_API_KEY  # Gemini API key

   VITE_APIKEY=YOUR_API_KEY  # Firebase

   VITE_APPID=YOUR_APP_ID    # Firebase

   VITE_AUTHDOMAIN=YOUR_AUTH_DOMAIN  # Firebase

   VITE_MEASUREMENTID=YOUR_MEASUREMENT_ID  # Firebase

   VITE_MESSAGINGSENDERID=YOUR_MESSAGING_SENDER_ID  # Firebase

   VITE_PROJECTID=YOUR_PROJECT_ID  # Firebase

   VITE_STORAGEBUCKET=YOUR_STORAGE_BUCKET  # Firebase
   ```

### 🔑 Obtaining API Keys

1. **Firebase Configuration**

   - Go to [Firebase Console](https://console.firebase.google.com/)
   - Create a new project
   - Navigate to Project Settings > General
   - Under "Your apps", register a new web app
   - Copy the configuration values into your `.env` file

2. **Gemini API Key**
   - Visit [Google AI Studio](https://aistudio.google.com/)
   - Create a new API key
   - Copy the key into your `.env` file

### Running the Application

```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:5173`

## 📂 Project Structure

```
AI-Interviewer-and-ChatBot/
├── public/               # Static files
├── src/
│   ├── Components/       # Reusable components
│   ├── Context/          # React contexts
│   ├── Layouts/          # App Layouts
│   ├── Pages/            # Application pages
│   ├── Routes/           # React Router Dom Routes
│   ├── utilities/        # Utility functions
│   ├── App.jsx           # Main application component
│   └── main.jsx          # Entry point
├── .env.sample           # Environment variables template
├── package.json          # Project dependencies
└── README.md             # Project documentation
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## � Get in Touch

Got questions or suggestions? Feel free to:

- Open an issue in this repo
- Connect with me on [LinkedIn](https://www.linkedin.com/in/hafiz-muhammad-furqan) or [hafizfurqan.dev@gmail.com](mailto:hafizfurqan.dev@gmail.com)
- Star the repo if you found it helpful!
