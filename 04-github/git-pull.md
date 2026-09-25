# git pull

Recupera aggiornamenti dal remoto e li integra nel branch corrente.

```bash
git pull
git pull origin main
git pull --ff-only
```

Metodo prudente: git status → git fetch origin → git log HEAD..origin/main --oneline → git pull --ff-only.
