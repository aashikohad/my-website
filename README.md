# CI/CD Enabled Static Website

This project is a simple static HTML website deployed using GitHub Pages with an automated CI/CD pipeline powered by GitHub Actions.

The objective of this project was to understand modern deployment practices where updates made to the code are automatically reflected on a live website without requiring any manual deployment process.

---

## Live Website

The website is available at:

https://aashikohad.github.io/my-website/

---

## Tech Stack

- HTML
- GitHub
- GitHub Actions
- GitHub Pages

---

## CI/CD Workflow

This project uses a Continuous Integration and Continuous Deployment pipeline.

Whenever a change is made to the code and pushed to the repository:

1. GitHub Actions automatically triggers the deployment workflow.
2. The updated website is processed.
3. The changes are deployed to GitHub Pages.
4. The live website updates shortly after.

In simple terms:

Code Change → Push → Automated Deployment → Live Update

---

## Project Structure

my-website/
│
├── index.html
└── .github/
    └── workflows/
        └── static.yml

---

## Key Feature

The deployment process is fully automated.  
Any change made in the codebase is automatically reflected on the live website through the CI/CD pipeline.

---

## Learning Outcome

Through this project, I gained practical understanding of:

- Continuous Integration
- Continuous Deployment
- GitHub Actions workflow
- Automated website deployment
- Live publishing using GitHub Pages

---

## Author

Aashi Kohad
