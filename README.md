# AI-Agent-for-process-gap-detection

AI-Agent for process gap detection is an intelligent system that analyzes process documents such as Standard Operating Procedures (SOPs) and workflow descriptions to detect gaps, ambiguities, and logical inconsistencies.

The system combines Natural Language Processing, semantic similarity search, and lightweight language models to understand process steps and identify potential issues before execution.

---

# 🛠️ Tech Stack

## Frontend
- HTML
- CSS
- JavaScript

## Backend
- Python
- FastAPI
- Uvicorn

## AI / NLP
- spaCy
- sentence-transformers
- FAISS
- Phi-3 Mini
- Custom Python Rule Engine

## PDF Processing
- pdfplumber

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/durganeha/AI-Agent-for-process-gap-detection.git
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

## 🌐 Frontend

Run the frontend server:

```bash
python -m http.server 5501
```

Open in browser:

```bash
http://127.0.0.1:5501/web/
```

---

## ⚡ Backend

Run the backend server:

```bash
uvicorn api.app:app --reload
```

Open API documentation:

```bash
http://127.0.0.1:8000/docs
```

---

# 📖 How It Works

1. Upload SOP documents through the frontend UI.
2. Backend extracts and preprocesses text.
3. AI pipeline converts process steps into semantic representations.
4. The system detects missing or inconsistent workflow steps.
5. Results are generated in structured JSON format.
6. Users can view analysis directly through the frontend.





