# Smart Career Toolkit 🚀

A comprehensive career assistance web application built with **Streamlit**. This tool helps students and job seekers optimize their resumes for ATS (Applicant Tracking Systems), build professional resumes from scratch, and calculate their academic CGPA.

## 🌟 Features

## 1. 📄 ATS Resume Scanner
- **File Support:** Upload resumes in **PDF** or **DOCX** format.
- **Smart Scoring:** Algorithms analyze your resume against **60+ technical keywords** (Python, Java, Machine Learning, etc.).
- **Feedback:** Provides a score out of 100 and lists missing skills to help you improve.

## 2. 📝 Resume Creator
- **Interactive Form:** Easy-to-use interface to input Education, Experience, Projects, and Skills.
- **Dynamic Generation:** Instantly compiles your data into a professional **.docx** file.
- **Formatted Output:** clean layout with bullet points and bold headers, ready for download.

## 3. 🧮 CGPA Calculator
- **Customizable:** Calculate CGPA based on the number of semesters completed.
- **SRM Standard:** Designed with university grading standards in mind.

---

## 🛠️ Tech Stack

- **Frontend/Backend:** [Streamlit](https://streamlit.io/)
- **PDF Processing:** [PyMuPDF (fitz)](https://pymupdf.readthedocs.io/)
- **Document Generation:** [python-docx](https://python-docx.readthedocs.io/)
- **Language:** Python 3.x

---

## 💻 Installation & Setup

Follow these steps to run the project locally on your machine.

## 1. Clone the Repository
```bash
git clone [https://github.com/your-username/smart-career-toolkit.git](https://github.com/your-username/smart-career-toolkit.git)
cd smart-career-toolkit

## 2. Create a Virtual Environment (Optional but Recommended)
```bash

python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

## 3. Run the Application
```bash

streamlit run app.py
The app will open in your browser at http://localhost:8501.

## 📂 Project Structure
smart-career-toolkit/
│
├── app.py                # Main application file
├── README.md             # Project documentation
└── .gitignore            # Files to ignore (e.g., venv, __pycache__)

Plaintext

streamlit
python-docx
pymupdf
🤝 Contributing
Contributions are welcome!

Fork the project.

Create your feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
