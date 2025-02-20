Step 1: Setup Git & SSH Key
Open Git Bash and check if Git is installed: a. git --version
Configure Git (if not already configured): a. git config --global user.name "2302031000143" b. git config --global user.email "2302031000143@silveroakuni.ac.in"
Generate an SSH key: a. ssh-keygen -t ed25519 -C "2302031000143@silveroakuni.ac.in"
Copy the SSH key to the clipboard: a. cat ~/.ssh/id_ed25519.pub
Go to GitHub ? Settings ? SSH and GPG keys ? New SSH Key
Paste the key and click Add SSH Key. Step 2: Create & Clone Git Repository
Go to GitHub ? Create New Repository
Name it your enrollment number
Select Public/Private ? Create Repository
Clone using SSH: a. git clone https://github.com parthpatel7687/2302031000143git
Move into the repository: a. cd 2302031000143 Step 3: Create Required Folders & Add Assignments
Create two folders: a. mkdir Assignment_1 Assignment_2
Copy assignment files into respective folders.
Verify files: a. ls Step 4: Commit & Push to GitHub
Check Git status: a. git status
Add files to staging: a. git add .
Commit the changes: a. git commit -m "first commit"
Push to GitHub: a. git push origin main
