# git push

## Cos'è
Invia commit e riferimenti locali a un repository remoto.

## Sintassi
~~~bash
git push
git push -u origin main
git push -u origin feature/login
~~~

## Esempio
~~~bash
git switch -c feature/login
git add .
git commit -m "feat: aggiunge login"
git push -u origin feature/login
~~~

## Attenzione
`git push --force` può sovrascrivere la storia remota. Quando appropriato, `--force-with-lease` aggiunge una protezione, ma va usato solo su branch dove la riscrittura è consentita.