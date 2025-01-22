# Séance 1 : Introduction à la Power Platform et notions fondamentales de gouvernance
## 1) Contenu théorique (1h)
- Panorama de la Power Platform : Power Apps, Power Automate, Power Pages, Power BI et Copilot Studio.
- Gouvernance et enjeux : pourquoi la gouvernance est cruciale (sécurité, conformité, standardisation, gestion du Shadow IT).
- Structure de la plateforme : Environnements, Dataverse, DLP (Data Loss Prevention), connecteurs, licences (Power Apps Pro, etc.).
- Présentation des rôles et responsabilités (administrateurs, makers, citoyens-développeurs, etc.).
## 2) Exercices & Ateliers (2h30 à 3h)
- Atelier d’exploration : Découverte de l’interface d’administration de la Power Platform (Power Platform Admin Center).
- Création d’un environnement de test : Configuration basique, paramétrages initiaux.
- Exercice sur la gouvernance : Identifier et décrire les règles de gouvernance nécessaires dans un scénario d’entreprise fictif.
## 3) Examen (1h)
- Examen théorique : QCM sur la terminologie, les concepts fondamentaux, les rôles et responsabilités.
- Quiz sur la gouvernance : Étude de cas rapide où le stagiaire doit recommander des règles de gouvernance.

# Séance 2 : Focus sur la gouvernance, les stratégies DLP et la gestion des environnements
## 1) Contenu théorique (1h)
- Stratégies de gouvernance avancées : Mise en place de Data Loss Prevention (DLP) et stratégies d’authentification.
- Gestion des environnements : Définition, nomenclature, cycles de vie, stratégies de provisioning.
- Licences et implications : Comparaison des différents types de licences, impacts sur l’architecture (Power Apps Pro, Premium, etc.).
## 2) Exercices & Ateliers (2h30 à 3h)
- Configuration DLP : Créer et configurer une stratégie DLP dans l’environnement de test.
- Organisation multi-environnements : Définir une hiérarchie (Production, Sandbox, Développement) et paramétrer chaque environnement.
- Étude de cas : Proposer un modèle de gouvernance simple pour une PME ou un grand compte.
## 3) Examen (1h)
- Examen théorique : QCM/QCU sur les stratégies DLP, best practices de gouvernance.
- Exercice rapide : Identifier les failles de gouvernance dans un exemple d’organisation.

# Séance 3 : Déploiement et exploration du CoE Starter Kit (Center of Excellence)
## 1) Contenu théorique (1h)
- Présentation du CoE Starter Kit : Objectifs, composants (audit, suivi des apps, gouvernance).
- Architecture du CoE : Connecteurs utilisés, flux Power Automate, tableaux de bord Power BI.
- Avantages : Visibilité globale, reporting sur les usages et les créateurs d’apps.
## 2) Exercices & Ateliers (2h30 à 3h)
- Installation du CoE Starter Kit : Préparation de l’environnement, mise en place pas à pas.
- Configuration initiale : Paramétrage des connecteurs (Admin | Compliance | Audit Logs, etc.).
- Exploration des rapports : Découverte des dashboards fournis et interprétation des données.
## 3) Examen (1h)
- Examen théorique : Questions sur les composants du CoE, compréhension du rôle de chaque outil.
- Étude de cas : Interpréter un rapport CoE Starter Kit et proposer des actions correctives.

# Séance 4 : ALM (Application Lifecycle Management) et Solutions dans la Power Platform
## 1) Contenu théorique (1h)
- Notions d’ALM dans la Power Platform : Solutions (gérer et transporter des personnalisations).
- Gestion des versions : Stratégies de versioning, bonnes pratiques de nommage.
- Environnements et déploiement de solutions : Processus de déplacement Dev → Test → Prod.
## 2) Exercices & Ateliers (2h30 à 3h)
- Création d’une solution : Inclure une Canvas App, un Flow et des tables Dataverse (ou entités).
- Export/Import : Déplacement de la solution d’un environnement Dev vers un environnement Test.
- Gestion des versions : Appliquer des mises à jour dans la solution et publier les modifications.
## 3) Examen (1h)
- Examen théorique : QCM sur les principes d’ALM, les étapes de déploiement, les bonnes pratiques de versioning.
- Exercice rapide : Correction d’erreurs dans un scénario de déploiement fictif (solution incomplète, environnement mal paramétré).

# Séance 5 : Mise en place du CI/CD avec Azure DevOps – Introduction
## 1) Contenu théorique (1h)
- Notions de CI/CD appliquées à la Power Platform : Principe, pipeline d’intégration continue, déploiement continu.
- Outils dans Azure DevOps : Repos, Pipelines, Boards, Artifacts.
- Configuration initiale : Connexion entre Azure DevOps et la Power Platform.
## 2) Exercices & Ateliers (2h30 à 3h)
- Création d’un projet dans Azure DevOps : Organisation, création des Repos (Git).
- Pipeline basique : Configuration d’un pipeline pour packager et déployer une solution Power Platform.
- Gestion des secrets : Utilisation d’Azure Key Vault (ou variables sécurisées) pour l’authentification.
## 3) Examen (1h)
- Examen théorique : QCM sur les principes de CI/CD, la structure d’un pipeline, la terminologie Azure DevOps.
- Exercice rapide : Créer ou compléter un fichier YAML de pipeline basique (blanc à remplir).

