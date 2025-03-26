# Modèle de documentation – Environnements Power Platform

Ce modèle permet de documenter les principales fonctionnalités et paramètres des environnements Power Platform de Microsoft. Il est structuré par types d’environnement : **Par défaut**, **Teams**, **Production**, **Développeur**, **Bac à sable** et **Essai**.

---

## Chapitre 1 – Informations générales sur l’environnement

- **Nom de l’environnement** :  
- **Nom d’affichage** :  
- **Type** (Par défaut, Production, etc.) :  
- **Région** :  
- **Date de création** :  
- **Date de dernière modification** :  
- **ID de l’environnement (GUID)** :  
- **Est l’environnement par défaut ?** (Oui/Non) :  
- **URL de l’environnement** :  

---

## Chapitre 2 – Détails spécifiques selon le type d’environnement

### 2.1 Environnement Par défaut
- Créé automatiquement pour chaque locataire  
- Un seul par locataire  
- Partagé par tous les utilisateurs  

**Restrictions de personnalisation :**
- [ ] Création d’applications autorisée  
- [ ] Création de flux autorisée  

**Notes de gouvernance :**  
**Rôles de sécurité :**  

---

### 2.2 Environnement Teams
- Lié à une équipe Microsoft Teams  
- Créé à la demande  
- Ne peut pas être supprimé manuellement  

**Dataverse pour Teams associé :**
- [ ] Capacité de stockage  
- [ ] Permissions gérées via Teams  

**Notes de gouvernance :**  

---

### 2.3 Environnement de Production
- Utilisé pour les applications et flux en production  
- Requiert une base de données (Dataverse)  

**Paramètres :**
- Capacité allouée :  
- Accès administrateur :  
- Groupes de sécurité appliqués :  
- Connecteurs activés/désactivés :  
- Sauvegarde et récupération :  

---

### 2.4 Environnement Développeur
- Un par utilisateur (avec un plan Développeur)  
- Destiné à l’apprentissage et aux applications personnelles  

**Détails :**
- Politique de nettoyage automatique :  
- Capacité de stockage :  
- Restrictions :  

---

### 2.5 Environnement Bac à sable
- Utilisé pour les tests et la validation  
- Peut être réinitialisé ou copié  

**Copie depuis** : Production / Autre  
**Éléments copiés :**
- [ ] Applications  
- [ ] Flux  
- [ ] Données  
- [ ] Connexions  

**Actions administratives :**
- Réinitialisation  
- Conversion en Production  

---

### 2.6 Environnement d’Essai
- Temporaire (30 jours par défaut)  
- Utilisé pour des démonstrations ou des tests  

**Détails :**
- Date d’expiration automatique :  
- Prolongeable :  
- Limites de stockage :  
- Peut être converti en Production :  

---

## Chapitre 3 – Paramètres de la base de données Dataverse

- Base de données provisionnée :  
- Capacité utilisée (en Go) :  
- Nombre de tables :  
- Tables personnalisées :  
- Tables gérées :  
- Audit activé :  
- Politiques de rétention :  

---

## Chapitre 4 – Sécurité et contrôle d’accès

- Groupes de sécurité appliqués :  
- Rôles administrateurs :  
- Rôles créateurs (makers) :  

**Rôles d’environnement :**
- [ ] Administrateur d’environnement  
- [ ] Créateur d’environnement  

**Aperçu des accès utilisateurs :**  
**Politiques d’accès conditionnel :**  
**Accès invité :**  

---

## Chapitre 5 – Politiques de données et DLP

- Politiques DLP appliquées :  
- Connecteurs bloqués :  
- Connecteurs autorisés :  
- Séparation données professionnelles / non professionnelles :  
- Exceptions :  

---

## Chapitre 6 – Connecteurs personnalisés et passerelles

- Connecteurs personnalisés créés :  
- Connecteurs certifiés utilisés :  
- Passerelle de données installée :  
- Groupes de passerelles :  
- Administrateurs de passerelles :  

---

## Chapitre 7 – Paramètres d’intégration

- Intégration Azure (Functions, Logic Apps) :  
- Intégration Microsoft 365 (Outlook, SharePoint, Teams) :  
- APIs externes :  
- Webhooks :  
- Intégration Power BI :  
- Autres services :  

---

## Chapitre 8 – Gestion de la capacité

- Capacité totale allouée :  
- Capacité utilisée :  
  - [ ] Base de données  
  - [ ] Fichiers  
  - [ ] Journaux  
- Alertes de capacité :  
- Politiques de quotas :  
- Dernière vérification de capacité :  

---

## Chapitre 9 – ALM et déploiements

- Solutions utilisées :  
- Gérées / Non gérées :  
- Références de connexion :  
- Pipelines de déploiement configurés :  
- Branches (Dév / Test / Prod) :  
- Outils utilisés (PAC CLI, GitHub Actions, Azure DevOps) :  

---

## Chapitre 10 – Notes de gouvernance et observations

- Propriétaire de l’environnement :  
- Notes opérationnelles :  
- Problèmes observés :  
- Changements prévus :  
- Calendrier de maintenance :  

---
