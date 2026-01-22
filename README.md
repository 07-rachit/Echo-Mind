EchoMind – Silent Stress Detection System

EchoMind is a Flask-based AI prototype designed to detect early signs of stress using behavioral and interaction patterns instead of intrusive inputs like cameras, microphones, or questionnaires. The goal is to enable early stress awareness while maintaining user privacy.

This project focuses on proving feasibility rather than claiming medical accuracy.

🚀 Features

Privacy-first stress detection (no camera, no mic)

Behavioral pattern analysis

Lightweight Flask backend

Modular code structure

Easy to extend with ML models

Suitable for students, developers, and remote workers

🛠 Tech Stack

Backend: Python, Flask

ML / Logic: Python (custom logic / model-ready structure)

Frontend: HTML, CSS (via Flask templates)

Tools: Git, GitHub

📂 Project Structure
echomind-flask/
│
├── app.py              # Main Flask application
├── engine.py           # Core logic / stress evaluation engine
├── model.py            # Model handling / abstraction
├── requirements.txt    # Python dependencies
│
├── templates/           # HTML templates
│   └── *.html
│
├── static/              # Static files (CSS, JS)
│
└── __pycache__/         # Python cache (auto-generated)

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/07-rachit/Echo-Mind.git
cd Echo-Mind/echomind-flask

2️⃣ Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate   # Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the application
python app.py

5️⃣ Open in browser
http://127.0.0.1:5000

🧠 Project Objective

Most stress-detection solutions rely on:

Self-reporting

Wearables

Camera or audio monitoring

EchoMind explores a non-intrusive alternative by analyzing behavioral signals, making it suitable for privacy-conscious users and scalable environments.

⚠️ Disclaimer

This project is a prototype for academic and hackathon purposes.
It is not a medical or psychological diagnostic tool.

📌 Future Improvements

Integrate real ML models for stress classification

Add dashboard for stress trends

User authentication

Cloud deployment

Dataset-driven evaluation

👤 Author

Rachit Yadav
B.E. CSE Student: https://github.com/07-rachit
