# ODTxKKU Workshop (2024-12-21) by The13OS5
## Git command line 

### Benefits
- version control
- collaboration

### Workflow
- create directory and create some file
- `git init`
- `git remote add origin <git_repository_url>`
- `git add <. or files name>`
- `git commit -m <commit message>` add commit to local repository
- `git push <-u : remember branch name> <remote name> <branch name>`

### Never knew CMD
- check current remote origin: `git remote -v`
- check status of commit: `git status`
- check commits: `git log`
- check branch: `git branch`
    - create: `<branch name>`
- change branch: `git checkout`
- switch branch: `git switch`
- fetch: `git fetch`
- unstage add files: `git rm --cached <files name>`
- un-commit : `git reset <options> HEAD~<number of commit >`
    - hard: unchange files
    - mixed(default): add stage
    - soft: before add stage
- go to commit: `git checkout <commit hash | id>`
- view change: `git diff <--cached> <file name>`

### When conflicts
- Use stash (stack): `git stash` and `git stash pop`