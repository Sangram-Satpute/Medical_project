MedicalClear – AI-Powered Medical Report Analysis System
📌 Project Overview

MedicalClear is an AI-powered web application developed using Python and Django that helps users analyze medical reports and understand important health-related information in a simple and organized manner.

The system allows users to upload medical reports, extracts relevant medical information, identifies abnormal values, and presents the analysis through an easy-to-understand dashboard.

Note: MedicalClear is an educational/software project and is not intended to replace professional medical diagnosis or treatment.

🎯 Objectives
Analyze uploaded medical reports automatically.
Extract important medical parameters and values.
Identify abnormal or potentially concerning results.
Provide understandable health-related insights.
Present report information through a user-friendly dashboard.
Reduce the difficulty of understanding complex laboratory reports.
Provide an AI-assisted medical information analysis workflow.
✨ Key Features
🔐 User Authentication
User registration
Secure login
Logout functionality
Password reset functionality
📄 Medical Report Upload
Upload medical report files.
Store report information for analysis.
Process medical report data.
🤖 AI-Based Analysis
Analyze extracted medical information.
Identify abnormal health parameters.
Categorize possible health concerns.
Generate understandable explanations.
📊 Dashboard
Display uploaded reports.
Show analysis results.
Highlight important medical parameters.
Present health-related insights in an organized interface.
🏥 Health Parameter Analysis

The system can be designed to analyze parameters such as:

Hemoglobin
Blood Glucose
HbA1c
Cholesterol
LDL
HDL
Triglycerides
Vitamin D
TSH
Creatinine
WBC
Platelets
Liver function parameters
Urine parameters
🛠️ Technologies Used
Technology	Purpose
Python	Backend programming
Django	Web framework
HTML5	Frontend structure
CSS3	Styling
JavaScript	Frontend interaction
SQLite	Database
Groq API	AI-assisted analysis
Git & GitHub	Version control
Python Virtual Environment	Dependency management
🏗️ System Architecture
                ┌──────────────────────┐
                │       User           │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │   Django Web App     │
                └──────────┬───────────┘
                           │
              ┌────────────┴────────────┐
              │                         │
              ▼                         ▼
      ┌───────────────┐         ┌────────────────┐
      │ Report Upload │         │ Authentication  │
      └───────┬───────┘         └────────────────┘
              │
              ▼
      ┌────────────────┐
      │ Report Parsing │
      └───────┬────────┘
              │
              ▼
      ┌────────────────────┐
      │ AI Analysis Engine │
      └─────────┬──────────┘
                │
                ▼
      ┌────────────────────┐
      │ Health Insights    │
      │ & Abnormal Values  │
      └─────────┬──────────┘
                │
                ▼
      ┌────────────────────┐
      │ User Dashboard     │
      └────────────────────┘
      <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f448c540-da5b-428f-b6af-1200479a7f15" />


<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/5fe467a1-50ec-4bed-a348-db4380078d11" />

⚙️ Installation & Setup
1. Clone the repository
git clone https://github.com/Sangram-Satpute/Medical_project.git
2. Open the project
cd Medical_project
3. Create virtual environment
python -m venv venv
4. Activate virtual environment

Windows PowerShell:

.\venv\Scripts\Activate.ps1

Windows CMD:

venv\Scripts\activate
5. Install dependencies
pip install -r requirements.txt
6. Configure environment variables

Create a .env file in the project root:

GROQ_API_KEY=your_api_key_here

Do not upload .env or API keys to GitHub.

7. Apply database migrations
python manage.py migrate
8. Run the development server
python manage.py runserver

Open:

http://127.0.0.1:8000/
🔑 Environment Variables

The project uses environment variables for sensitive credentials.

Example:

GROQ_API_KEY=your_groq_api_key

Make sure .env is included in .gitignore:

.env
venv/
__pycache__/
*.pyc
db.sqlite3
🔄 Application Workflow
1. User Registration/Login
             ↓
2. Upload Medical Report
             ↓
3. Report Processing
             ↓
4. Extract Medical Parameters
             ↓
5. AI-Based Analysis
             ↓
6. Detect Abnormal Values
             ↓
7. Generate Health Insights
             ↓
8. Display Results on Dashboard
🧪 Example Analysis
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/c95e821c-cabb-4aa1-a22b-3cab775eeb5b" />

A sample report may contain:

Fasting Blood Glucose: 118 mg/dL
HbA1c: 6.2%
LDL Cholesterol: 142 mg/dL
Vitamin D: 18 ng/mL
TSH: 4.8 mIU/L

The system can flag these values as requiring attention based on the reference ranges provided in the report and present them as possible health-condition categories, rather than claiming a definitive diagnosis.

🔒 Security

Medical information can be sensitive. The project follows basic security practices such as:

Environment variables for API credentials.
.env excluded from Git.
Authentication for user accounts.
Django's built-in security mechanisms.
Avoiding hard-coded API keys.

Never commit API keys, passwords, tokens, or private credentials to GitHub.

⚠️ Disclaimer

MedicalClear is developed for educational, academic, and software demonstration purposes.

The analysis provided by the application should not be considered a medical diagnosis. Users should consult a qualified healthcare professional for interpretation of medical reports, diagnosis, treatment, and medical decisions.

🚀 Future Enhancements
PDF report text extraction and OCR.
Advanced medical parameter recognition.
Improved AI-based report summarization.
Graphical visualization of health parameters.
Historical report comparison.
Personalized health trends.
Multi-language support.
Doctor/healthcare professional dashboard.
Cloud deployment.
Advanced role-based authentication.
Automated report classification.
Improved NLP-based medical entity extraction.
🎓 Academic Project

Project Name: MedicalClear – AI-Powered Medical Report Analysis System

Domain: Artificial Intelligence / Healthcare / Web Development

Backend: Python Django

Database: SQLite

AI Integration: Groq API

Project Type: Academic / Final Year IT Engineering Project
