# git merge

## Cos'è
Integra nella branch corrente la storia di un'altra branch.

## Sintassi
~~~bash
git switch main
git merge feature/login
~~~

## Merge esplicito
~~~bash
git merge --no-ff feature/login
~~~

## Conflitto
~~~bash
git status
git add <file>
git commit
~~~

## Annullamento
~~~bash
git merge --abort
~~~

## Esercizio
Crea due branch con modifiche indipendenti e integrale.