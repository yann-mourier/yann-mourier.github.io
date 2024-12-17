# Migrations AWS

## A1 : Organisation du projet systèmes et réseaux  

### Présentation de la situation actuelle  

#### Architecture Legacy  
Décrire l'architecture actuelle du système, y compris les outils, les serveurs, et les technologies en place.  

#### Architecture cible  
Présentation de l'architecture cible après la migration vers AWS, en détaillant les composants, services et ressources impliqués.  

#### Analyse de faisabilité  
- **Coûts** : Évaluation des coûts associés à la migration vers AWS, incluant les coûts de service, de gestion, et d'infrastructure.  
- **Technologies** : Technologies sélectionnées pour la nouvelle architecture, en tenant compte des besoins et des contraintes.  
- **Impact organisationnel** : L'impact sur les équipes et les processus de l'entreprise, incluant les besoins en formation et l'adoption des nouvelles technologies.  

#### Explication de la nouvelle infrastructure  
Détails sur les services AWS utilisés, les raisons de leur choix et leur rôle dans la nouvelle infrastructure.  

#### Suivi du projet  
- **KPIs** : Indicateurs clés de performance utilisés pour suivre la réussite de la migration.  
- **Analyse des performances** : Mesures de performance après la migration.  
- **Respect des objectifs** : Évaluation de la conformité aux objectifs définis avant la migration.  

### Compétences associées  
- **Analyse approfondie de l’architecture systèmes et réseaux existante**  
- **Mise en place du plan de veille technologique et réglementaire des systèmes et réseaux informatiques**  
- **Analyse de faisabilité du projet d’architecture informatique**  
- **Description de la solution d’architecture informatique proposée à l’entreprise**  
- **Élaboration du projet d’architecture informatique**  
- **Mise en œuvre du projet d’architecture informatique**  
- **Évaluation de la performance du projet d’architecture informatique**  
- **Contrôle du projet d’architecture informatique**  

---

## A2 : Construire la solution technique du projet de systèmes-réseaux et sécurité  

### Metabase  

#### Conception de l'architecture (Diagramme)  
Présentation du diagramme représentant l'architecture de Metabase existante puis l'architecture cible dans le cadre de la migration AWS.  

#### Mise en place de l'architecture et difficultés rencontrées  
- **Problèmes rencontrés** : La migration sans mise à jour était impossible, et des problèmes de taille de la base de données sont apparus.  
- **Solutions trouvées** : Explication des solutions trouvées en anglais pour résoudre ces problèmes.  

#### Explication du fonctionnement des maintenances  
Présentation du processus de maintenance pour garantir la disponibilité et la fiabilité de l'application Metabase.  

#### Surveillance de l'infrastructure  
Utilisation de **Prometheus**, **Grafana** et **CloudWatch** pour surveiller l'infrastructure de Metabase.  

#### Évolution de l'infrastructure  
Prévisions sur l'évolution de l'infrastructure, notamment avec l'implémentation potentielle de **Kubernetes**.  

#### Explication de la documentation  
Présentation de la documentation liée à Metabase et à son architecture AWS.  

---

### Serveur Packages  

#### Conception de l'architecture (Diagramme)  
Diagramme représentant l'architecture du serveur de packages en utilisant de l'infrastructure as code (IaC).  

#### Mise en place de l'architecture et difficultés rencontrées  
- **Problèmes rencontrés** : Description des difficultés lors de la mise en place de l'architecture.  
- **Solutions trouvées** : Solutions proposées pour résoudre ces problèmes en anglais.  

#### Surveillance de l'infrastructure  
Surveillance de l'infrastructure du serveur de packages avec **Prometheus**, **Grafana** et **CloudWatch**.  

#### Explication de la documentation  
Présentation de la documentation relative à l'architecture et à la gestion du serveur de packages.  

