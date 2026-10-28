python -m venv .venv
source .venv/bin/activate        # Linux/macOS
# .venv\Scripts\activate         # Windows

pip install latex2sympy2 sympy numpy pytest
pip freeze > requirements.txt
