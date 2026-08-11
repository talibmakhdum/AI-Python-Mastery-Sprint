
# Day 0 Setup Notes

## Environment Setup

- Virtual environment is active: `(venv)`
- VS Code extensions to install:
  - Python
  - Pylance
  - Jupyter
  - GitLens
- Activate the virtual environment each day:

```
source venv/Scripts/activate

```

---

## Basic Terminal Commands

### Check current folder

```
pwd

```

### See files and folders

```
ls

```

### Move into a folder

```
cd Day-01

```

### Go back one folder

```
cd ..

```

### Create a folder

```
mkdir Day-01

```

### Run a Python file

```
python main.py

```

---

## Creating Files with CAT and EOF

`cat > filename << "EOF"` can be used to create a file and write text into it from the terminal.

Example:

```
cat > notes.md << "EOF"

# My Notes

Today I learned how to use the terminal.

