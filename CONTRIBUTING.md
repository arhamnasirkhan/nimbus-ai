# Contributing

## Branches
- `main` – always demo-ready. Protected, merge via PR only.
- `develop` – integration branch. Feature branches merge here.
- `feature/<short-name>`, `fix/<short-name>`, `docs/<short-name>` – your work.

## Flow
1. `git checkout develop && git pull`
2. `git checkout -b feature/my-thing`
3. Commit small, push, open a PR into `develop`.
4. One teammate reviews, then squash-merge.
5. Before submission, PR `develop` → `main`.

## Commit messages
`type: short summary` — types: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`.

## Secrets
Never commit API keys. Put them in `.env` (git-ignored) and document the name in `.env.example`.
