# Problèmes DNS

## Symptôme

- Le poste client ne résout pas le domaine

📸 Capture d’écran : erreur DNS

## Vérification

- Contrôler la carte réseau client (DNS = IP du DC)
- Tester `nslookup techcorp.local`

## Solution

- Corriger le DNS client vers DC01
- Redémarrer le service DNS si nécessaire
