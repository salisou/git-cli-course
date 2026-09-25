# git commit

## Cos'è
Registra nello storico il contenuto presente nella staging area.

## Sintassi
~~~bash
git commit -m "messaggio"
~~~

## Esempio
~~~bash
git add README.md
git commit -m "docs: aggiorna README"
~~~

## Errori comuni
`nothing to commit` significa che non ci sono modifiche staged.

## Esercizio
Crea una modifica, fai staging e crea un commit descrittivo.

## Buone pratiche
Evita messaggi generici come `update` o `fix`.