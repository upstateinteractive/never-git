# Git Commands

## Basics 
### Make Changes
```bash
git add .
git commit -m "the commit"
```

### Get Updates
```bash
git pull
```

### Send Updates
```
git push
```

## Branching

### Switch Branch
```bash
git checkout master
```

### List Branches on Local Computer
```
git branch
```

### List Branches on Local Computer and on Github
```
git branch -a 
```

## Other
### Open VS Code
```bash
code .
```

### Git Flow for new branching
```
git checkout master
git pull
git checkout -b <NEW_BRANCH>
# make your changes in VS CODE
git add .
git commit -m "<MESSAGE>"
git push
# git will prompt you to push to upstream. copy/paste.
# open github and create a pull request
```

### Pro Tips
1. Do **NOT** merge your own pull request

fifth branch
