# 🤖 AI-Powered Resume Analyzer

An AI-powered platform that analyzes resumes and provides personalized job recommendations using machine learning — now enhanced with **Google Gemini AI** to offer **smart resume feedback and improvement suggestions**.  
Designed to assist job seekers and recruiters by automating the screening process and suggesting best-fit roles.

---

## 📌 Features

✅ Resume parsing from PDF using PyPDF2  
✅ Text cleaning and preprocessing  
✅ Resume categorization using TF-IDF + Random Forest Classifier  
✅ Job role recommendation based on extracted keywords and categories  
✅ **Smart AI suggestions for resume improvement using Gemini AI**  
✅ Responsive web interface for file upload and result display  
✅ Flask-powered backend for inference and processing  

---

## 🛠️ Tech Stack

| Category             | Technologies Used                                        |
|----------------------|--------------------------------------------------------  |
| 🔍 Machine Learning  | Scikit-learn, TF-IDF Vectorizer, RandomForest           |
| 🧠 AI Integration     | **Google Gemini AI (gemini-1.5-flash)**                |
| 📂 File Handling     | PyPDF2                                                  |
| 🌐 Web Framework     | Flask, HTML, CSS                                        |
| 🖥️ Frontend          | HTML, CSS (Responsive UI)                               |
| 🧪 Tools             | Git, GitHub, VS Code                                    |

---

## 📁 Project Structure

AI-Powered-Resume-Analyzer/
│
├── static/ # CSS and static assets
├── templates/ # HTML templates
├── models/ # Trained ML models and vectorizers
├── app.py # Main Flask backend
├── resume_parser.py # Text extraction and preprocessing logic
├── requirements.txt # Python dependencies
└── README.md # This file


## 🚀 Getting Started

### 🔧 Installation
git clone https://github.com/AbhinashRao/AI-Powered-Resume-Analyzer.git

cd AI-Powered-Resume-Analyzer
pip install -r requirements.txt


▶️ Run the Application
python app.py
Then open: http://localhost:5000 in your browser.

📊 Model Training (Optional)
The Random Forest classifier was trained on cleaned and labeled resume data, transformed using TF-IDF.

💡 Gemini AI Resume Suggestions (New Feature)
We’ve added Gemini AI to:
Summarize the candidate's resume professionally.
Provide constructive feedback and suggestions to enhance the resume.
This makes the platform smarter and more user-friendly for applicants aiming to improve their profile.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

📃 License
This project is open source and available under the MIT License.

🙋‍♂️ Author
Abhinash Rao Madikonda

📧 abhinashrao28@gmail.com

🔗 LinkedIn • GitHub
