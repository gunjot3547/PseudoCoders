

Adapt Learn Pathways is an AI-driven online education platform that delivers personalized learning experiences, dynamic assessments, and real-time mentorship based on user performance. Built with React, TypeScript, and modern UI frameworks, the system integrates adaptive learning, community engagement, and intelligent tutoring all in one ecosystem.

---

 🚀 Features

- 🔍 Initial Diagnostic Assessment
  - Detects strengths and weak areas using user responses.
  - Personalized quiz questions generated via Gemini AI API.

- 🧠 Adaptive Learning Engine
  - Curates lessons and paths based on progress and test performance.
  - Supports domain-specific skill development (OS, CN, DSA, etc.).

- 📊 Dynamic Dashboard & Analytics
  - Tracks progress, visualizes weak topics, and provides improvement charts.

- 🤖 AI Teaching Assistant
  - Post-quiz feedback and suggestion system using LLM.
  - AI-driven chatbot to reinforce concepts and correct mistakes.

- 🌐 Community & Collaboration
  - AI-moderated discussion forums and 1:1 mentor support.
  - Peer learning groups and gamified learning environment.

---

 🧱 Tech Stack

| Layer            | Technology                                     |
|------------------|------------------------------------------------|
| Frontend         | React, TypeScript, Tailwind CSS, ShadCN UI     |
| Routing          | React Router DOM                               |
| AI Integration   | Gemini API (Google Generative Language API)    |
| Visualization    | Chart.js or Recharts (for analytics)           |
| Backend (optional)| Node.js + Express (if using API backend)     |

---

 🔗 APIs Used

- 📚 Gemini Generative Language API
  - Used to generate quiz questions dynamically based on domain.
  - Provides post-assessment learning suggestions.

- 📈 Charting Library (e.g., Recharts/Chart.js)
  - Used in the dashboard to display analytics and progress tracking.

---

 📂 Project Structure

```
src/
│
├── components/
│   ├── Navbar.tsx
│   ├── QuizQuestion.tsx
│   ├── ProgressBar.tsx
│   └── DashboardCharts.tsx
│
├── pages/
│   ├── Quiz.tsx
│   ├── Results.tsx
│   └── Dashboard.tsx
│
├── utils/
│   └── generateQuiz.ts (Gemini API integration)
│
└── App.tsx
```

---

 🛠️ Setup Instructions

```bash
# 1. Clone the repo
git clone https://github.com/your-username/adapt-learn-pathways.git

# 2. Install dependencies
npm install

# 3. Create a .env file with your Gemini API key
REACT_APP_GEMINI_API_KEY=your_google_gemini_api_key_here

# 4. Start the development server
npm run dev
```

---

 🎯 How Gemini API is Used

- Upon domain selection, questions are dynamically fetched via Gemini.
- Prompt structure is designed to generate MCQs with difficulty levels.
- Gemini also provides post-assessment suggestions based on user choices.

---

 📌 To-Do / Future Enhancements

- [ ] Add backend authentication
- [ ] Integrate full mentor matching algorithm
- [ ] Expand multilingual support
- [ ] Enable spaced revision paths
- [ ] Add exportable learning reports

