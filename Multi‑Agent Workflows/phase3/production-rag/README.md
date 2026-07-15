# Production Hybrid RAG

## Prerequisites

- Python 3.13+
- PostgreSQL
- OpenAI API Key

---

## Installation

### Step 1: Clone the repository

```bash
git clone <repository-url>
cd production-rag
```

### Step 2: Create a virtual environment

```bash
python3 -m venv venv
```

### Step 3: Activate the virtual environment

**macOS/Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### Step 4: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 5: Configure environment variables

Create a `.env` file and add:

```text
OPENAI_API_KEY=your_api_key
```

### Step 6: Run the application

```bash
uvicorn app.main:app --reload
```

### Step 7: Open Swagger UI

```
http://127.0.0.1:8000/docs
```
