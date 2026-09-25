# git add

## Cos'è
Aggiunge contenuto alla staging area.

## A cosa serve
Seleziona ciò che entrerà nel prossimo commit.

## Sintassi
~~~bash
git add file.txt
git add .
git add -A
git add -p
~~~

## Esempio professionale
~~~bash
git add README.md
git diff --staged
~~~

## Errore comune
`git add .` può includere modifiche non desiderate. Controlla sempre il diff staged.

## Esercizio
Modifica due file e prepara per il commit solo uno.

## Soluzione
~~~bash
git add primo-file.txt
git diff --staged
~~~