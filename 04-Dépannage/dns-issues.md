# Problèmes DNS

## Symptôme
- Le poste client ne résout pas le domaine

## Vérification
- Contrôler la carte réseau client (DNS = IP du DC)
- Tester `nslookup techcorp.local`

## Solution
- Corriger le DNS client vers DC01
- Redémarrer le service DNS si nécessaire
