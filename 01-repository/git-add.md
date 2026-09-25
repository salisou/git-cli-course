# git add

## Cos'è
Inserisce snapshot delle modifiche nella staging area.

## Sintassi
```bash
git add file.txt
git add directory/
git add .
```

## Esempio
```bash
git status
git add README.md
git status
```

## Punto fondamentale
`git add` non crea un commit: prepara il contenuto che entrerà nel prossimo commit.

## Errore comune
Usare sempre `git add .` senza controllare cosa si sta mettendo in staging.

## Esercizio
Modifica due file, aggiungine solo uno e verifica lo stato.
