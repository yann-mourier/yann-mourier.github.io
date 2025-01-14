# Fiche de Révision : Présentation du Projet Yann Mourier

## **Introduction**
- **Titre** : Présentation de Projet - Expert en architectures systèmes, réseaux et sécurité informatique
- **Objectif** : Présenter le projet, ses étapes, et les compétences mobilisées pour l’obtention de la certification RNCP38823 (Niveau 7).

---

### **Diapositives et Notes Associées par Blocs de Compétences**

---

## **Bloc A1 : Organisation du projet systèmes et réseaux** (Durée : 20 minutes)

### **Présentation personnelle et de l’entreprise**
1. **Diapositive : Qui je suis ?**
   - **Durée estimée :** 2 minutes.
   - **Contenu :** Yann Mourier, 23 ans, issu d’une formation d’électricien, basé à Saint-Laurent-en-Royans.
   - **Note :** Insister sur le parcours atypique et la transition réussie vers le domaine IT pour montrer l’adaptabilité.

2. **Diapositive : Présentation de l’entreprise**
   - **Durée estimée :** 3 minutes.
   - **Chiffres clés :** 
     - 2009 : Création de la première agence.
     - Plus de 100 agences en France.
     - Chiffre d’affaires : 60 M€ en 2019.
     - 110 salariés.
   - **Domaines d’activité :**
     - Achat/vente de métaux précieux (or, argent, objets plaqués or).
     - Services : Or Collection, Or Investissement.
   - **Note :** Souligner la diversification des activités et la solidité financière.

### **Organisation et gestion du projet**
3. **Diapositive : Réglementations et veille technologique**
   - **Durée estimée :** 4 minutes.
   - **Réglementations :** 
     - ISO 9001, 27001, 27701.
     - Implémentations : Chiffrement KMS, Secret Manager, réseaux privés.
   - **Veille Technologique :** 
     - Outils : Feedly, Twitter, forums, vidéos techniques.
   - **Note :** Expliquer l’impact de la veille et des normes sur le projet.

4. **Diapositive : Architecture actuelle (Bloc A1.1)**
   - **Durée estimée :** 3 minutes.
   - **Problèmes majeurs :**
     - Manque de documentation.
     - Infrastructure publique (Elastic Beanstalk).
     - Coûts élevés et organisation inefficace.
   - **Note :** Expliquer pourquoi l’architecture actuelle est inadéquate pour les objectifs de l’entreprise.

5. **Diapositive : Architecture cible (Bloc A1.4)**
   - **Durée estimée :** 4 minutes.
   - **Caractéristiques :**
     - Cloisonnement des environnements (Dev, Pré-prod, Prod).
     - Gestion via Kubernetes et Infrastructure as Code (IaC).
     - Sécurité renforcée.
   - **Note :** Montrer comment cette transition répond aux besoins métier et réglementaires.

6. **Diapositive : Planification et suivi (Blocs A1.5, A1.8)**
   - **Durée estimée :** 4 minutes.
   - **Objectifs SMART** et Matrice RACI.
   - **Suivi des compétences et formations.**
   - **Note :** Relier la planification à la méthodologie et aux résultats obtenus.

---

## **Bloc A2 : Développer des solutions d’infrastructure systèmes et réseaux** (Durée : 20 minutes)

### **Conception et mise en œuvre**
1. **Diapositive : Architecture cible et Kubernetes (Blocs A2.1, A2.2)**
   - **Durée estimée :** 5 minutes.
   - **Caractéristiques :**
     - Migration vers Kubernetes.
     - Utilisation d’Infrastructure as Code (Terraform).
   - **Note :** Insister sur l’automatisation et la flexibilité offertes.

2. **Diapositive : Fonctionnement d’une maintenance (Bloc A2.3)**
   - **Durée estimée :** 4 minutes.
   - **Étapes clés :**
     - Préparation.
     - Mise à jour.
     - Validation post-mise à jour.
   - **Note :** Montrer comment une maintenance bien planifiée minimise les interruptions.

