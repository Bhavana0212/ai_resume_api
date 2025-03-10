🏆 AI Resume Screening & Ranking System  

![DALLE2025-03-0723 51 57-AflowchartdiagramillustratingtheprocessofanAI-poweredresumescreeningandrankingsystemstartingfromloginandendingwithresumeranking-ezgif com-jpg-to-png-converter](https://github.com/user-attachments/assets/d8466c05-fbe5-4b4f-a78b-4534a0767a11)


🔍 AI-powered Resume Screening & Ranking System helps HR professionals analyze & rank resumes efficiently using Machine Learning & NLP!  

📌 This GitHub repository contains two projects:  
1️⃣ Version 1 (`resume_screening_system.py`) – Basic functionality (no database/frontend).  
2️⃣ Full AI Resume Screening System – Includes backend, frontend, and database integration.  

🚀 Features  

✔ Upload & Analyze Resumes – Supports multiple formats (PDF, DOCX, TXT, PNG, JPG)  
✔ Job Description Parsing – Extracts key skills & requirements  
✔ AI Matching Algorithm – Calculates resume-to-job fit using TF-IDF  
✔ Candidate Ranking – Sorts candidates based on match score  
✔ Database Integration – Stores and retrieves resumes from PostgreSQL  
✔ Web UI with Streamlit – User-friendly dashboard  
✔ Quick Test with Version 1 – Run `resume_screening_system.py` to check output  

🏗 Project Overview  

📌 Version 1 (Basic Functionality) – Run directly to test ranking!  
📌 Full Project – Complete Flask API + PostgreSQL + Streamlit Web UI  

🎯 Architecture Diagram  

 ![system architech](https://github.com/user-attachments/assets/b92eef04-6692-4b9c-9a6c-3960e3fbe13c)


🎯 Installation & Setup  

🔹 Prerequisites  
✅ Python 3.8+  
✅ PostgreSQL  

🔹 Clone the Repository  
```bash
git clone https://github.com/Bhavana0212/ai_resume_system.git
cd ai_resume_system
```

🔹 Set Up Virtual Environment  
```bash
python -m venv resume_system_env
source resume_system_env/bin/activate   # Mac/Linux
resume_system_env\Scripts\activate      # Windows
```

🔹 Install Dependencies  
```bash
pip install -r requirements.txt
```

🏃‍♀️ Running Version 1 (Basic Code)  
To quickly check how resume ranking works, run:  
```bash
python resume_screening_system.py
```
🔹 Outputs ranking without a database or UI.  

🌐 Running the Full Project  

 ![Flowcharts](https://github.com/user-attachments/assets/9ce39295-63d8-46ff-9d4c-72375b78d135)


🗄 Set Up PostgreSQL Database  
Modify `db_connection.py`:  
```python
DATABASE_URL = "postgresql://postgres:password123@localhost/resume_system" / postgresql://resume_system_user:yuBfSUksRBqFmWFU2bJf3RFSuhn1F7Rh@dpg-cv228b1u0jms738pcmkg-a/resume_system 
```
Create a database & run migrations if needed.  

🏗 Start the Backend (Flask API)  
```bash
cd backend
python api.py
```
✅ Check API: [http://127.0.0.1:5000/ping](http://127.0.0.1:5000/ping)  / https://ai-resume-system.onrender.com 

🎨 Run the Frontend (Streamlit)  
```bash
cd frontend
streamlit run app.py
```

🔥 API Endpoints  

| Endpoint                  | Method | Description |
|---------------------------|--------|-------------|
| `/upload_resume`          | `POST` | Uploads & extracts resume content |
| `/analyze_resume`         | `POST` | Matches resume with job description |
| `/get_candidates`         | `GET`  | Fetches all ranked candidates |
| `/ping`                   | `GET`  | Health check API |

📸 Demo  

🔹 Resume Upload & Ranking Process  

https://github.com/user-attachments/assets/79a16b07-33b0-491a-b708-914e95a8d221

🔹 Candidate Ranking UI   
<img width="1440" alt="figure2" src="https://github.com/user-attachments/assets/81343a2d-b7bf-4a01-a2ca-c4e942c2ee77" />

<img width="1440" alt="figure4" src="https://github.com/user-attachments/assets/935c3ba0-2286-497e-9244-0f7c0383fd65" />

🛠 Technologies Used  

🚀 Backend: Flask, PostgreSQL  
🎨 Frontend: Streamlit  
🧠 AI Models: TF-IDF, NLP (spaCy, NLTK)  
📊 Data Processing: Pandas, NumPy  

🤝 Contributing  

🚀 Want to improve this project? Follow these steps:  

1. Fork the repository  
2. Create a new feature branch  
3. Commit your changes  
4. Push to your fork & submit a PR  

📜 License  
Licensed under MIT License  

🌟 Acknowledgments  
❤️ Built with Flask, Streamlit, PostgreSQL, and AI  
🔹 NLP libraries: spaCy, NLTK, scikit-learn  
🔹 AI Matching: TF-IDF, Cosine Similarity  

📢 Connect with Me  

[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github)](https://github.com/Bhavana0212)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](www.linkedin.com/in/bhavana-shah-875a85137)  
```

This is now completely free of extra formatting symbols and ready for **direct copy-pasting**! 🚀 Let me know if you need any modifications. 😊
