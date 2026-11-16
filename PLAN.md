# Plan

## Organisation retenue
- Un dépôt de règles et de méthodes, sans code ni données clients.
- Les données restent dans les outils métiers (Gmail, Pennylane, HubSpot, Notion, Drive).
- Les méthodes longues vivent dans des skills Claude ; ce dépôt y renvoie.

## Décisions
- Mails : brouillons uniquement, jamais d'envoi direct (verrou dans `.claude/settings.json`).
- Écritures dans les outils : après validation de Pierre (confirmation demandée par Claude Code).
- Fusion en squash, sur « fusionne » de Pierre ; Claude fusionne après une carte de confirmation (`ask`, jamais `deny`).
- Pas de workflow de tests : le dépôt ne contient pas de code.

## Phases
### Phase 1 - Gouvernance
- [x] Règles de Claude (`CLAUDE.md`)
- [x] Fichiers de départ (README, PLAN, docs, CODEOWNERS, verrous, .gitignore)
- [x] Réglages GitHub cochés par Pierre

### Phase 2 - Méthodes
- [ ] Notes de méthode dans `notes/` au fil des sessions (tri des mails, préparation des rendez-vous)
- [x] Règle du fichier Stripe (suivi ADV) dans `CLAUDE.md`
- [ ] Inventaire des automatisations tenu à jour dans `docs/processus.md`
