# git rm e git mv

## git rm
Rimuove un file dal working tree e prepara la rimozione per il commit.

```bash
git rm vecchio.txt
git commit -m "chore: remove obsolete file"
```

## git mv
Rinomina/sposta un file mantenendo l'operazione sotto controllo di Git.

```bash
git mv appunti.md docs/appunti.md
git commit -m "docs: move notes"
```

## Attenzione
Non usare questi comandi per cancellare dati senza aver prima verificato lo stato.
