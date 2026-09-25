# git fetch

## Cos'è
Scarica aggiornamenti dal remote senza integrarli automaticamente nella branch corrente.

## Sintassi
~~~bash
git fetch origin
git fetch --all --prune
~~~

## Esempio
~~~bash
git fetch origin --prune
git log --oneline --graph --all
~~~

## Perché usarlo
Aggiorna la conoscenza locale del remote prima di decidere come integrare le modifiche.