# Séance 6 : CI/CD avancé et automatisation des tests
## 1) Contenu théorique (1h)
- Pipelines de build et de release : Concepts avancés, stratégies de branches (GitFlow, etc.).
- Automatisation des tests : Power Apps Test Framework, tester automatiquement les Canvas Apps.
- Reporting de déploiement : Surveiller les logs, configurer des alertes.
## 2) Exercices & Ateliers (2h30 à 3h)
- Pipeline avancé : Mise en place d’un pipeline multi-étapes (Build → Test → Release).
- Integration de tests automatiques : Exemple de tests sur une Canvas App ou un Flow.
- Débogage : Simulation d’erreurs de déploiement, interprétation des logs et correctifs.
## 3) Examen (1h)
- Examen théorique : QCU/QCM sur les étapes d’un pipeline avancé, les frameworks de test, la gestion des défaillances.
- Exercice pratique : Résolution d’erreurs dans un pipeline existant (scénario complet).

# Séance 7 : Sécurité, DLP avancé et gouvernance d’applications
## 1) Contenu théorique (1h)
- Sécurité et rôles dans Dataverse : Configuration avancée, champs sécurisés, équipes, hiérarchies.
- DLP avancé : Gestion des exceptions, gouvernance des connecteurs personnalisés.
- Gouvernance des applications : Cycle de vie d’une application, mises à jour, retrait d’une application.
## 2) Exercices & Ateliers (2h30 à 3h)
- Gestion des rôles : Création d’un rôle de sécurité personnalisé dans Dataverse.
- Paramétrage DLP avancé : Empêcher l’utilisation de connecteurs sensibles, mise en place de politiques d’exception.
- Processus de gouvernance d’app : Formaliser le cycle de vie d’une app depuis la demande initiale jusqu’au décommissionnement.
## 3) Examen (1h)
- Examen théorique : Questionnaire sur la sécurité, l’attribution de rôles, les scénarios de DLP.
- Étude de cas : Proposer une architecture sécurisée pour une application sensible (données RH, par exemple).

# Séance 8 : Création et gouvernance d’une Canvas App avec bonnes pratiques UX/UI
## 1) Contenu théorique (1h)
- Rappels sur la création d’une Canvas App : Connecteurs, galeries, formulaires, bonnes pratiques de performance.
- Approche UX/UI : Design responsive, guidelines Microsoft, standardisation des composants.
- Contrôles et cycles de vie : Mise à jour, versioning, rollbacks.
## 2) Exercices & Ateliers (2h30 à 3h)
- Création d’une Canvas App : Scénario pratique (application de tickets internes, par ex.).
- Implémentation UX : Utilisation de composants réutilisables, adaptation responsive pour mobile.
- Analyse des performances : Mesurer et optimiser les performances (Checker intégré).
## 3) Examen (1h)
- Examen théorique : Questions sur l’architecture d’une Canvas App, la gestion des données, les best practices UX.
- Exercice rapide : Sur base d’une maquette, corriger/optimiser la structure d’une app existante.

# Séance 9 : Automatisation avec Power Automate, intégration et connecteurs
## 1) Contenu théorique (1h)
- Création de flux Power Automate : Triggers, actions, utilisation d’Approvals.
- Connecteurs standards et personnalisés : Mise en place, gouvernance et sécurité.
- Intégration avec d’autres services M365 : Teams, SharePoint, Outlook.
## 2) Exercices & Ateliers (2h30 à 3h)
- Création d’un flux approbation : Workflow d’approbation multi-niveaux (ex. validation de frais).
- Connexion à un service externe : Mise en place d’un connecteur personnalisé (si possible) ou utilisation d’un connecteur Premium.
- Intégration Power Apps/Power Automate : Lier l’app Canvas à un flux pour automatiser une action (ex. envoi d’email, mise à jour d’un enregistrement).
## 3) Examen (1h)
- Examen théorique : Quiz sur les types de flux, la configuration des connecteurs, la sécurité.
- Exercice pratique : Dépanner un flux existant qui ne s’exécute plus correctement (analyse d’erreurs).

# Séance 10 : Intégration globale et finalisation – Projet de synthèse
## 1) Contenu théorique (1h)
- Récapitulatif et bonnes pratiques : Synthèse sur la gouvernance, le CoE, le CI/CD, la sécurité.
- Gestion du changement et adoption : Stratégies de formation des utilisateurs, mise en place d’un centre de support.
- Modern Workspace : Intégration des apps et flux dans Microsoft Teams, SharePoint, etc.
## 2) Exercices & Ateliers (2h30 à 3h)
- Projet de synthèse : Créer une solution complète (Canvas App + Flow + tables Dataverse) avec déploiement via pipeline Azure DevOps.
- Vérifier la conformité avec la gouvernance mise en place (DLP, sécurité, rôles).
- Mise en situation : Présentation du projet réalisé, passage en « Production » simulée.
## 3) Examen (1h)
- Examen final : Évaluation écrite et/ou pratique.
- Validation de la compréhension globale (gouvernance, ALM, CoE, CI/CD).
- Analyse de cas pratiques (résolution de problèmes courants).
## Conclusion : Retours d’expérience, discussion sur les perspectives d’évolution (Power Pages, IA Builder, etc.).
