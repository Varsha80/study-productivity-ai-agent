->Study & Productivity AI Agent (Gemini-Powered)
A personalized AI Study & Career Coach that generates smart study plans, manages tasks, remembers your preferences, and helps you stay consistent throughout your exam and placement preparation journey.
Built as part of the Google x Kaggle – 5-Day Agents Intensive Capstone Project.
🚀 About the Project
This AI Agent helps students:

📚 Create personalized study plans
📝 Manage tasks, deadlines & learning goals
🤖 Use Gemini 2.5 Flash / Pro for intelligent responses
🧠 Maintain session memory + long-term memory
📈 Provide consistent guidance for exams & placements

It acts like your friendly senior, strict mentor, or fun study buddy — depending on your chosen style.
🧠 Features
1. Study Plan Generator
Takes:

*Subjects
*Days left
*Hours per day

And generates:
*Day-wise structured timetable
*Balanced study blocks
*Consistent routines

2. Task Manager
You can:

*Add tasks
*Set deadlines
*Mark tasks as completed
*Retrieve pending tasks

3. Personality-Driven AI Responses
Supports:

*Friendly Senior
*Strict Mentor
*Fun & Energetic
*Default Study Assistant

4. Gemini Integration
Uses:

*models/gemini-2.5-flash
*models/gemini-2.5-pro

For:

*Natural language planning
*Study explanations
*Task reasoning
*Personalization

🔧 Tech Stack

| Component             | Details                                  |
| --------------------- | ---------------------------------------- |
| **AI Model**          | Gemini 2.5 Flash / Pro                   |
| **Framework**         | Python                                   |
| **Tools**             | ADK, Gradio (optional), Custom Functions |
| **Notebook Platform** | Kaggle                                   |
| **Memory**            | Session + Long-term                      |

📑 File Structure
📁 study-productivity-ai-agent
 ├── study-productivity-ai-agent.ipynb
 ├── README.md

🧪 How It Works
1️⃣ Setup API
-Add GOOGLE_API_KEY to Kaggle Secrets
-Configure environment
-Install google-generativeai

2️⃣ AI Helper Functions
-gemini_text()
-get_system_instruction()
-gemini_text_with_personality()

3️⃣ Study Plan + Task Tools
-generate_study_plan()
-print_study_plan()
-Task management dictionary

🏁 Project Goal
To build a capable AI productivity system that:

✔ Helps students study smarter
✔ Reduces stress
✔ Supports exam preparation
✔ Keeps tasks organized
✔ Uses AI to personalize learning

>>> Author
Varsha S
Aspiring AIML Student
GitHub: https://github.com/Varsha80
Kaggle: https://www.kaggle.com/varshu31

📌 Notes
This project was created as part of the Kaggle + Google Agents Intensive Capstone 2025.
It demonstrates AI agents, tools, memory, and generative reasoning.
