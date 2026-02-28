# Rubik's Cube Exploration

This project explores Rubik’s Cube mathematics and algorithms using Python, JupyterLab, and data‑science visualization tools.

## Quick Start (Docker Compose)
1. Copy the env template and adjust the token if desired:

```bash
cp .env.example .env
```

2. Build and start JupyterLab:

```bash
docker compose up --build
```

3. Open JupyterLab in your browser:

```
http://localhost:8888
```

Use the token from `.env` (`JUPYTER_TOKEN`).

## Local Setup (Optional)
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pip install -e .
```

## Project Structure
- `notebooks/`: Exploration notebooks
- `src/`: Reusable Python modules
- `data/`: Local datasets and artifacts (ignored, except `.gitkeep`)

## Notes
- Keep notebooks reproducible top‑to‑bottom.
- Move stable utilities from notebooks into `src/`.
