# ODTxKKU Workshop (2024-12-21)
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

### Never knew CMD
- check current remote origin: `git remote -v`
- check status of commit: `git status`
- check commits: `git log`
- unstage add files: `git rm --cached <files name>`
- un-commit : `git reset <options> HEAD~<number of commit >`
    - hard: unchange files
    - mixed(default): add stage
    - soft: before add stage
# 