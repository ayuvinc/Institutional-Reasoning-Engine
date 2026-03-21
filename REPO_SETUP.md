# Repository Setup and Publishing

## Local setup

```bash
git init
git add .
git commit -m "Initial commit: IRE v1.1 docs, whitepaper, and pages site"
```

## Create remote and push

Option A: existing GitHub repo

```bash
git remote add origin <YOUR_GITHUB_REPO_URL>
git branch -M main
git push -u origin main
```

Option B: create with GitHub CLI

```bash
gh repo create institutional-reasoning-engine --public --source=. --remote=origin --push
```

## Enable GitHub Pages

In GitHub repo settings:
- Pages → Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/docs`

Public URL will be:
`https://<github-username>.github.io/<repo-name>/`

Landing page file:
- `docs/index.html`

Builder guide file:
- `docs/ire-builder-guide.html`

Downloads:
- `docs/downloads/IRE_v1.1_Final.pdf`
- `docs/downloads/IRE_v1.1_Final.docx`
