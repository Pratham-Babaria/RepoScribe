# RepoScribe

**GitHub Repo to Doc Converter** is a lightweight Python script that clones a GitHub repository and compiles all source code files (e.g., `.py`, `.html`, `.js`, `.css`, etc.) into a single `.docx` document. It's perfect for reviewing, archiving, printing, or sharing codebases in a clean, readable format.

---

## ⚙️ Requirements

- Python 3.X
- `git` installed and available in your system PATH
- Python packages: pip install gitpython python-docx

## 🚀 How to Use

1. **Download or clone this repository**: git clone https://github.com/Pratham-Babaria/RepoScribe.git
2. **CD into the correct folder**: cd RepoScribe
3. **Run the Script**: python github_repo_to_doc.py
4. **Enter the GitHub repository URL** when prompted:
5. The script will:
- Clone the GitHub repo into a temporary folder
- Collect all code files with common extensions
- Skip non-relevant folders like `node_modules/`, `.git/`, `venv/`, etc.
- Compile all code into a single `output.docx` file
- Automatically open the document after generation

---

## 📁 Output

The final `.docx` file will be saved
in the same directory as the script.

---

## 🔐 Private Repositories

To use with private repositories, modify the GitHub URL like this: https://<your-personal-access-token>@github.com/username/private-repo.git

Or use SSH if you’ve configured your GitHub SSH key.


---

## ✅ License

MIT License. Feel free to use, modify, and contribute.

---

## 📌 Author

Created by Pratham Babaria — feel free to connect or contribute!










