# Assignment 1 — Git workflow

Run these commands from the repository root. The email below is a placeholder: replace it with your own Git commit email before committing.

```bash
git init
git config --local user.name "Shivam"
git config --local user.email "YOUR_GITHUB_NOREPLY_OR_EMAIL"
git config user.name
git config user.email
```

To demonstrate the two commits in order, first copy the one-heading version over `index.html`:

```bash
cp assignments/01-starting-a-git-repository/index-step-1.html assignments/01-starting-a-git-repository/index.html
git status
git add assignments/01-starting-a-git-repository/index.html
git commit -m "Add home page"
```

Now use the completed `index.html` version (it contains the second h2 heading), stage it and commit:

```bash
git add assignments/01-starting-a-git-repository/index.html
git commit -m "Add next meeting heading"
git log --oneline
```

On Windows PowerShell, use `Copy-Item` instead of `cp` if needed.
