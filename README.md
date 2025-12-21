# GenAI Phishing Website Detection

## 🚀 Project Setup

### Initialize Project

```bash
# Initialize project with uv
uv init

# Rename default branch to main
git branch -m master main

# Check uv version
uv --version

# List available Python versions
uv python list
```

### Create Virtual Environment

```bash
# Create virtual environment with Python 3.11
uv venv env --python cpython-3.11.13-windows-x86_64-none
```

### Activate Environment and Install Dependencies

**Windows:**
```bash
# Activate virtual environment
env\Scripts\activate

# Install requirements
uv pip install -r requirements.txt
```

## 🌐 Running the Application

Start the GenAI Phishing Website Detection app:

```bash
uvicorn backend.app:app --reload
```
