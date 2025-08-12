# Steps to get started

Create and activate a virtual environment and install requirements.txt

```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
```

Use uvicorn to start the server

```bash
uvicorn main:app --reload
```
