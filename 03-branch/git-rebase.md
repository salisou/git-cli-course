# git rebase

## Cos'è
Riapplica i commit di una branch sopra una nuova base.

## Sintassi
~~~bash
git switch feature/login
git fetch origin
git rebase origin/main
~~~

## Conflitto
~~~bash
git status
git add <file>
git rebase --continue
~~~

Per annullare:
~~~bash
git rebase --abort
~~~

## Attenzione
Il rebase riscrive la storia della branch interessata. Evita di riscrivere commit già condivisi senza coordinamento.