## Instructions: How to create a node backend

### Create project
1. create a folder in local system give project name to the folder
2. npm init

### Create git repo
3. create .gitignore file and go to gitignore generator in google and paste the generated code
4. create a git repository with project name
5. follow the instructions for git
    1. echo "# video-app-backend" >> README.md
    2. git init
    3. git add README.md
    4. git commit -m "first commit"
    5. git branch -M main
    6. git remote add origin https://github.com/arupsaha07/video-app-backend.git
    7. git push -u origin main

### Project folder structure
6. create "src" folder
7. add 3 files to the folder "app.js", "constants.js" and "index.js"
8. create more folders inside /src called "controllers", "db", "middlewares", "models", "routes" and "utils"

### Package install
9. Install nodemon and prettier in dev dependency e.g. (npm i -D nodemon)
10. Create 2 files ".prettierrc" and ".prettierignore"