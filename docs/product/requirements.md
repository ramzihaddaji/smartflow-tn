# Cahier des charges MVP V1

| ID | Fonctionnalité | Description | Priorité |
|---|---|---|---|
| F01 | Gestion des prospects | Ajouter et consulter les candidats | P0 |
| F02 | Formulaire | Collecter les demandes | P0 |
| F03 | Gestion des formations | Définir les formations | P0 |
| F04 | Statuts | Suivre la progression | P0 |
| F05 | WhatsApp | Générer un lien de contact | P0 |
| F06 | Relances | Définir une date de rappel | P0 |
| F07 | Notifications | Alerte e-mail | P1 |
| F08 | Dashboard | Indicateurs | P1 |
| F09 | Recherche | Retrouver un candidat | P1 |
| F10 | Export | CSV | P2 |

## Statuts officiels
Nouveau, À contacter, Contacté, Intéressé, Inscription confirmée, Perdu.
(« Intéressé » ≠ « Inscrit »)

## Règles métier
- R1 Création automatique avec statut Nouveau
- R2 Notification au responsable
- R3 Date de relance
- R4 Relances en retard : liste prioritaire
- R5 Conversion : Inscription confirmée
- R6 Taux de conversion = inscriptions confirmées / prospects totaux × 100
- R7 Détection des doublons par téléphone, sans suppression
- R8 Historique des changements de statut

## Hors MVP
Comptabilité, facturation, salaires, RH, applis mobiles, chatbot IA, envoi WhatsApp automatique, gestion des étudiants/examens, paiement en ligne, multi-établissements.
