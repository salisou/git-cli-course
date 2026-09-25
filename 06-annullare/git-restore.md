# git restore

Ripristina file dal working tree o dallo staging.

```bash
git restore file.txt
git restore --staged file.txt
git restore --source HEAD~1 file.txt
```

Attenzione: il primo comando può eliminare modifiche locali non committate nel file indicato.
