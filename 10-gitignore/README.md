# .gitignore

## Esempio
~~~gitignore
bin/
obj/
.vscode/
.env
*.log
__pycache__/
node_modules/
~~~

## Regola importante
Un `.gitignore` impedisce normalmente il tracking di nuovi file, ma non protegge un segreto già committato.

## File già tracciato
~~~bash
git rm --cached .env
git commit -m "chore: rimuove configurazione dal tracking"
~~~

## Esercizio
Crea un `.gitignore` per un progetto .NET o Python e verifica con `git status`.