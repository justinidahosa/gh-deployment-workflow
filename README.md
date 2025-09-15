## Project Goal
- Understand how GitHub Actions is used to perform a CI/CD pipeline
- Understand the difference between continuous integration and continuous deployment

## Project Structure
- README.md - description of project
- index.html - static website that will be deployed to GitHub Pages
- .github/workflows/deploy.yaml - GitHub Actions workflow

## How it works
- push changes to index.html to main branch
- GitHub Actions workflow notices the changes and prepares them to be deployed automatically (CI)
- index.html is deployed as a static website at https://justinidahosa.github.io/gh-deployment-workflow/ (CD)
