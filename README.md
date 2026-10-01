# AutoLoc

Plateforme de gestion de location de véhicules multi-agences.

## Acteurs

- **Client** : consulte les véhicules disponibles, réserve et loue un véhicule.
- **Agent d'agence** : gère les locations au quotidien (remise et retour des véhicules).
- **Responsable d'agence** : supervise son agence (parc de véhicules, agents, activité).
- **Administrateur** : administre la plateforme (agences, comptes, paramètres).

## Cas d'utilisation

### Client
- Créer un compte et s'authentifier
- Consulter les véhicules disponibles
- Réserver un véhicule
- Annuler ou modifier une réservation
- Consulter l'historique de ses locations

### Agent d'agence
- Enregistrer un client
- Créer une location à partir d'une réservation
- Enregistrer le retour d'un véhicule
- Mettre à jour la disponibilité d'un véhicule
- Générer la facture d'une location

### Responsable d'agence
- Gérer le parc de véhicules de son agence
- Gérer les agents de son agence
- Consulter le tableau de bord de son agence
- Transférer un véhicule vers une autre agence

### Administrateur
- Gérer les agences
- Gérer les comptes et les rôles des utilisateurs
- Paramétrer les catégories de véhicules et les tarifs
- Consulter les statistiques globales
