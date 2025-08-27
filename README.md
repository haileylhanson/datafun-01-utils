# datafun-01-utils
CC1.4: Start a Professional Python Project



Reusable module for my Data Analytics Python projects

Project Requirements
VS Code
Git
Python
Use Standard Professional Workflow
See pro-analytics-01

Commands to Manage Virtual Environment
These commands will:

Create virtual environment in .venv folder
Activate .venv
Upgrade core tools
Install external project packages
Verify installed packages
Mac/Linux

python3 --version
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install --upgrade -r requirements.txt
pip list
Windows PowerShell

py --version
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install --upgrade -r requirements.txt
py -m pip list
Commands to Run Python Script
Mac/Linux

python3 utils_case.py
Windows PowerShell

py utils_case.py
To stop a running Python program, press Ctrl + C in the terminal (works the same on Windows, Mac, and Linux).

Commands to Git add-commit-push
Write a custom message (-m) in quotes describing what was done, e.g. "completed first TODO", "final commit", etc.

These commands work the same in all terminals and will:

Add all new and modified files in the current project folder into Git staging area. The . means everything in this folder.
Commit (record) a snapshot of staged changes with a descriptive message that will appear in the repo history.
Push (upload) commits from local machine to the remote (GitHub) repo (alias origin) on the main branch. The -u tells Git to remember this this branch mapping on upstream commands, so future git push commands can be shorter (just git push).
git add .
git commit -m "custom message here"
git push -u origin main
Reference Project
This project is a custom implementation of the example project at datafun-01-utils.

Writing Good README.md Files
Every GitHub project has a README.md file with an overview. The file type is Markdown and it's a very simple Markup language for text.

A Markdown title starts with: hash space
A Markdown second-level heading starts with: hash hash space
A Markdown un-ordered list starts with: dash space
A Markdown ordered list start with: 1. space
Markdown code fencing uses three back tics on their own line to display code and commands.
Markdown bold text is surrounded by: two asterisks
Markdown underline text is surrounded by: one asterisk
Markdown skills are critical for project README files, Jupyter Notebooks (code, charts, and narrative together), and writing technical papers with Sphinx.

Example Screenshots
Know how to display an image in Markdown - you'll want this to highlight your charts and more.

VS Code While Working

Skills Demonstrated
GitHub repo with README.md
Git clone to machine.
Create Python module.
Create Python local virtual environment in .venv folder.
Manage external packages (e.g. for logging and read-out-loud)
Working with variables and functions.
Creating a standard Python module (ready for import or running as a script).
Git clone, add, commit, push, pull
Using a professional IDE (VS Code)