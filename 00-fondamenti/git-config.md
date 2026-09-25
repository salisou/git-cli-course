# git config

## Cos'è
Gestisce le impostazioni di Git.

## Perché usarlo
L'identità dell'autore viene registrata nei commit; una configurazione coerente evita commit attribuiti male.

## Sintassi
```bash
git config [--global|--local] chiave valore
```

## Esempi
```bash
git config --global user.name "Moussa Salisou"
git config --global user.email "email@example.com"
git config --global init.defaultBranch main
git config --global core.editor "code --wait"
git config --global --list
```

## Errore comune
Confondere `--global` con `--local`: global vale per l'utente, local per la repository corrente.

## Esercizio
Imposta nome, email e branch predefinito `main`.