### **Surveillance et amélioration continue**
3. **Diapositive : Surveillance - Outils (Blocs A2.4, A2.5)**
   - **Durée estimée :** 5 minutes.
   - **Outils :**
     - CloudWatch, Prometheus, Grafana.
     - Alertes configurées pour CPU, connexions, espace disque.
   - **Note :** Illustrer l’impact du monitoring sur la qualité du service.

4. **Diapositive : Documentation technique (Bloc A2.7)**
   - **Durée estimée :** 3 minutes.
   - **Outils :** Confluence pour la gestion centralisée des connaissances.
   - **Note :** Souligner l’importance de la documentation pour la durabilité de l’infrastructure.

---

## **Bloc A3 : Sécurité de l’infrastructure informatique** (Durée : 20 minutes)

### **Évaluation et plan de sécurité**
1. **Diapositive : Architecture actuelle et sécurité (Bloc A3.1)**
   - **Durée estimée :** 3 minutes.
   - **Problèmes identifiés :**
     - Infrastructure publique.
     - Manque de cloisonnement et de contrôle des accès.
   - **Note :** Expliquer l’importance de l’évaluation initiale.

2. **Diapositive : Plan PCA/PRA (Bloc A3.3)**
   - **Durée estimée :** 4 minutes.
   - **Objectif :** Assurer la continuité des services en cas de panne.
     - Snapshots RDS.
     - Réplication Multi-AZ.
   - **Note :** Insister sur les tests réguliers pour garantir l’efficacité.

### **Implémentation des solutions de sécurité**
3. **Diapositive : IAM Identity Center et Groupes de Sécurité (Blocs A3.4, A3.5)**
   - **Durée estimée :** 5 minutes.
   - **IAM Identity Center :**
     - Gestion centralisée des accès.
     - MFA obligatoire.
   - **Groupes de Sécurité :**
     - Autorisation stricte des connexions HTTP/HTTPS.
   - **Note :** Montrer comment ces outils augmentent la résilience.

4. **Diapositive : Surveillance et alertes (Bloc A3.5)**
   - **Durée estimée :** 4 minutes.
   - **Outils :** Prometheus, Grafana.
   - **Note :** Illustrer l’intégration des alertes pour une gestion proactive des incidents.

---

## **Bloc A4 : Management de l’équipe de projet** (Durée : 20 minutes)

### **Collaboration et formation**
1. **Diapositive : Collaboration de l’équipe (Bloc A4.2)**
   - **Durée estimée :** 4 minutes.
   - **Outils :**
     - Transition vers Office 365 et Teams.
     - Daily meetings pour éviter le travail en silo.
   - **Note :** Montrer comment ces pratiques renforcent la cohésion de l’équipe.

2. **Diapositive : Formations et certifications (Bloc A4.4)**
   - **Durée estimée :** 5 minutes.
   - **Contenu :**
     - AWS Cloud Practitioner, Kubernetes, Terraform.
   - **Note :** Souligner l’impact sur la montée en compétences et la répartition des tâches.

### **Conclusion**
3. **Diapositive : Résumé et impact global (Bloc A4)**
   - **Durée estimée :** 4 minutes.
   - **Résumé du projet :**
     - Migration réussie vers Kubernetes.
     - Sécurité et performances accrues.
   - **Note :** Mettre en avant la contribution à la stratégie globale de l’entreprise.

---

### **Conseils pour la présentation**
1. **Structure claire :** Respecter les blocs de compétences pour une progression logique.
2. **Focus technique :** Expliquer les choix et outils en détail.
3. **Interaction :** Préparer des réponses sur les choix stratégiques et techniques.

---

### **Blocs de compétences mobilisés**
1. **Bloc A1 : Organisation du projet systèmes et réseaux**
   - Analyse de l’existant, veille, planification, et contrôle.
2. **Bloc A2 : Développement des solutions d’infrastructure**
   - Conception, mise en œuvre, maintenance, documentation.
3. **Bloc A3 : Sécurité de l’infrastructure informatique**
   - Évaluation, implémentation, gestion des incidents.
4. **Bloc A4 : Management de l’équipe de projet**
   - Collaboration, formation, suivi des performances.

---

Bonne révision et préparation à votre présentation !

