#Phase 1: Configure Git
Step 1. Initialize the repository

git init
Step 2. Configure your name

git config --global user.name "Nupur Patil"
Step 3. Configure your email

git config --global user.email "nups2319@gmail.com"
Phase 2: Version 1.0 — Basic Shopping Page
Step 4. Check the current status

git status
Step 5. Add the HTML file to the staging area

git add index.html
Step 6. Commit Version 1.0

git commit -m "Version 1.0: Basic E-Shopping Page"
Phase 3: Version 2.0 — Styling and Cart Feature
First, update index.html in VS Code and save it using Ctrl + S.

Step 7. Check modified files

git status
Step 8. Stage the updated file

git add index.html
Step 9. Commit Version 2.0

git commit -m "Version 2.0: Add Styling and Cart Feature"
Step 10. Display the commit history

git log --oneline
Expected output: two commit entries, one for Version 2.0 and one for Version 1.0.

Phase 4: Push to GitHub
First, create a public repository named ESW-Git-Demo on GitHub, leaving the README option unchecked.

Step 11. Rename the branch to main

git branch -M main
Step 12. Connect the local repository to GitHub

Replace the URL with your actual GitHub repository URL.

git remote add origin https://github.com/YOUR-USERNAME/ESW-Git-Demo.git
Step 13. Push the commits to GitHub

git push -u origin main
Phase 5: Final verification
Step 14. Check the repository status

git status
Step 15. Verify the two commits again

git log --oneline
