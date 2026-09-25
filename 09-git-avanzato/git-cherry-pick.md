# git cherry-pick

## Cos'è
Applica in una branch le modifiche introdotte da un commit esistente.

## Sintassi
~~~bash
git cherry-pick <commit>
~~~

## Scenario
Una correzione urgente deve essere portata in una release branch.

## Conflitto
~~~bash
git status
git add .
git cherry-pick --continue
~~~

Per annullare:
~~~bash
git cherry-pick --abort
~~~

## Buone pratiche
Usalo con una motivazione chiara e documentabile.