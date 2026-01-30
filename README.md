# Phish Analyzer 🛡️

Phish Analyzer is a cybersecurity-focused project designed to detect and analyze phishing URLs/websites using data analysis and machine learning techniques. The goal of this project is to help identify malicious links and improve user awareness against phishing attacks.

---

## 🚀 Project Objectives
- Detect phishing websites and URLs
- Analyze features commonly used in phishing attacks
- Improve online safety through automated detection
- Demonstrate practical application of cybersecurity concepts

---

## 🧰 Technologies Used
- Python
- Machine Learning
- Scikit-learn
- Pandas & NumPy
- Jupyter Notebook
- Git & GitHub

---

## 📂 Project Structure
- `data/` – Dataset used for training and testing
- `src/` – Source code for preprocessing and model building
- `models/` – Trained machine learning models
- `notebooks/` – Analysis and experimentation notebooks
- `README.md` – Project documentation

---

## ⚙️ How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/phish-analyzer.git
#  Phish Analyzer — Heuristic-Based Phishing Email Detection

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-green)](https://streamlit.io/)

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Demo / Screenshots](#demo--screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview
Phish Analyzer is a **heuristic-based phishing email simulator and analyzer** built using **Python and Streamlit**.  

It is designed to help:
- **Non-technical users** understand phishing risks.
- **Security enthusiasts** analyze email campaigns.
- **Students & professionals** simulate phishing campaigns for learning purposes.

With this tool, you can **upload email CSV logs** or **simulate campaigns**, analyze risk levels, and get **actionable advice** for safe email behavior.

---

## Features
- **CSV-based analysis:** Supports GoPhish CSV exports or any email dataset.
- **Simulate phishing campaigns:** Randomly generate emails with clickable links and test user behavior.
- **Heuristic risk scoring:** Detect phishing emails based on keywords, link patterns, domain reputation, and click/report status.
- **Risk labels:** Low / Medium / High scoring with color-coded dashboard.
- **Domain summary:** Analyze suspicious domains used in emails.
- **Top risky recipients:** Easily identify high-risk users in campaigns.
- **User advice:** Suggest safe email practices.
- **Theme toggle:** Switch between light and dark mode for user comfort.
- **Export results:** Download analyzed CSV for reporting.

---

## Demo / Screenshots
### Example Dashboard
![Dashboard Screenshot](https://github.com/Chandan-kumar10/phish-analyzer/tree/main/phish-analyzer/Screenshorts))


- **Risk Distribution Pie Chart**: Visual overview of email risks.
- **Top Risky Recipients**: Sorted table for quick analysis.
- **Domain Summary**: Identify suspicious domains in email links.

---

## Installation
```
pip install streamlit pandas matplotlib
```

## Usage
Run the app
```
python -m streamlit run app.py
```

Open the URL shown in terminal (usually(http://localhost:8501/)).

Use the sidebar to:

Simulate phishing emails or upload your own CSV.

Adjust number of emails, phishing fraction, click/report probabilities.

Edit keywords and suspicious domains.

Switch between light/dark mode.

View the dashboard:

Total emails, high-risk emails, reported emails.

Risk distribution pie chart.

Top risky recipients.

Domain summary.

Download the analyzed CSV if needed.

## How It Works

Keywords: Checks email subject/body for risky words (e.g., verify, urgent, account suspended).

Link Analysis: Flags suspicious domains, URL shorteners, and IP-based URLs.

User Behavior: Clicking a link increases risk, reporting decreases risk.

Risk Scoring: Combines all heuristics to generate a score (0–100) and assign a label (Low / Medium / High).

## Contributing

Contributions are welcome! You can:

Improve the heuristic scoring system

Add more realistic phishing simulation templates

Improve dashboard UX

Optimize performance

## License

This project is MIT licensed. See LICENSE
 for details.

 ## Contact

GitHub: https://github.com/Chandan-kumar10

Email: ck598364@gmail.com
