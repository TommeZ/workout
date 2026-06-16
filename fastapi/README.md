## Tutorial

[How to Build a Next.js + FastAPI Application](https://www.youtube.com/watch?v=g566eI2EmeY&list=WL&index=4)

## Setup

### Create and Activate a Virtual Environment

Navigate to the FastAPI project directory:

```bash
cd fastapi/api
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it:

**macOS/Linux**

```bash
source .venv/bin/activate
```

**Windows**

```bash
.venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Start the FastAPI Server

Make sure you are inside the `fastapi/api` directory (where `main.py` is located), then run:

```bash
fastapi run main.py
```