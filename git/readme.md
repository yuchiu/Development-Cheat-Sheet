# Git

## Quick Links

- [Sync Git Branch With Master](#Sync-Git-Branch-With-Master)

- [Merge Git Branch With Master](#Merge-Git-Branch-With-Master)

- [Remove Git Commit Locally](#Remove-Git-Commit-Locally)

- [Remove Git Commit on Github](#Remove-Git-Commit-on-Github)

## Sync Git Branch With Master

- to sync somebranch with master

```
git checkout master
git pull
git checkout somebranch
git merge master
```

- [reference](https://stackoverflow.com/questions/16329776/how-to-keep-a-git-branch-in-sync-with-master)

## Merge Git Branch With Master

- merge somebranch to master

```
git checkout master
git merge somebranch
git push origin master
```

- [reference](https://stackoverflow.com/questions/16329776/how-to-keep-a-git-branch-in-sync-with-master)

## Remove Git Commit Locally

- This will "pop" the current head commit

```
git reset --soft HEAD^
```

- [reference](https://stackoverflow.com/questions/448919/how-can-i-remove-a-commit-on-github)

## Remove Git Commit on Github

- This will "undo" the push on github

```
git push -f origin HEAD^:master
```

- [reference](https://stackoverflow.com/questions/448919/how-can-i-remove-a-commit-on-github)
