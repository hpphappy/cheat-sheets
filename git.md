### Useful Git commands

#### To make a folder a Git directory:

```
git init
```

#### Undo `git init`

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
#### Remove the last commit while keeping the changes

```
git reset HEAD^
```