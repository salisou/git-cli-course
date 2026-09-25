# git diff

## Cos'è
Confronta versioni del contenuto.

## Sintassi
~~~bash
git diff
git diff --staged
git diff HEAD
git diff branchA..branchB
~~~

## Concetto
`git diff` confronta working tree e index. `git diff --staged` confronta index e HEAD.

## Esercizio
Modifica un file, osserva `git diff`, fai staging e osserva `git diff --staged`.

## Buone pratiche
Controlla il diff prima di ogni commit.