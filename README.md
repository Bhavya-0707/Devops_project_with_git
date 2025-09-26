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
