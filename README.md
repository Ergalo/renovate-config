# Ergalo — règles Renovate communes

Dépôt public : les règles de mises à jour automatiques de tous les projets Ergalo (les nôtres et ceux des clients).

- Correctifs et versions mineures : fusionnés automatiquement si la CI est verte.
- Versions majeures : regroupées et proposées du 1er au 7 du mois, jamais fusionnées seules.
- Failles de sécurité : traitées tout de suite.
- Images Docker : épinglées par empreinte.

## Utilisation

Dans `renovate.json` du projet :

```json
{
  "extends": ["github>Ergalo/renovate-config"]
}
```

L'application gratuite Mend Renovate doit être installée sur l'organisation GitHub du projet.
