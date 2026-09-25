# 03 — Branch

Un branch è un riferimento mobile a un commit. I branch permettono di sviluppare funzionalità isolate senza destabilizzare direttamente `main`.

Workflow base:
```bash
git switch -c feature/login
# lavoro
git add .
git commit -m "feat: add login"
git switch main
git merge feature/login
```
