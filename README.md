Jira Ticket:


Task Title: Set up new Git repository and create development branch for 'new-project'


Task Description:


As a developer, I need a new GitHub repository for 'new-project' and i need a development branch so that I can work on new features without affecting the main branch. 

Readme file should contain step-by-step instructions on how we can do it ourselves.


Expected Results:


A new branch called "development" is created and the user is able to switch to it successfully.

A new file called "README.md" is created and step-by-step instructions is added to it successfully.

The changes to the "development" branch are committed with a commit message successfully.

The changes from the "development" branch are merged into the "main" branch successfully.



Definition of Done (DoD):


Link to new-project Readme file


Instruction:

1. Mkdir new-project
2. cd new-project
3. git init
4. vi README.md
5. git add README.md
6. git commit -m "init"
7. git branch development
8. git checkout development
9. git README.md
10. git commit -am "updated README.md"
11. git checkout main
12. git merge development
13. git status
14. Vi README.md
15. git commit -am "Merged development"
