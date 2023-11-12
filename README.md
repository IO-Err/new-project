# DevOps Course by Denys Vasyliev & GlobalLogic
mkdir new-project && cd new-project
git init
git remote add origin git@github.com:IO-Err/new-project.git
nano README.md
git add README.md
git commit -m "init"
git push origin main
git checkout -b development
nano README.md
git add README.md
git commit -m "add instruction"
git push origin development
git checkout main
git merge development main
git push origin main
