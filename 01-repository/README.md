# 01 — Repository, staging e commit

Una repository contiene la cronologia Git. Il ciclo fondamentale è:

1. modifica un file;
2. `git status`;
3. `git add`;
4. `git status`;
5. `git commit`;
6. controlla la storia.

Laboratorio:
```bash
mkdir laboratorio-git
cd laboratorio-git
git init
echo "# Laboratorio" > README.md
git status
git add README.md
git commit -m "docs: add initial README"
```
