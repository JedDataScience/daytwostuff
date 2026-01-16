## Simple Recipe: Creating a New Working Project Environment

1. Clone the repo from GitHub (or fork it first if needed).
2. Open the project in VS Code (Codespace or local).
3. Open a terminal in the project folder.
4. Create a virtual environment  
   - `python -m venv venv`
5. Activate the virtual environment  
   - Mac/Linux: `source venv/bin/activate`  
6. Install dependencies from `requirements.txt`  
   - `pip install -r requirements.txt`
7. Confirm things installed correctly  
   - `python --version`  
8. If you install new packages, update `requirements.txt`  
   - `pip freeze > requirements.txt`
9. Commit and push changes to GitHub  