# Unity és GitHub beállítása
Részletes leírás Unity projektek GitHub-ra való feltöltéséhez

## Lépések
1. 
2. 
3. 
4. 
https://unityatscale.com/unity-version-control-guide/how-to-setup-unity-project-on-github/#step-1---create-the-project

# 1. Empty Unity project
# 2. cd into project directory
# 3. $ git init
> check with \$ git status
# 4. $ curl https://raw.githubusercontent.com/github/gitignore/master/Unity.gitignore --output .gitignore
# 5. $ git add "filename" | . to stage all changes
> check with \$ git status
# 6. $ git commit -m "MESSAGE"
# 7. __Empty__ GitHub repo
# 8. Open Git Bash
# 9. $ ssh-keygen -t ed25519 -C "your_email@example.com"
> Use default directory, password optional. Password will be required on every push
# 10. $ eval "\$(ssh-agent -s)"
# 11. $ ssh-add ~/.ssh/id_ed25519
# 12. $ clip < ~/.ssh/id_ed25519.pub
# 13. Add key to GitHub account
# 14. $ git remote add origin <GITHUB_REPOSITORY_URL>
> in project directory
# 15. $ git push --set-upstream origin master

# MENTÉS: add, commit, push
# LETÖLTÉS: pull
