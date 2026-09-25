# git reset

## Cos'è
Sposta HEAD e può modificare index e working tree.

## Modalità
~~~bash
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
~~~

## Differenze
`soft`: mantiene staging e working tree.  
`mixed`: aggiorna HEAD e index, mantiene working tree.  
`hard`: allinea anche working tree e può eliminare modifiche locali.

## Regola
Non usare `--hard` senza aver verificato cosa verrà perso.

## Esercizio
Crea due commit e annulla l'ultimo con `--soft`.