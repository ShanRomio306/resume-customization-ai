# 🧠 Resume Customization AI

**Resume Customization AI** is a full-stack web application that helps job seekers tailor their resumes using Gemini AI, evaluate them against job descriptions using ATS logic, and download polished versions in `.docx` or `.pdf` format. Built for impact, speed, and user control.

---

## 🚀 Features

- ✨ **AI Resume Transformation**  
  Uses Gemini to rewrite resumes based on job descriptions for better relevance and clarity.

- 📊 **ATS Match Scoring**  
  Visual chart shows how well your resume matches the job description using keyword analysis.

- ✍️ **Live Resume Editor**  
  Edit the AI-generated resume before downloading — full control, no surprises.

- 📥 **Multi-Format Downloads**  
  Export your resume as `.docx` or `.pdf` with clean formatting.

- 🔐 **User Authentication**  
  Secure sign-up and login system with password hashing.

- 📁 **Resume History Dashboard**  
  View all past resume transformations with timestamps and scores.

- ☁️ **Cloud Database**  
  Powered by PostgreSQL on Railway for scalable, persistent storage.

---

## 🛠 Tech Stack

| Layer       | Technologies Used                                      |
|-------------|--------------------------------------------------------|
| Frontend    | HTML, Bootstrap 5, Chart.js                            |
| Backend     | Flask, Flask-SQLAlchemy                                |
| AI Engine   | Gemini via `google-generativeai`                       |
| Export      | `fpdf` for PDF, `python-docx` for DOCX                 |
| Database    | PostgreSQL (hosted on Railway)                         |
| Auth        | Werkzeug password hashing                              |
| Config      | `.env` with `python-dotenv`                            |

---

## 📦 Installation

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/resume-ai-app.git
   cd resume-ai-app
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file  
   ```
   SECRET_KEY=your_flask_secret_key
   DATABASE_URL=your_postgresql_connection_string
   GEMINI_API_KEY=your_gemini_api_key
   ```

4. Run the app  
   ```bash
   python app.py
   ```

---

## 💡 Future Enhancements

- Resume templates and styling options  
- Email verification and password reset  
- Job matching and application tracking  
- Deployment on Render or Railway

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙌 Acknowledgments

Built with passion and persistence by Shan — empowering job seekers with AI and beautiful design.

