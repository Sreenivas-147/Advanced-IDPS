# Advanced Intrusion Detection and Prevention System (Advanced_IDPS)

An intelligent and secure Intrusion Detection and Prevention System (IDPS) built using machine learning techniques on the NSL-KDD dataset. This project detects and prevents network-based cyberattacks in real time with a web interface.

---

## 🔒 Features

- 🚀 Machine Learning-based threat detection
- 📊 Trained on NSL-KDD dataset (2025)
- 🌐 Web dashboard using Flask
- 📝 Real-time logging of detected threats
- 📁 Model persistence using joblib
  
---

## 🧠 ML Model Training

- File: `IDPS_Train_Model.ipynb`
- Dataset: `NSL-KDD-2025`
- Libraries: `scikit-learn`, `pandas`, `joblib`

> Trains and evaluates various models to identify anomalies in network traffic.

---

## 🌐 Web Application

- Entry point: `app.py`
- Templates: `templates/`
- Static files (CSS/JS): `static/`
- Frontend: Simple UI to upload logs and see detection results.

---

## 📁 Folder Structure


---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/advanced-idps.git
cd advanced-idps

# Create virtual environment
python -m venv venv
source venv/bin/activate      # On Linux/Mac
venv\Scripts\activate         # On Windows

# Install dependencies
pip install -r requirements.txt

🚀 Running the App
# Activate environment and run Flask app
python app.py


)

📚 Dataset
NSL-KDD 2025 is an improved version of the classic KDD Cup 1999 dataset.
Includes labeled records for DoS, Probe, R2L, and U2R attacks.

.

🤝 Contributors
Thammisetti Sreenivasulu
Cybersecurity Intern | B.Tech in CSE - Cybersecurity
GitHub: Sreenivas-147

📬 Contact
For questions or contributions, reach out at:
📧 sree.tham147@gmail.com
