# GIT-branch-cheatsheet

```bash
# new branch
git branch <new-branch-name>
git branch <new-branch-name> 89a2faad
```

```bash
# rename

git branch -m <new-name>
git branch -m <old-name> <new-name>
```

```bash
# delete remote branch
git push origin --delete <old-name>
# delete local branch
git branch -d <branch-name>
```

```bash
# switch branch
git checkout <other-branch>
# or
git switch <other-branch>
```

```bash
# compare branches
git log branch-A..branch-B
git diff branch-A..branch-B
```
