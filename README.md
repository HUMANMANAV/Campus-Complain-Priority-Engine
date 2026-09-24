# Campus-Complain-Priority-Engine
ECPS is a Flask web app that collects, evaluates, and prioritizes student-reported engineering issues. It features a smart Math &amp; Explainability Engine that calculates urgency based on severity, safety impact, and recurrence, enabling admins to efficiently triage complaints with transparent rationale and pairwise issue comparisons.
# ECPS Triage Engine

**ECPS (Engineering Complaint Prioritization System)** is a Flask-based web application that collects, evaluates, and prioritizes student-reported issues. It features a Math & Explainability Engine that dynamically scores complaints based on category, severity, safety impact, headcount, and recurrence.

## 🚀 Key Features

- **Student Portal**: Secure issue reporting with CAPTCHA verification.
- **Admin Triage**: Dashboard to view issues dynamically ranked by priority score.
- **Smart Prioritization**: Calculates urgency using a mathematical model (+25% score boost for recurring issues).
- **Explainable AI (XAI)**: Generates clear, human-readable rationales for why a specific issue received its priority score and routing.
- **Pairwise Comparator**: Allows admins to compare two issues side-by-side to understand which takes precedence and why.

## ⚙️ How to Run Locally

Everything is packaged in a single Jupyter Notebook.

1. **Install Dependencies:**
   ```bash
   pip install flask werkzeug jupyter
   ```
2. **Run the Project:**
   Open `ECPS_Engine_and_Server.ipynb` and run all cells sequentially. This auto-generates the database, HTML templates, and the backend application.
3. **Access the App:**
   Go to `http://127.0.0.1:5000`. Login with **admin** / **admin123** for the triage dashboard.
