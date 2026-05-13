# Ticket #002 — GPO non appliquée

## Problème
CMD non bloqué

## Analyse
powershell : gpresult /r


## Solution
- `gpupdate /force`

## Résultat
- GPO appliquée
