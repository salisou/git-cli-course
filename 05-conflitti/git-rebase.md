# git rebase

Ricostruisce i commit di una branch sopra una nuova base.

```bash
git switch feature/login
git rebase main
```

Evita il rebase di commit pubblici condivisi da altri sviluppatori. In caso di conflitto: risolvi → git add → git rebase --continue. Per annullare: git rebase --abort.
