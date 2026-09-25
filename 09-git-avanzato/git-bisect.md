# git bisect

Usa una ricerca binaria nella storia per individuare il commit che ha introdotto un problema.

```bash
git bisect start
git bisect bad
git bisect good <commit-funzionante>
# esegui il test
git bisect good
# oppure git bisect bad
git bisect reset
```

È particolarmente efficace quando esiste un test riproducibile.
