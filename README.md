# Getting Started with GitHub Copilot

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

Hey Klawler23!

Mona here. I'm done preparing your exercise. Hope you enjoy! 💚

Remember, it's self-paced so feel free to take a break! ☕️

[![](https://img.shields.io/badge/Go%20to%20Exercise-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/Klawler23/skills-getting-started-with-github-copilot/issues/1)

---

## Project Overview

This repository implements a small FastAPI application for the Mergington High School extracurricular activity signup system. Students can view available activities, register for a club, and unregister from an activity.

The frontend is served from `src/static/`, while the backend API lives in `src/app.py`.

## Setup

1. Create and activate a Python environment (recommended):
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the app

Start the FastAPI server with:

```bash
uvicorn src.app:app --reload
```

Then open `http://127.0.0.1:8000` in your browser.

## Testing

The repository includes backend tests in the `tests/` folder.

Run the test suite with:

```bash
pytest
```

## Notes

- `requirements.txt` now includes `pytest` for running the backend test suite.
- Tests use FastAPI `TestClient` and reset the in-memory activity data between cases.

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

