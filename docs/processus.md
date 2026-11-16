# Processus et automatisations

Inventaire de chaque automatisation : ce qu'elle fait, quand, où elle vit.
Toute automatisation ajoutée, modifiée ou supprimée met à jour ce fichier dans la même PR.

| Automatisation | Ce qu'elle fait | Quand | Où elle vit |
|---|---|---|---|
| Revue d'actualités hebdomadaire | Veille IA, Pennylane, outils cabinet, présidentielle  ; message court puis revue complète, directement dans la session « Actualités » | Vendredi 5 h 47 (Paris), prête pour 7 h | Tâche planifiée claude.ai, alimente la session « Actualités » (consigne permanente dans son premier message) |

## Tâches manuelles récurrentes (à la demande de Pierre)
- Tri de la boîte mail et brouillons de réponse : skill `redaction-mails-cabinet`.
- Suivi ADV Stripe : ligne proposée à partir des mails (bon pour accord, résiliation, nouveau client), écrite après accord de Pierre ; règles dans `CLAUDE.md`.
- Business plan prévisionnel : skill `business-plan-previsionnel`.
- Déclaration de soupçon LAB : skill `declaration-de-soupcon`.
