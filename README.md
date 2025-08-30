# 🤖 AI-Powered Mock Interview Platform – *InterviewSarthi*

## 📌 Description
This is an advanced and interactive **AI-powered mock interview platform** designed to help job seekers practice and improve their interview skills.  
Built with **Next.js, Tailwind CSS, Gemini API, PostgreSQL (Neon Serverless), and Drizzle ORM**, it provides users with a real interview-like experience to enhance their chances of landing their dream job.  

---

## ✨ Features
- 🤖 **AI-driven Interview**: Interview questions and feedback powered by AI.  
- 🧑‍💼 **Personalized Interview Experiences**: Tailor interview sessions based on job roles and industries.  
- 📊 **Experience-Level Questions**: Difficulty adjusts based on the user’s experience level.  
- 📝 **Detailed Feedback & Insights**: Strengths, areas for improvement, and actionable tips.  
- 📚 **Question Bank**: Wide range of interview questions across domains & difficulty levels.  
- 🏆 **Overall Grade**: Quick performance assessment after each session.  
- 🕑 **Recent Interviews**: Review your most recent interviews directly from the home page.  

---

## 🚀 Getting Started
Follow these steps to set up and run **InterviewSarthi** locally:

1️⃣ **Clone this repository**:
```bash
git clone https://github.com/sandipgunale/InterviewSarthi.git
```

2️⃣ **Install Dependencies**  

Using npm:
```bash
npm install
```

Or using yarn:
```bash
yarn install
```

3️⃣ **Set Up Environment Variables**  

Create a `.env.local` file in the root directory and add:  
```env
DATABASE_URL=your_postgresql_connection_string
NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
```

💡 Get your PostgreSQL DB from **Neon** and your Gemini API Key from **AI Studio**.

4️⃣ **Run Database Migrations**
```bash
npx drizzle-kit generate
npx drizzle-kit push
```

5️⃣ **Start Development Server**
```bash
npm run dev
```

Now open [http://localhost:3000](http://localhost:3000) 🎉

---

## 📸 Screenshots (Optional – Add Later)
- 🔹 Home Page (Dashboard)  
- 🔹 AI Interview Session  
- 🔹 Feedback & Insights Page  
- 🔹 Recent Interviews  

---

## 📖 Usage
1. Sign Up / Log In to start using the platform.  
2. Choose Interview Type (Technical / Behavioral / Mixed).  
3. Set Job Role & Experience Level for personalized questions.  
4. Start Mock Interview and answer AI-generated questions.  
5. Receive Feedback & Overall Grade instantly after completion.  
6. Review Recent Interviews anytime from your dashboard.  

---

## 📂 Project Structure
```
InterviewSarthi/
│── public/              # Static assets (images, icons, etc.)
│── src/
│   ├── app/             # Next.js App Router pages
│   ├── components/      # Reusable React components
│   ├── db/              # Drizzle ORM schema & queries
│   ├── lib/             # Utility functions & configs
│   ├── styles/          # Tailwind CSS & global styles
│   └── api/             # API routes (AI, feedback, etc.)
│── drizzle.config.ts    # Drizzle ORM configuration
│── package.json
│── README.md
│── .env.local           # Environment variables
```
  

---

## 🙌 Acknowledgements
- Next.js  
- Tailwind CSS  
- Gemini API  
- PostgreSQL  
- Drizzle ORM  
- Neon Serverless  

---

## 🌟 Support & Feedback
If you like this project, don’t forget to ⭐ star the repo on GitHub!  

For feedback, suggestions, or issues:  
👉 Create an Issue  
👉 Contact: **sandipgunale (GitHub)**  
