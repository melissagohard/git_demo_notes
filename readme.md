Git Demo

# Commands

```
git init
git status
git add <file>
git add -A
git commit -m "message"
git log
git remote add origin <url>
git branch
git checkout -b <branch_name>
git merge <branch_name>
```

## First Time Setup Process

1. Create a repository on GitHub
    - ``` git init```

2. Create and add an ignore file
    - ``` touch .gitignore```
    - ``` git add .gitignore```

3. Commit the changes
    - ``` git commit -m "Initial commit"```

4. Add the remote repository
    - ``` git remote add origin <url>```

5. Push the changes to the remote repository
    - ``` git push origin <branch_name>```

Continuing to use Git Notes
1. ``` git add -A```
2. ``` git commit -m "message"```
3. ``` git tag -a <tag_name> -m "message"```
4. ``` git merge <branch_name>```
5. ``` git push origin <branch_name>```
6. ``` git push origin <branch_name> --tags```