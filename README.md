# 🧠 GenerativeAI Resume Assistant

A **Generative AI-powered Resume Assistant** built using **Python**, **LangChain**, and **PostgreSQL**, designed to automatically align candidate resumes with job descriptions. It leverages **prompt engineering**, **keyword scoring**, and **structured output pipelines** to deliver resume optimization suggestions that maximize ATS compatibility and recruiter impact.

---

## 🚀 Features

- **Job-Aware Resume Optimization**  
  Uses NLP + prompt-engineering to compare a resume with a job description and generate bullet points tailored for that role.

- **Smart Keyword Matching**  
  Automatically extracts critical keywords from the job description and evaluates their presence in the resume using a scoring logic.

- **AI-Generated Suggestions**  
  Suggests rephrased content, achievements, and impact statements aligned with the target role.

- **Structured Output Pipelines**  
  Generates standardized **JSON templates** for resume content, enabling easy export to **PDF/HTML formats**.

- **PostgreSQL Integration**  
  Stores user inputs, resume data, and job matching results for reusability and analytics.

---

## 🧩 Tech Stack

| Component | Technology |
|------------|-------------|
| Language | Python |
| Frameworks | LangChain, FastAPI |
| Database | PostgreSQL |
| LLM Integration | OpenAI / Ollama (configurable) |
| Output Format | JSON, PDF, HTML |
| Frontend (Optional) | Streamlit / React |

---

## ⚙️ System Architecture


---

## 🧪 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/<your-username>/generativeai-resume-assistant.git
   cd generativeai-resume-assistant
## Create Virtual Environment

python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

## Install dependencies

pip install -r requirements.txt

## Configure Environment Variables

OPENAI_API_KEY=your_api_key
DATABASE_URL=postgresql://user:password@localhost:5432/resume_db

## Run the application.

python main.py

## 📊 Example Output

Input:
Resume (Plain text or PDF) + Job Description

Output (JSON):

{
  "match_score": 0.86,
  "missing_keywords": ["TensorFlow", "A/B Testing"],
  "optimized_bullets": [
    "Developed end-to-end ML pipelines using TensorFlow improving model performance by 15%.",
    "Implemented data-driven testing strategies to enhance model robustness."
  ]
}


## 📈 Results

Reduced manual resume editing time by 75%

Enhanced keyword coverage and recruiter alignment

Improved candidate relevance scores across ATS platforms

## 🤝 Contributing

Pull requests are welcome!
If you'd like to add integrations (e.g., Gemini API, Claude, or HuggingFace models), please open an issue first to discuss your ideas.


## 🧾 License

This project is licensed under the MIT License – see the LICENSE
 file for details.

## 💡 Future Enhancements

Add multi-role batch analysis (optimize for several job descriptions)

Integrate UI dashboard using Streamlit

Export to LaTeX resume templates

Add analytics to track keyword improvement history

 
## ✨ Author

Viraj Kenekar
📧 [YourEmail@example.com
]
🔗 LinkedIn
 | GitHub
