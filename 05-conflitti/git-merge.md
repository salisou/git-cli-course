# git merge

Integra nella branch corrente la storia di un'altra branch.

```bash
git switch main
git merge feature/login
```

Con conflitto: git status → risolvi i file → git add . → git commit.

Per annullare un merge in corso: git merge --abort.
