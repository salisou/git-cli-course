# git restore

## Cos'è
Ripristina file nel working tree oppure rimuove contenuto dalla staging area.

## Sintassi
~~~bash
git restore file.txt
git restore --staged file.txt
git restore --source=HEAD -- file.txt
~~~

## Esempio
Per togliere un file dallo staging mantenendo la modifica:
~~~bash
git restore --staged file.txt
~~~

## Attenzione
`git restore file.txt` può eliminare modifiche locali. Controlla prima `git diff`.