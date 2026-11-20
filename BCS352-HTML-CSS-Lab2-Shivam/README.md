# HTML and CSS Introduction Lab — BCS352

**Student:** Shivam  
**Student ID:** BCS2025535  
**Roll No.:** 2510303488  
**Programme:** B.Tech CSE — Second Year  
**University:** Invertis University, Bareilly  
**Lab:** HTML and CSS Introduction Lab (BCS352)

This repository contains the completed source files for all **15 assignments (45 tasks)** listed in the supplied lab assignment sheet.

## Repository structure

```text
.
├── index.html
├── README.md
├── .gitignore
├── assets/
│   └── site.css
├── images/
│   └── instructor-image-placeholder.svg
├── assignments/
│   ├── 01-starting-a-git-repository/
│   ├── 02-pushing-and-cloning/
│   ├── 03-first-html-page/
│   ├── 04-divs-attributes-fix/
│   ├── 05-links-and-images/
│   ├── 06-html-lists/
│   ├── 07-about-me-page/
│   ├── 08-signup-forms/
│   ├── 09-html-tables/
│   ├── 10-css-fundamentals/
│   ├── 11-units-css-variables/
│   ├── 12-box-model-cards-scroll/
│   ├── 13-flexbox-layouts/
│   ├── 14-css-grid-layouts/
│   └── 15-responsive-pages/
└── git-workflow.md
```

Each assignment folder contains its working HTML/CSS files and a local README describing the tasks and expected output.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Git
- A code editor such as Visual Studio Code (recommended, not required)

No external libraries or build tools are required.

## Run the project

1. Download or clone this repository.
2. Open the folder in VS Code.
3. Open `index.html` in a browser, or start a local server from the repository root:

   ```bash
   python -m http.server 8000
   ```

4. Visit `http://localhost:8000`.
5. Open the HTML files inside each assignment folder to view the individual outputs.

## Assignment list

| No. | Assignment | Folder |
|---:|---|---|
| 1 | Starting a Git Repository | `01-starting-a-git-repository` |
| 2 | Pushing and Cloning a Repository | `02-pushing-and-cloning` |
| 3 | Your First HTML Page | `03-first-html-page` |
| 4 | Divs, Attributes and a Small Fix | `04-divs-attributes-fix` |
| 5 | Links and Images | `05-links-and-images` |
| 6 | Types of HTML Lists | `06-html-lists` |
| 7 | About Me Page | `07-about-me-page` |
| 8 | Sign-Up Forms and Choices | `08-signup-forms` |
| 9 | Tables with Headers and Footers | `09-html-tables` |
| 10 | CSS Fundamentals | `10-css-fundamentals` |
| 11 | Units and CSS Variables | `11-units-css-variables` |
| 12 | Box Model, Cards and Scrolling | `12-box-model-cards-scroll` |
| 13 | Flexbox Layouts | `13-flexbox-layouts` |
| 14 | CSS Grid Layouts | `14-css-grid-layouts` |
| 15 | Responsive Pages with Media Queries | `15-responsive-pages` |

## Publish to GitHub

### Option A — GitHub website (easiest)

1. Sign in to GitHub.
2. Select **New repository**.
3. Repository name: `BCS352-HTML-CSS-Lab`.
4. Choose Public or Private as required by your instructor.
5. Do not initialize it with another README because this project already contains one.
6. Create the repository.
7. In this project folder, open a terminal and run:

   ```bash
   git init
   git add .
   git commit -m "Complete BCS352 HTML and CSS lab assignments"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/BCS352-HTML-CSS-Lab.git
   git push -u origin main
   ```

8. Replace `YOUR-USERNAME` with your GitHub username and use the exact repository URL shown by GitHub.

### Configure your Git identity

Before your first commit, set your own name and email:

```bash
git config --global user.name "Shivam"
git config --global user.email "YOUR-EMAIL-OR-GITHUB-NOREPLY-EMAIL"
```

Use the email address associated with your GitHub account, or your GitHub-provided noreply address. Do not use the placeholder text literally.

### Option B — GitHub Desktop

1. Install and sign in to GitHub Desktop.
2. Choose **File → Add Local Repository** and select this project folder.
3. If prompted, create a repository in this folder.
4. Enter a commit summary such as `Complete BCS352 lab assignments`.
5. Select **Commit to main**, then **Publish repository**.
6. Choose the visibility required by your instructor.

## Important items to personalize before submission

- **Email address:** In `assignments/07-about-me-page/about-me.html`, replace `your-email@example.com` with your actual email address.
- **Instructor-provided images:** The assignment sheet says to use the image filename supplied by the instructor. No such image file was included with the PDF, so the image tasks currently use `images/instructor-image-placeholder.svg`. Replace this placeholder with the required image and update the `src` path in:
  - `assignments/05-links-and-images/portfolio-image.html`
  - `assignments/15-responsive-pages/responsive-image.html`
- **Git evidence:** Assignment 1 and 2 are accompanied by command guides. Run the commands on your own computer to produce your actual Git history, remote listing and clone output.
- **Screenshots:** The assignment PDF asks students to run their code and keep output evidence. The repository includes the runnable pages and written expected outputs, not fabricated screenshots. Capture screenshots from your browser after running the pages if your instructor requires them.

## Notes

This is a static HTML/CSS learning project. The sign-up form is a front-end demonstration; it does not have a server to store submitted data.
