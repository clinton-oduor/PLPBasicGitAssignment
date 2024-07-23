# PLPBasicGitAssignment

# Navigate to your project directory
cd path/to/PLPBasicGitAssignment

# Initialize a new Git repository
git init

# Link to the GitHub repository
git remote add origin https://github.com/clinton-oduor/PLPBasicGitAssignment.git

# Create and add text to hello.txt
echo "Hello, Git!" > hello.txt

# Stage the new file
git add hello.txt

# Commit the changes
git commit -m "Add hello.txt with a greeting"

# Push the changes to GitHub
git push -u origin main
