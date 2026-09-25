# Progetto finale — Git Professional Team Workflow

## Obiettivo
Simulare lo sviluppo di una piccola applicazione in un team.

## Requisiti
Repository locale e remoto, branch feature, commit professionali, Pull Request, review, conflitto, merge, revert, tag, recovery e diagnosi.

## Bootstrap
~~~bash
git init
git branch -M main
git remote add origin <repository-url>
~~~

## Feature
~~~bash
git switch -c feature/login
git add .
git commit -m "feat: aggiunge login"
git push -u origin feature/login
~~~

## Release
~~~bash
git switch main
git pull --ff-only
git tag -a v1.0.0 -m "Release 1.0.0"
git push origin v1.0.0
~~~

## Consegna
Almeno 10 commit significativi, 2 branch, una PR, un conflitto documentato, un tag e una relazione finale.