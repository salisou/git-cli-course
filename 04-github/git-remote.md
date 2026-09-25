# git remote

## Cos'è
Gestisce i collegamenti tra repository locale e remoti.

## Sintassi
```bash
git remote -v
git remote add origin <URL>
git remote set-url origin <URL>
git remote remove origin
```

## Esempio
```bash
git remote add origin https://github.com/utente/progetto.git
git remote -v
```

## Errore comune
**remote origin already exists**: controlla con git remote -v e usa set-url se l'URL deve essere modificato.
