# 🛡️ C.O.R.E. – Career Optimization & Recruitment Engine

C.O.R.E. is an AI-powered web platform built to streamline the hiring process for both **job seekers** and **recruiters**. It provides tools like smart resume generation, customizable portfolios, mock interview simulations, and recruiter-side shortlisting powered by AI.

---

## 🚀 Features

### 👨‍💻 For Candidates:
- AI-based Resume Generator
- One-Click Portfolio Builder with shareable links/QR codes
- Mock Interview Simulator with real-time feedback
- Job Role Insights and career tips

### 🧑‍💼 For Recruiters:
- Post job requirements with skill filters
- Smart shortlisting with AI-driven candidate ranking
- View detailed candidate profiles, resumes, and portfolios
- Recruiter dashboard for managing applicants efficiently

---

## 🏗️ Tech Stack

- **Frontend:** HTML, Tailwind CSS, JavaScript, React (optional)
- **Backend:** Odoo (Python-based ERP framework)
- **Database:** PostgreSQL
- **AI Tools:** OpenAI API (for mock interviews and insights)
- **Deployment:** Odoo.sh / VPS / Local Dev

---

## 🛠️ Installation (Local Dev)

```bash
# Clone the repo
git clone https://github.com/yourusername/core-career-platform.git
cd core-career-platform

# Set up a Python virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Make sure PostgreSQL is running
# Run Odoo
./odoo-bin -c odoo.conf
