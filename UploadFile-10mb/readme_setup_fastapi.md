
## Setup Instructions

```bash
# 1. Create a Virtual Environment (Python 3)

# On macOS and Linux:
cd /path/to/your/project
python3 -m venv venv
source venv/bin/activate

# On Windows:
cd \path\to\your\project
python -m venv venv
venv\Scripts\activate

# 2. Install Required Packages
pip3 install fastapi python-multipart uvicorn

# 3. Run the FastAPI Application
uvicorn main:app --reload #go to http:(web address)/docs and upload the related file

# Additional Notes:
# - Modify main.py and other files as needed for your FastAPI project.
# - Deactivate the virtual environment when done:
deactivate
