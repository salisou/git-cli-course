# Git CLI Cheatsheet

## Configurazione
~~~bash
git --version
git config --global user.name "Nome"
git config --global user.email "email@example.com"
~~~

## Repository
~~~bash
git init
git clone <url>
git status
~~~

## Snapshot
~~~bash
git add .
git diff
git diff --staged
git commit -m "..."
~~~

## Storia
~~~bash
git log --oneline --graph --decorate --all
git show <commit>
git blame <file>
~~~

## Branch
~~~bash
git branch
git switch -c feature/x
git switch main
git merge feature/x
git rebase main
~~~

## Remote
~~~bash
git remote -v
git fetch origin
git pull --ff-only
git push -u origin feature/x
~~~

## Recovery
~~~bash
git restore
git reset
git revert
git reflog
~~~

## Release
~~~bash
git tag -a v1.0.0 -m "Release 1.0.0"
git push origin v1.0.0
~~~