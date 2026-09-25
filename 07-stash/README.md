# Git Stash

## A cosa serve
Mettere temporaneamente da parte modifiche non committate.

## Comandi
~~~bash
git stash push -m "lavoro temporaneo"
git stash list
git stash show -p
git stash pop
git stash apply
git stash drop
~~~

## Scenario
~~~bash
git stash push -m "feature login in corso"
git switch main
git pull --ff-only
git switch feature/login
git stash pop
~~~

## Buona pratica
Non usare lo stash come archivio permanente. Per lavoro importante è spesso più tracciabile un commit su una branch privata.