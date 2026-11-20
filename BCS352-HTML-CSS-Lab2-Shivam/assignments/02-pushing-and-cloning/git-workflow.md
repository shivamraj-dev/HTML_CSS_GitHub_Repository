# Assignment 2 — Push and clone

These steps use a second local bare repository, as required by the assignment sheet.

```bash
# From inside the working repository folder:
git init --bare ../html-remote
git remote add origin ../html-remote
git remote -v
git branch --show-current
git push -u origin main
```

If your current branch is named `master`, use `git push -u origin master` instead.

```bash
# Move to the parent folder:
cd ..
git clone html-remote html-copy
cd html-copy
git log --oneline
```

For publishing this project to GitHub, follow the root README section **Publish to GitHub** instead of using the local bare remote.
