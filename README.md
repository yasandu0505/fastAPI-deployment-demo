# fastAPI-deployment-demo

A simple FastAPI demo project with a health check endpoint.

## Setup

1. Creating virtual environemnt
```bash
python3 -m venv venv
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
uvicorn main:app --reload
```

4. Access the health endpoint:
- Open your browser to `http://localhost:8000/health`
- Or view the interactive API docs at `http://localhost:8000/docs`

## Test the endpoint

```bash
curl http://localhost:8000/health
```