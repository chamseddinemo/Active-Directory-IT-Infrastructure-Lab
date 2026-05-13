# GPO ne s’applique pas

## Symptôme
- User n’a pas restriction

## Vérification
powershell : gpresult /r

## Causes possibles
- Mauvais OU
- Filtrage groupe incorrect

## Solution
- Vérifier le groupe
- `gpupdate /force`
