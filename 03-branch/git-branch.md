# git branch

## Cos'è
Gestisce i riferimenti ai branch.

## Sintassi
~~~bash
git branch
git branch feature/login
git branch -d feature/login
git branch -D feature/login
git branch -vv
~~~

## Esempio
~~~bash
git branch feature/dashboard
git switch feature/dashboard
~~~

## Esercizio
Crea due branch e visualizzale con `git branch -vv`.

## Attenzione
`-D` forza l'eliminazione di un branch anche quando la sua storia non è stata integrata.