AutoSupport AI Agent (CLI-based AI Assistant)

This project is a basic Enterprise AI Agent designed to handle customer issue reporting and log them into storage.
It demonstrates how agents can automate IT Support workflows using Python.

🚀 Features

1. Feature	Description
2. Raise New Issue	User enters their complaint and agent logs it
3. View Issue Records	Displays all saved issues
4. CSV Storage	Persistent database-like storage
5. Modular System Design	Easy to scale and integrate with APIs later
6. CLI Interface	Runs in terminal / Colab input
   
🧠 Tech Stack

Python 3
CSV for saved records
Datetime logging

📂 Project Structure

enterprise-task-agent/
│
├── AutoSupport AI.ipynb
├── architecture.png
├── README.md
├── LICENSE
└── data/
    └── issues.csv   # stores all issue reports

🔄 System Architecture

(See architecture.png)

📌 How to Run

1️⃣ Download the repository
2️⃣ Open Notebook in Google Colab / Jupyter
3️⃣ Run all cells
4️⃣ Select from menu:

1 → Create / Raise New Issue
2 → View Issue Records
3 → Exit

📝 Sample Output
1️⃣ Raise New Issue
2️⃣ View Issue Records
3️⃣ Exit

Select an option: 1
Describe customer's issue: I can't login to my account  
📌 Issue saved successfully!

🎯 Future Scope

✔ Add Generative AI (Gemini/OpenAI) to auto-suggest solutions
✔ Deploy as a Web App / Streamlit
✔ Add User Authentication
✔ Integrate Email/WhatsApp notifications
✔ Database integration (MongoDB / MySQL)
✔ Multi-agent workflow (Ticket assign system)

🏆 Why this project matters?

This shows understanding of:

✔ AI Agent Pipeline
✔ Data Logging
✔ Software Engineering skills
✔ Enterprise Automation

👤 Author

Anamika Pandey
BCA — AI/ML Enthusiast
2025
