# git status

## Cos'è
Mostra lo stato del working tree e della staging area.

## Perché usarlo
È il comando di controllo più importante prima e dopo una modifica.

## Sintassi
`git status`

## Esempio
```bash
git status
git add README.md
git status
git commit -m "docs: add README"
git status
```

## Errori comuni
Ignorare file non tracciati oppure confondere "Changes not staged" con "Changes to be committed".

## Esercizio
Modifica un file e osserva come cambia lo stato prima e dopo `git add`.
