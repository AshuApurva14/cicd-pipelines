# CI/CD Pipelines

This repo contains pipeline definitions for GitHub Actions and Jenkins.

## ⚙️ GitHub Actions
- `github-actions/build.yml` → Build & test code
- `github-actions/deploy.yml` → Deploy to cloud/k8s

## 🧩 Jenkins
- `jenkins/Jenkinsfile` → Declarative pipeline with stages:
  - Build
  - Test
  - Deploy

## 🚀 Usage
1. Copy workflow/pipeline into your project.
2. Update environment variables/secrets.
3. Run pipelines via GitHub Actions or Jenkins.

