[200~# Day 0 Setup Notes

## Environment Setup

* Virtual environment is active: `(venv)`

* VS Code extensions to install:

  * Python
  * Pylance
  * Jupyter
  * GitLens

* Activate the virtual environment each day:

```bash
source venv/Scripts/activate
```

---

## Basic Terminal Commands

### Check current folder

```bash
pwd
```

### See files and folders

```bash
ls
```

### Move into a folder

```bash
cd Day-01
```

### Go back one folder

```bash
cd ..
```

### Create a folder

```bash
mkdir Day-01
```

### Run a Python file

```bash
python main.py
```

---

## Creating Files with CAT and EOF

`cat > filename << "EOF"` can be used to create a file and write text into it from the terminal.

Example:

```bash
cat > notes.md << "EOF"

# My Notes

Today I learned how to use the terminal.

