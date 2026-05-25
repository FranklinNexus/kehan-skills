# Publish Checklist

Suggested repository name: `kehan-skills`

Suggested description:

```text
Portable Kehan-inspired founder coaching skill package for Cursor, Claude Code, Antigravity, and AGENTS.md-compatible agents.
```

## Before Creating The Remote

Run:

```powershell
python .\scripts\validate.py
git status --short
```

Expected result:

- Validation passes.
- `git status --short` is empty.

## Create The GitHub Repository

Create an empty GitHub repository named `kehan-skills`.

Do not initialize it with a README, license, or `.gitignore`; this repository already contains those files where needed.

## Push

Use HTTPS:

```powershell
git remote add origin https://github.com/<your-github-user>/kehan-skills.git
git branch -M main
git push -u origin main
```

Or use SSH:

```powershell
git remote add origin git@github.com:<your-github-user>/kehan-skills.git
git branch -M main
git push -u origin main
```

## After Push

Open the GitHub repository page and confirm these paths are visible:

- `skills/kehan/SKILL.md`
- `skills/kehan/PLAYBOOK.md`
- `.agents/skills/kehan.md`
- `scripts/install.ps1`
- `scripts/validate.py`
