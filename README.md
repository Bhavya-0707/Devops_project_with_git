INITIALIZE REPOSITORY AND PUSH INTO GITHUB:-       
# Create project folder
mkdir devops-project && cd devops-project

# Initialize git repo
git init

# Create README.md
echo "# DevOps Project" > README.md

# Create initial commit
git add .
git commit -m "Initial commit: project setup with README"

# Add remote GitHub repo (replace with your repo URL)
git remote add origin https://github.com/Bhavya-0707/Devops_project_with_git/tree/master

# Push to GitHub
git branch -M main
git push -u origin main

MAIN USES OF .gitignore

Avoid committing unnecessary files

Example: log files, temporary build files, OS-generated files (.DS_Store, Thumbs.db).

Keep repo clean and lightweight

Prevents large or auto-generated files (like node_modules, compiled binaries, dist/) from bloating the repository.

Improve security

Helps avoid accidentally pushing sensitive files like .env (with passwords, API keys) to GitHub.

Consistency across team

Everyone working on the repo ignores the same unnecessary files.
