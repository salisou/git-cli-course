# git reset

Sposta HEAD e, in base all'opzione, aggiorna staging e working tree.

```bash
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
```

soft conserva staging; mixed conserva i file ma svuota lo staging; hard riallinea anche i file e va usato con estrema attenzione.
