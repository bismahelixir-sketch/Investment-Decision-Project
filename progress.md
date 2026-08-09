# Progress Log

## Day 1

### Completed
- Created the main project folders
- Created README.md
- Created .gitignore
- Created requirements.txt
- Set up the basic project structure
- Set up virtual environment
- Installed required libraries
- Created GitHub repository
- Wrote initial README

### Learned
- What a README file is used for
- What .gitignore does
- Why a virtual environment is useful (.venv)

### What is `.gitignore`?

A `.gitignore` file tells Git which files or folders it should ignore and not upload to GitHub.

Think of it as a "Do Not Upload" list.

---

### Why do we need it?

Some files are automatically created by Python, VS Code, macOS, or other software.

These files are temporary or specific to my computer, so they don't need to be shared with anyone else.

Keeping them out of GitHub makes the project cleaner.

---

### Why do we ignore `.venv/`?

`.venv` contains my project's virtual environment.

It includes Python and all the installed libraries.

Every developer creates their own virtual environment, so uploading mine is unnecessary and can make the repository very large.

Instead, I upload `requirements.txt`, which lists all the libraries needed to recreate the environment.

---

### Why ignore `__pycache__/`?

Python automatically creates this folder to make programs run a little faster.

These files are temporary and can always be recreated.

---

### Why ignore `*.pyc`?

These are compiled Python files that Python generates automatically.

They are not part of my actual code and don't need to be uploaded.

---

### Why ignore `.ipynb_checkpoints/`?

Jupyter Notebook automatically creates backup files while I'm working.

These are only for recovery and shouldn't be part of the project.

---

### Why ignore `.DS_Store`?

This is a macOS system file that stores Finder settings like icon positions and folder views.

It has nothing to do with my project.

---

### Important takeaway

GitHub should only contain files that someone else needs to run or understand my project.

Everything that can be recreated automatically should usually be ignored.

Git
- Tracks changes in my project.
- Lets me save checkpoints using commits.

GitHub
- Stores my Git project online.
- Makes it easy to share my work.

Commit
- A snapshot of my project at a specific point in time.

README
- The front page of my project.

.gitignore
- Tells Git which files not to upload.
