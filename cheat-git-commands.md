Configure Git for use

git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"
git config --global credential.https://github.com.username <username>
git config --global credential.https://github.com.token <token>

Local Project to Online Repo

// Project progress on local Git
git init -b main
git add .
git commit -m "First commit"

// Pushing local Git to Online Repo
git remote add origin <URL>
git remote -v
git push origin main


