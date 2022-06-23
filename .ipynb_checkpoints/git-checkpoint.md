### Useful Git commands

#### To make a folder a Git directory:

```
git init
```

#### To undo `git init`

```
rm -rf .git
```

---
#### To update the .gitignore file:

1. Make change to the .gitignore file
2. Commit everything you've changed
3. Run `git rm -r --cached .`
4. Run `git add .`
5. Make a commit again

The .gitignore should work now!

---
#### To remove the last commit while keeping the changes

```
git reset HEAD^
```
---
#### To pull a specific file from the other branch

To pull "wanted-file" from "source-branch" to "target-branch", first make sure that "other-branch" is up to date locally by:

```
git checkout source-branch
git pull origin source-branch
```

Then checkout the target-branch, pull the wanted-file from the source-branch

```
git checkout target-branch
git checkout source-branch wanted-file   # git checkout <branch> <path>
```