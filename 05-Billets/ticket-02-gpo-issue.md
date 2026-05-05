# Ticket #002 — GPO non appliquée

## Problème

CMD non bloqué

## Analyse

```powershell
gpresult /r
```

📸 Capture d’écran

## Solution

- `gpupdate /force`

## Résultat

- GPO appliquée