### Compétences associées  
- **Élaboration de l’architecture informatique évolutive**  
- **Mise en place de l’architecture informatique**  
- **Maintenance du niveau de service optimal de l’infrastructure informatique**  
- **Surveillance du bon fonctionnement de l’infrastructure informatique**  
- **Pilotage de l’amélioration de la qualité du service informatique**  
- **Évolution de l’architecture informatique**  
- **Élaboration de la documentation technique**  

---

## A3 : Organiser la sécurité de l’infrastructure informatique  

### Metabase  

#### Explication de la sécurité actuelle  
- **Réseau public** : L'architecture actuelle expose Metabase à un réseau public.  
- **Credentials dans les variables Elastic Beanstalk** : Utilisation de variables d'environnement pour stocker les informations sensibles.  

#### Veille informatique avec Feedly  
Explication de la mise en place de la veille informatique à l'aide de **Feedly** pour suivre les actualités liées à AWS et à Metabase.  

#### Mise en place de policies AWS personnalisées  
Création de **policies personnalisées AWS** avec le principe du minimum de privilèges pour renforcer la sécurité.  

#### Mise en place de GuardDuty et Secret Manager  
- **GuardDuty** : Mise en place de GuardDuty pour la surveillance des menaces.  
- **Secret Manager** : Utilisation de **AWS Secrets Manager** pour gérer les secrets et les clés d'API de manière sécurisée.  

#### Création de tickets en cas d'incident  
- **Auto-scaling** : Processus d'auto-scaling pour recréer les instances EC2 en cas d'incident.  
- **Snapshots RDS** : Prise de snapshots des bases de données RDS pour garantir la continuité de service.  

#### Évolution possible à venir  
Discussion des évolutions potentielles de l'architecture et des pratiques de sécurité.  

---

### Serveur Packages  

#### Explication de la sécurité actuelle  
- **Hébergement local** : Hébergement local du serveur avec une gestion limitée de la maintenance, notamment en raison du manque de temps.  

#### Mise en place de policies AWS personnalisées  
Création de **policies AWS** personnalisées pour restreindre les droits d'accès au strict nécessaire, afin de renforcer la sécurité.  

### Compétences associées  
- **Évaluation de la sécurité existante des systèmes et réseaux informatiques**  
- **Mise en place du plan de veille de sécurité des systèmes et réseaux informatiques**  
- **Construction de la politique de sécurité des systèmes et réseaux informatiques**  
- **Implémentation des solutions de sécurité des systèmes et réseaux informatiques**  
- **Détection des incidents de sécurité de l’infrastructure informatique**  
- **Gestion des incidents de sécurité de l’infrastructure informatique**  
- **Évolution de la politique et des solutions de sécurité de l’infrastructure informatique**  

---

## A4 : Management de l’équipe du projet d’architecture informatique  

### Définir les besoins de compétences pour la nouvelle infrastructure  
Identifications des compétences nécessaires pour la mise en place et la gestion de la nouvelle infrastructure :  
- **Prestataire DevOps** : Expertise en DevOps pour gérer l'infrastructure.  
- **Montée en compétences des collaborateurs** : Formation des collaborateurs internes pour s'assurer qu'ils puissent gérer l'infrastructure AWS à long terme.  

### Communication avec les collaborateurs  
Planification de réunions et envoi de communications régulières pour tenir les collaborateurs informés de l'avancement du projet, des objectifs et des changements apportés :  
- **Réunions** : Planification des réunions pour discuter des étapes du projet.  
- **Mails** : Envoi de mails pour informer des progrès et des points clés.  

### Compétences associées  
- **Définition des besoins en compétences de l’équipe du projet d’architecture informatique**  
- **Création de l’équipe du projet d’architecture informatique**  
- **Gestion opérationnelle de l’équipe du projet d’architecture informatique**  
- **Animation de l’équipe du projet d’architecture informatique**  
- **Plan de formation de l’équipe du projet d’architecture informatique**  
- **Suivi de la performance de l’équipe du projet d’architecture informatique**  
