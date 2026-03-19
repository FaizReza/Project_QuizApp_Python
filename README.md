# QuizApp in Python

# 🎓 Python Quiz Application

A robust, full-featured web-based Quiz Application built with **Python (Flask)** and **SQLite**. This application offers a seamless experience for students to take assessments and provides administrators with powerful tools to manage content, users, and analyze performance.

---

## 🚀 Key Features

### 👤 User Panel
*   **interactive Quizzes**: Timed quizzes with immediate feedback on submission.
*   **Smart Dashboard**: Tree-view navigation of Subjects, Topics, and Quizzes tailored to user group access.
*   **History & Review**: 
    *   Detailed attempt history with filtering and sorting.
    *   **PDF Download** of result cards.
    *   Review mode to analyze correct vs. incorrect answers.
*   **Theme Support**: Toggle between 🌑 **Dark** and ☀️ **Light** modes.

### 🛡️ Admin Panel
*   **Content Management System (CMS)**: 
    *   Manage hierarchy: **Subject → Topic → Quiz**.
    *   **CSV Import**: Bulk import questions for quizzes.
    *   Drag-and-drop hierarchy adjustments (via move functionality).
*   **User & Group Management**: 
    *   Role-based access control (Admin/User).
    *   **Bulk User Import** via CSV.
    *   Group-based subject access assignments.
*   **Analytics & Reporting**:
    *   📊 **Visual Dashboard**: Charts for performance trends, pass/fail ratios, and top topics using **Chart.js**.
    *   🏆 **Leaderboard**: View top performers by Subject, Topic, or Quiz.
    *   **Data Export**: Download comprehensive result data as CSV.

---

## 🛠️ Tech Stack

| Component | Technology |
| :--- | :--- |
| **Backend** | Python 3, Flask |
| **Database** | SQLite (Built-in) |
| **Frontend** | HTML5, CSS3, JavaScript (Chart.js) |
| **Security** | Werkzeug (PBKDF2 Hashing), Dotenv |
| **Reporting** | FPDF (PDF Generation) |

---

## ⚙️ Installation & Setup

### 1. Prerequisites
*   Python 3.8+ installed on your system.

### 2. Installation
Navigate to the project folder and install the required dependencies:

```bash
pip install flask python-dotenv fpdf
```

### 3. Configuration
Create a `.env` file in the root directory to secure your app:

```env
SECRET_KEY=your_super_secret_key_change_this
SECURITY_PEPPER=your_security_pepper_value
```

Access the application in your browser at:
👉 **http://<FQDN>:<Curstom_Port>**

---

## 🔐 Default Credentials

The system automatically creates a default admin account on the first run.

> ⚠️ **Security Note:** It is highly recommended to change the admin password immediately after the first login.

---

## 📂 Project Structure

<details>
<summary><b>Click to expand file structure</b></summary>

```text
Quiz_App/
├── quiz_app.py          # Core application logic (Flask routes & views)
├── quiz_app.db          # Database file (Auto-generated)
├── .env                 # Configuration secrets
├── README.md            # Project documentation
└── templates/           # (Templates are currently embedded in .py for portability)
```
</details>

## 📬 Contact Information

For program demonstration, collaboration and/or setup the custom environment for your requirement, please feel free to reach out!

**Name:** Faiz Sultan
**Email:** [faiz.sultan@gmail.com](mailto:faiz.sultan@gmail.com)

---
*Automate the boring stuff, focus on the architecture.*
