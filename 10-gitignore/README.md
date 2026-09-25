# 10 — .gitignore

Evita di versionare file generati, segreti, cache, build e configurazioni locali.

```gitignore
bin/
obj/
.vscode/
.env
*.log
__pycache__/
```

Un segreto non deve essere committato solo perché è in .gitignore: se è già stato pubblicato, va revocato e sostituito.
