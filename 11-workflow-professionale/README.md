# Workflow professionale

## Ciclo quotidiano
~~~text
modifica -> status -> diff -> add -> diff --staged -> commit -> fetch -> push
~~~

## Feature workflow
~~~bash
git switch main
git pull --ff-only
git switch -c feature/nome
git status
git diff
git add .
git commit -m "feat: descrizione"
git push -u origin feature/nome
~~~

## Conventional Commits
~~~text
feat: nuova funzionalità
fix: correzione
docs: documentazione
refactor: ristrutturazione
test: test
chore: manutenzione
~~~

## Regola
Le policy di merge, rebase, review e protezione branch devono essere concordate dal team.