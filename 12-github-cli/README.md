# GitHub CLI (gh)

## Cos'è
`gh` permette di lavorare con GitHub dal terminale.

## Verifica
~~~bash
gh --version
gh auth status
~~~

## Comandi
~~~bash
gh repo clone OWNER/REPO
gh issue list
gh pr list
gh pr create --fill
gh pr view 123
gh pr checkout 123
~~~

## Esercizio
Autentica `gh`, elenca le issue e crea una Pull Request di prova.