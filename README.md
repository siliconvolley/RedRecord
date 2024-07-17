# ARC-AI

## Installation:

1. Navigate to `client/`, and install the dependencies,

```bash
cd client && npm install
```

2. Navigate to `server/`, and create a virtual environment `venv`, activate the virtual environment and install the dependencies,

```bash
cd server && python -m venv venv && .\.venv\Scripts\Activate && pip install -r requirements.txt

or

cd server && python3 -m venv venv && source ./venv/bin/activate && pip3 install -r requirements.txt
```

3. Start the backend server,

```bash
cd server && fastapi dev main.py
```

4. Start the client server,

```bash
cd client && npm run dev
```

## NOTE:

- In `server/` directory, create a `secrets.py` file and add your Gemini API Key,

```python
GEMINI_API = '<YOUR_GEMINI_API_KEY>'
```
