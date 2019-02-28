# Common Git Command

## Quick Links

- [Sync Git Branch With Master](#Sync-Git-Branch-With-Master)

- [Merge Git Branch With Master](#Merge-Git-Branch-With-Master)

## Sync Git Branch With Master

- to sync somebranch with master

```
git checkout master
git pull
git checkout somebranch
git merge master
```

## Merge Git Branch With Master

- merge somebranch to master

```
git checkout master
git merge somebranch
git push origin master
```
