# Gestione dei conflitti

## Procedura universale
1. Leggere `git status`.
2. Individuare i file in conflitto.
3. Comprendere le due versioni.
4. Modificare il file scegliendo il risultato corretto.
5. Eliminare i marcatori di conflitto.
6. Eseguire test.
7. Fare `git add`.
8. Completare merge o rebase.

## Marcatori
~~~text
<<<<<<< HEAD
versione corrente
=======
versione concorrente
>>>>>>> feature/x
~~~

## Regola professionale
Il conflitto non è un errore di Git: è una decisione sul contenuto che Git non può prendere automaticamente.