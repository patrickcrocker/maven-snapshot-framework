# Snapshot branch

This `version` branch is used to store the current Maven `snapshot` timestamp.

How this branch was setup:
```
git checkout --orphan snapshot
git rm --cached -r .
rm -rf *
rm .gitignore .gitmodules
touch README.md
git add .
git commit -m "new branch"
git push origin snapshot
```
