# AI-Resume-Critiquer
This model analyze your resume and based on that suggest changes and job role...

# AI Resume Critiquer

AI Resume Critiquer is a Streamlit-based web application that uses LLMs (LLaMA 3 via Groq API) to provide AI-powered resume feedback. Users can upload their resumes (PDF or TXT) and receive detailed suggestions on improving content, structure, and job relevance — all in real-time.

---

## 🚀 Features

- 📄 Upload PDF or TXT resumes.
- 🤖 Powered by `LLaMA 3` via the `Groq API`.
- 🎯 Personalized feedback based on a specified job role.
- 📋 Constructive review of content clarity, skills, experience, and formatting.
- 🧵 Clean and interactive Streamlit UI.

---

## 🛠️ Tech Stack

- **Frontend/UI**: [Streamlit](https://streamlit.io/)
- **LLM Integration**: [LangChain](https://www.langchain.com/) + [Groq API](https://console.groq.com/)
- **Model**: `llama3-70b-8192` via `ChatGroq`
- **Environment Management**: `python-dotenv`

---

 ## 📦 Installation
 
 ### 1. Clone the Repository

- git clone https://github.com/Gayatrisjadhav/AI-Resume-Critiquer.git
- cd AI-Resume-Critiquer

### 2. Set Up a Virtual Environment


python -m venv env
source env/bin/activate    # On Windows: env\Scripts\activate

### 3. Install Dependencies

pip install -r requirements.txt

### 4. Configure Environment Variables
Create a .env file in the project root with your Groq API key:

GROQ_API_KEY=your_groq_api_key_here

### Run the app

streamlit run app.py
The app will launch at http://localhost:8501

## 📌 Usage
- Upload your resume in PDF or TXT format.

- Optionally specify the job role you’re targeting.

- Click Analyze Resume.

- View structured feedback directly on the page.

## 📂 Project Structure

AI-Resume-Critiquer/
- ├── app.py                  # Main Streamlit app
- ├── .env                   # Groq API key (not checked in)
- ├── requirements.txt       # Python dependencies
- └── README.md              # Project documentation


# 💡 Future Enhancements
- Resume scoring system (0–100)

- Keyword optimization and ATS check

- Downloadable PDF feedback reports

- Job role-specific resume templates



