# git bisect

## Cos'è
Usa una ricerca binaria per individuare il commit che ha introdotto un problema.

## Procedura
~~~bash
git bisect start
git bisect bad
git bisect good <commit-funzionante>
# esegui il test
git bisect good
# oppure git bisect bad
git bisect reset
~~~

## Automazione
Con un test affidabile è possibile usare `git bisect run`.

## Esercizio
Crea una storia con più commit e individua quello che introduce un bug.