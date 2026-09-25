# git reflog

## Cos'è
Registra localmente i movimenti dei riferimenti come HEAD.

## A cosa serve
Aiuta a recuperare riferimenti dopo reset, rebase o altre operazioni locali.

## Sintassi
~~~bash
git reflog
git reflog show main
~~~

## Recupero
~~~bash
git reflog
git branch recovery/backup <hash>
git log --oneline recovery/backup
~~~

## Limite
È principalmente un registro locale e non sostituisce un backup remoto.