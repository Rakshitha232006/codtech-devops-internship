# Task 2 – CI/CD Pipeline Setup

## Objective

The objective of this task is to design and implement a Continuous Integration and Continuous Deployment (CI/CD) pipeline that automatically deploys a web application whenever changes are pushed to the GitHub repository.

This task demonstrates how automation can be used to reduce manual deployment effort and ensure faster and more reliable software delivery.

---

## Overview of CI/CD

- **Continuous Integration (CI):** Automatically checks and integrates code changes when they are pushed to the repository.
- **Continuous Deployment (CD):** Automatically deploys the updated application after successful integration.

In this task, both CI and CD are implemented using GitHub Actions.

---

## Application Description

A simple static web application was created using HTML.  
The application serves as a demonstration project for automated deployment.

- File name: `index.html`
- Type: Static HTML webpage
- Hosting platform: GitHub Pages

---

## Tools and Technologies Used

- **Git** – Version control system
- **GitHub** – Source code hosting
- **GitHub Actions** – CI/CD automation tool
- **GitHub Pages** – Hosting platform for static websites
- **HTML** – Web application content

---

## CI/CD Pipeline Configuration

The CI/CD pipeline is configured using a YAML workflow file placed in the following location:

# .github/workflows/

The pipeline is triggered automatically when:

- Code is pushed to the `main` branch
- The `index.html` file is updated

### Pipeline Workflow Steps

1. The pipeline is triggered by a push event.
2. The repository code is checked out.
3. GitHub Actions deploys the static website.
4. The application is published automatically to GitHub Pages.

---

## Deployment Process

- GitHub Pages is configured to deploy using GitHub Actions.
- The `index.html` file is served as the root page.
- Every new commit updates the live website automatically without manual intervention.

Live Deployment URL:

The pipeline is triggered automatically when:

- Code is pushed to the `main` branch
- The `index.html` file is updated

### Pipeline Workflow Steps

1. The pipeline is triggered by a push event.
2. The repository code is checked out.
3. GitHub Actions deploys the static website.
4. The application is published automatically to GitHub Pages.

---

## Deployment Process

- GitHub Pages is configured to deploy using GitHub Actions.
- The `index.html` file is served as the root page.
- Every new commit updates the live website automatically without manual intervention.

Live Deployment URL:

The pipeline is triggered automatically when:

- Code is pushed to the `main` branch
- The `index.html` file is updated

### Pipeline Workflow Steps

1. The pipeline is triggered by a push event.
2. The repository code is checked out.
3. GitHub Actions deploys the static website.
4. The application is published automatically to GitHub Pages.

---

## Deployment Process

- GitHub Pages is configured to deploy using GitHub Actions.
- The `index.html` file is served as the root page.
- Every new commit updates the live website automatically without manual intervention.

Live Deployment URL:
https://rakshitha232006.github.io/codtech-devops-internship/

---

## Testing the Pipeline

To test the CI/CD pipeline:

1. The content of `index.html` was modified.
2. The changes were committed and pushed to the main branch.
3. GitHub Actions executed the workflow automatically.
4. The updated content appeared on the live website.

This confirms that the CI/CD pipeline is functioning correctly.

---

## Outcome

- Successfully implemented a CI/CD pipeline using GitHub Actions.
- Automated deployment achieved using GitHub Pages.
- Manual deployment steps eliminated.
- The pipeline ensures fast, reliable, and consistent deployment.

---

## Conclusion

This task demonstrates a practical implementation of CI/CD principles using modern DevOps tools. Automating the deployment process improves efficiency, reduces human error, and follows industry best practices.

The task fulfills all the requirements of CI/CD pipeline setup as part of the CODTECH DevOps Internship.
