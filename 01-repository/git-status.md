# git status

## Cos'è
Mostra lo stato del working tree e della staging area.

## Modello mentale
~~~text
working tree -> staging area -> commit
~~~

## Sintassi
~~~bash
git status
git status --short
git status --branch
~~~

## Esempio
~~~bash
echo "# Progetto" > README.md
git status
git add README.md
git status
~~~

## Esercizio
Crea due file, modifica uno e aggiungi l'altro allo staging. Interpreta `git status --short`.

## Buone pratiche
Esegui `git status` prima di operazioni importanti.