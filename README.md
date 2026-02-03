# Quantum Computing

This is a repository for my quantum computing independent study.

## Setup

### 1. Create and Activate Virtual Environment

**Windows (PowerShell):**

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**Windows (Command Prompt):**

```cmd
python -m venv .venv
.venv\Scripts\activate.bat
```

**macOS/Linux:**

```bash
python -m venv .venv
source .venv/bin/activate
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run Jupyter Notebook

```bash
jupyter notebook
```

This will open a browser window at `http://localhost:8888` where you can access and run `single_systems.ipynb`.

## Project Files

- `single_systems.ipynb` - Main notebook exploring quantum state vectors, operators, and circuits
- `requirements.txt` - Python package dependencies
