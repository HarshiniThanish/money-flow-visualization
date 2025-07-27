# Fund Trail Analysis - Web Backend

This is a Flask-based web application built for visualizing and analyzing fund trails in cybercrime investigations. It allows authorities to upload datasets, inspect transaction networks, and trace illicit financial flows. The project was developed with real-world problems provided by the Tamil Nadu Police Cyber Crime Unit.

---

## 🚀 Features

- Upload and visualize financial transaction data
- Generate fund flow graphs and network trees
- User authentication for secure access
- Persistent storage using SQLite
- Preloaded sample data (`cleandata.xlsx`) for quick testing

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript (with D3.js for visualizations)
- **Database**: SQLite (via SQLAlchemy ORM)
- **Others**: Bootstrap, Flask-Jinja2 templates

---

## 📁 Project Structure

fundtrail_backend_web/
├── app.py # Main Flask app
├── models.py # SQLAlchemy models
├── setup.sql # Database schema (for initial setup)
├── instance/
│ └── fundtrail.db # SQLite DB (example instance)
├── uploads/
│ └── cleandata.xlsx # Sample cleaned transaction data
├── templates/ # HTML templates
│ ├── index.html
│ ├── login.html
│ ├── complaint.html
│ └── graph_tree.html
├── static/
│ ├── style.css # Custom CSS
│ ├── graph.js # D3.js visualization script




---

## 🔧 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fundtrail_backend_web.git
cd fundtrail_backend_web
2. Create a virtual environment and activate it

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3. Install dependencies

pip install -r requirements.txt
If requirements.txt is missing, manually install:


pip install flask sqlalchemy openpyxl
4. Run the application

python app.py
Visit http://127.0.0.1:5000 in your browser.

📷 Screenshots
<img width="1827" height="773" alt="Screenshot 2025-07-24 234141" src="https://github.com/user-attachments/assets/a3cf986a-c0f7-46d8-9a4d-bf4914411b22" />


🤝 Acknowledgements
Special thanks to the Tamil Nadu Cyber Crime Police for providing real-case datasets and problem statements.

📜 License
This project is licensed under the MIT License.


