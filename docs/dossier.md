# Plan pour un dossier d'architecture de migration Metabase

## 1. Introduction
- Objectif de la migration.  
- Contexte actuel (Elastic Beanstalk + RDS).  
- Enjeux et bénéfices attendus (flexibilité, sécurité, coût, etc.).  

## 2. Architecture Actuelle
- Schéma de l’architecture (Elastic Beanstalk, RDS, réseaux).  
- Points faibles identifiés (performances, sécurité, limitations).  

## 3. Architecture Cible
- Schéma de l’architecture cible (EC2 + RDS, VPC, groupes de sécurité).  
- Description des composants (instances EC2, RDS, monitoring, sauvegardes).  
- Avantages de l’architecture cible.  

## 4. Plan de Migration
- Étapes détaillées :  
  - Préparation de l’environnement (création des instances EC2, configuration réseau).  
  - Migration de l’application Metabase (déploiement Docker ou binaire sur EC2).  
  - Migration et test de la base de données (RDS).  
  - Validation et tests finaux (performances, fonctionnalités).  
- Stratégie de bascule (downtime minimal ou migration progressive).  

## 5. Sécurité et Résilience
- Renforcement des accès (groupes de sécurité, SSH, IAM).  
- Plan de sauvegarde et reprise après sinistre.  

## 6. Surveillance et Maintenance
- Configuration des outils de monitoring (CloudWatch, logs).  
- Plan de mise à jour et gestion des incidents.  

## 7. Conclusion
- Résumé des bénéfices apportés par la migration.  
- Étapes futures ou optimisations possibles.  
