### Useful Git commands

To make a folder a Git directory:

```
git init
```

Undo <mark >git init</mark>

```
rm -rf .git
```

---
To update the .gitignore file:

1. Make change to the .gitignore file
2. Commit everything you've changed
3. Run <mark >git rm -r --cached .</mark>
4. Run <mark >git add .</mark>
5. Make a commit again

The .gitignore should work now!

---
