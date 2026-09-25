# git pull

## Cos'è
Recupera modifiche remote e le integra nella branch corrente.

## Sintassi
~~~bash
git pull
git pull --rebase
git pull --ff-only
~~~

## Workflow prudente
~~~bash
git status
git fetch origin
git pull --ff-only
~~~

## Errori comuni
Una divergenza può richiedere merge o rebase. In un'operazione interrotta usa `git merge --abort` oppure `git rebase --abort`.