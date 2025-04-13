# BrightMind💡– Empowering Rural Education with AI

**BrightMind** is an AI-powered educational platform designed to bridge the learning gap in rural and under-resourced areas. Leveraging cutting-edge language models like **Gemini 2.0 Flash**, the platform provides accessible, engaging, and personalized learning experiences to both students and teachers.

---

## 🚀 Features

- 🔍 **AI-Generated Content Summaries**  
  Quickly understand complex topics with concise summaries powered by Gemini 2.0 Flash.

- ❓ **Doubt-Solving Chat Assistant**  
  Real-time AI chat to help students and teachers clarify doubts instantly.

- 📝 **Quiz Generation**  
  Automatically generate quizzes from lesson content to reinforce learning.

- 📄 **Downloadable PDFs**  
  Export summaries, quizzes, and notes as PDFs for offline use—ideal for areas with limited connectivity.

- 🌐 **Multi-Platform Access**  
  Built with **Next.js** for web and **React Native** for mobile—ensuring access across devices.

- 🧠 **Teacher Toolkit**  
  Access teaching aids, translated materials, and lesson plans tailored for rural contexts.

- 🌍 **Multilingual Support**  
  BrightMind breaks language barriers by offering educational content in multiple **regional languages**, ensuring inclusivity and better understanding for learners in diverse linguistic backgrounds.

---

## 🧱 Tech Stack

| Tech               | Purpose                             |
|--------------------|--------------------------------------|
| 🌐 Next.js         | Web Frontend                        |
| 📱 React Native    | Mobile Application                  |
| 🐍 Django REST     | Backend API Framework               |
| 🗃️ SQLite          | Lightweight, portable database       |
| 🤖 Gemini 2.0 Flash| LLM for AI content & interaction    |

---

## 🛠️ Installation

### Backend – Django

```bash
cd backend
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend - Next.js

```bash
cd frontend
npm install
npm run dev
```

### Mobile - React Native

```bash
cd mobile
npm install
npx react-native run-android  # or run-ios
```
