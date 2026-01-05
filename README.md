# Cloud Resume Platform

🚀 A modern, CI/CD-enabled resume platform built with Jekyll and GitHub Actions.

## Live Site
[View Resume](https://s1xte3n.github.io/cloud-resume-platform/)

## Features
- Markdown-based content management
- Automated CI/CD pipeline
- Security scanning with CodeQL
- Dependency management with Dependabot
- Browser-based development with Codespaces

## Development

### Local Setup
```bash
bundle install
bundle exec jekyll serve
```

### Using Codespaces
Click the "Code" button → "Create codespace on main"

## Workflow
1. Create feature branch
2. Make changes to resume content
3. Open pull request
4. CI validates changes automatically
5. Merge to deploy to production

## Project Structure
- `_data/resume.yml` - Resume content
- `_layouts/` - Page templates
- `.github/workflows/` - CI/CD pipelines
- `.devcontainer/` - Codespaces configuration