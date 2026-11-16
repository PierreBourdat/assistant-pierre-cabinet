# Assistant du cabinet BOURDAT Finance - Adviteo

## Objectif
Donner à Claude Code les règles, modèles et notes de méthode pour assister Pierre au quotidien :
mails, agenda, documents, suivi des clients. Le dépôt ne contient pas de code.

## Principes
- Claude prépare, Pierre décide : aucun envoi, aucune suppression, aucune écriture sans accord.
- Aucune donnée client ni secret dans ce dépôt.
- Rien n'entre dans `main` sans l'accord de Pierre.

## Sources de vérité
| Quoi | Où |
|---|---|
| Règles de Claude | `CLAUDE.md` |
| Mails | Gmail |
| Agenda | Google Calendar |
| Comptabilité | Pennylane |
| Clients et prospects | HubSpot |
| Notes et comptes rendus | Notion |
| Documents | Google Drive |
| Signatures | Youtrust |
| Méthodes réutilisables | Skills Claude (`redaction-mails-cabinet`, `business-plan-previsionnel`, `declaration-de-soupcon`) |

## Structure
- `CLAUDE.md` : règles impératives pour Claude.
- `PLAN.md` : organisation retenue, décisions, phases.
- `docs/architecture.md` : outils reliés, flux, sécurité.
- `docs/processus.md` : inventaire des automatisations.
- `notes/` : notes de méthode (sans données clients).
- `.claude/settings.json` : verrous sur les outils dangereux.

## Contribution
Branche dédiée, PR brouillon en français (quoi, pourquoi, comment vérifier), fusion en squash
uniquement sur « fusionne » de Pierre.

## Environnements
Sessions Claude Code dans le cloud (claude.ai/code), connecteurs claude.ai pour les outils ci-dessus.
