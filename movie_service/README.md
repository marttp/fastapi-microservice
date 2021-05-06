Create Virtual Environment for Python project  

**python -m venv venv**

---
Activate venv

Windows: .\venv\Scripts\activate

Linux: source ./venv/bin/activate

---
Install dependencies

pip install -r requirements.txt

---
Start Server

uvicorn app.main:app --reload --host 0.0.0.0 --port 8000