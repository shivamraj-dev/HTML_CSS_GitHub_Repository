# Git command reference for this lab

## First-time setup

```bash
git config --global user.name "Shivam"
git config --global user.email "YOUR-EMAIL-OR-GITHUB-NOREPLY-EMAIL"
git init
git status
git add .
git commit -m "Complete BCS352 HTML and CSS lab assignments"
git branch -M main
```

## Connect and push to GitHub

```bash
git remote add origin https://github.com/YOUR-USERNAME/BCS352-HTML-CSS-Lab.git
git remote -v
git push -u origin main
```

## Later updates

```bash
git add .
git commit -m "Update lab assignment files"
git push
```

## Clone

```bash
git clone https://github.com/YOUR-USERNAME/BCS352-HTML-CSS-Lab.git
cd BCS352-HTML-CSS-Lab
```

Replace placeholders with your own GitHub username and commit email. Do not share passwords or personal access tokens in source files.
