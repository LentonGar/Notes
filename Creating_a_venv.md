## Navigate to your project directory or create new one
cd my_project

## Create a virtual environment - in this case named "venv" (the second)
python3 -m venv venv

## Activate the virtual environment (Linux/mac)
source venv/bin/activate

## Or on Windows:
.\venv\Scripts\activate

## Install dependencies
pip install requests

## If a list of dependencies is available in a "requirements.txt" file:
pip install -r requirements.txt

## Deactivate the virtual environment when done
deactivate

## Remember, so as to keep GH clean
The virtual environment folder (e.g., venv/) to your .gitignore 
file if you are using Git for version control, as you 
don't need to version control the environment itself. In 
standard .gitignore, this is already there