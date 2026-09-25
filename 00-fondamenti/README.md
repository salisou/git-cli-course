# 00 — Fondamenti

## Git e GitHub
Git è un sistema distribuito di controllo versione. GitHub è una piattaforma che ospita repository Git e aggiunge collaborazione, issue, pull request, review e automazioni.

## Il modello mentale
Working tree → staging area → commit → branch → remote.

## Installazione
Verifica con:

```bash
git --version
```

Configura identità:

```bash
git config --global user.name "Nome Cognome"
git config --global user.email "email@example.com"
git config --global init.defaultBranch main
```

Controlla:

```bash
git config --global --list
```
