# AI-Resume-Analyser

License: MIT

# Problem Statement

Many students and professionals struggle with:

Resume Analysis: Understanding what skills to highlight

Career Guidance: Choosing the right career path

Skill Development: Identifying what to learn next

Job Search: Finding relevant job opportunities

# Solution: AI-Resume-Analyser

AI-Resume-Analyser is an intelligent AI-powered career mentor that:

Analyzes resumes using advanced PDF parsing
Provides personalized career guidance using RAG (Retrieval-Augmented Generation)
Identifies skill gaps and suggests learning paths
Scrapes LinkedIn job data for real-time job insights
Recommends suitable job roles based on user profiles

# Key Features

1. Advanced Resume Parsing
PyPDF2 Integration: Efficient text extraction from PDF resumes
Smart Text Processing: Handles structured and unstructured resumes
Skill Detection: Identifies key technical and soft skills
Project Analysis: Extracts and evaluates project details
2. AI-Powered Career Guidance
RAG Pipeline: Context-aware responses using LangChain
Personalized Suggestions: Based on resume content
Skill Gap Analysis: Identifies missing skills for target roles
Career Recommendations: Suggests suitable job titles
Learning Roadmaps: Step-by-step improvement plans
3. LinkedIn Job Scraper
Built using Selenium automation
Extracts:
Company Name
Job Title
Location
Job URL
Job Description

👉 Helps users directly explore job opportunities

4. Modern Web Interface
Built with Streamlit
Easy resume upload
Interactive UI
Real-time AI responses
Clean and responsive design
🛠️ Technical Stack
🔹 Backend
Python
LangChain
FAISS
OpenAI API
🔹 Frontend
Streamlit
HTML/CSS
🔹 AI/ML
Large Language Models (LLM)
Retrieval-Augmented Generation (RAG)
Hugging Face Transformers
🔹 Automation
Selenium WebDriver
📊 Performance Metrics
Component	Status	Performance
Resume Parsing
✅ Working	High accuracy Resume Analysis
✅ Working	Smart insights RAG Pipeline	
✅ Working	Context-awareLinkedIn Scraper	
✅ Working	Real-time dataWeb Interface	
✅ Working	User-friendly

# Project Structure
Sahay-AI/
├── app.py                     # Main Streamlit app
├── src/
│   ├── rag/                  # RAG pipeline
│   ├── scraper/              # LinkedIn scraper
│   └── utils/                # Resume parsing
├── data/                     # Sample resumes
├── requirements.txt
└── README.md

🚀 Quick Start
📌 Prerequisites
Python 3.8+ pip

⚙️ Installation
# Clone the repository
git clone https://github.com/manjulabandari/AI-Resume-Analyzer-and-LinkedIn-Scraper-with-Selenium.git

# Navigate to project
cd AI-Powered-Resume-Analyzer-and-LinkedIn-Scraper-with-Selenium

# Install dependencies
pip install -r requirements.txt
▶️ Run the Application
streamlit run app.py

Open in browser:
👉 http://127.0.0.1:5000/

🎨 Features Demo
📄 Resume Analysis
Upload resume
Get summary, strengths, weaknesses
View recommendations
🤖 AI Career Chat
Ask career-related questions
Get personalized responses
📊 Skill Gap Analysis
Compare current vs required skills
Get improvement suggestions
💼 Job Insights
View scraped LinkedIn job data
Explore job roles and descriptions
🏆 Project Impact
🔹 Technical Innovation
RAG-based AI career guidance
Resume + Job data integration
Automation using Selenium
Vector search using FAISS
🔹 User Value
Personalized career guidance
Resume improvement insights
Real-time job opportunities
Structured learning paths
🔧 Improvements
Enhanced resume parsing accuracy
Improved response quality using RAG
Optimized performance for faster analysis
Clean UI for better user experience
🎯 Developed By

👩‍💻 Manjula Bandari
AI-Resume-Analyser – Your intelligent career companion powered by AI

📫 Contact
📧 Email: manjulabandari21@gmail.com     
🌐 LinkedIn: https://www.linkedin.com/in/manjula-bandari-348347361
