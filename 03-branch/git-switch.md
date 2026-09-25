# git switch

## Cos'è
Comando dedicato alla gestione del cambio branch.

## Sintassi
~~~bash
git switch main
git switch -c feature/login
~~~

## Workflow professionale
~~~bash
git switch main
git pull --ff-only
git switch -c feature/login
~~~

## Errori comuni
Git può impedire il cambio se modifiche locali verrebbero sovrascritte.

## Esercizio
Crea `feature/report`, passa al branch e verifica con `git status`.