# Go to your project directory
cd path"C:\Users\iniya\Desktop\Projects\project 2\pp.pbix"

# Initialize git (if not already a git repo)
git init

# Add your GitHub repository as a remote (copy the repo URL from GitHub)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git

# Add all files for commit
git add .

# Commit your files
git commit -m "Initial commit"

# Push your project to GitHub
git branch -M main
git push -u origin main
