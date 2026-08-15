### Day 00: Technical Setup & Terminal Workflows

### 1. Virtual Environments (venv)

* **Concept:** Isolate project dependencies to avoid system-wide software conflicts.
* **Windows (Git Bash):** Run source venv/Scripts/activate.
* **Mac / Linux:** Run source venv/bin/activate.
* **Visual Cue:** Terminal prompt prepends (venv) when active.
* **Exit:** Run deactivate to close the environment.

### 2. Terminal Navigation & Daily Routine

* pwd: Print working directory to check your location.
* ls -la: List files, including hidden system files (-a).
* cd FolderName: Change directory downward into a specific folder.
* cd ..: Move upward exactly one folder level.
* mkdir Name: Create a brand new directory.
* **Daily Flow:** Open terminal -> Navigate to repository root -> Activate venv -> Create and enter today's folder -> Confirm with pwd.

### 3. Terminal File Creation Methods

* **touch file.py:** Creates an empty file placeholder. Best for structuring folders early.
* **echo 'text' > file:** Writes text to a file. Overwrites existing contents completely.
* **echo 'text' >> file:** Appends text safely to the bottom of the file.
* **cat > file << "EOF":** Starts multi-line terminal writing. Terminate the input by typing EOF.
* **nano file:** Mini terminal-based text editor. Save and exit using Ctrl+X -> Y -> Enter.

### 4. Automation & Git Version Control

* **Step 1:** Run git status to see uncommitted workspace modifications.
* **Step 2:** Run git add Day-XX-Name/ to stage specific folders only.
* **Step 3:** Run git commit -m "Day X: Topics - Deliverable" for deployment snapshots.
* **Step 4:** Run git push origin main to synchronize local code with GitHub.

### 5. Core Reference Libraries

* **Python Basics:** Python Tutor (code visualization) and Official Python Documentation.
* **Data Science:** NumPy Documentation and Pandas Documentation.
* **Machine Learning:** Scikit-learn Ecosystem and Hugging Face Hub.
* **Interactive Code Workspaces:** Google Colab (Free GPUs) and Kaggle (Data hosting).
