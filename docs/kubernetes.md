# Fonctionnement de Kubernetes

- **Kubernetes** : plateforme open-source de gestion de conteneurs.
- **Objectif** : automatiser le déploiement, l'extensibilité et la gestion des applications conteneurisées.
- **Structure** : Organise les conteneurs en **pods** (groupes de conteneurs).
- **Fonctionnalités principales** :
  - Gestion du cycle de vie des conteneurs.
  - **Scaling automatique** et haute disponibilité.
  - **Équilibrage de charge**.
  - **Mises à jour continues** (rolling updates).
  - **Monitoring** et gestion des défaillances.
- **Composants principaux** :
  - **kube-apiserver** : gestion des requêtes API.
  - **kube-scheduler** : planification des pods sur les nœuds.
  - **kube-controller-manager** : gestion des ressources et maintien de l'état désiré.
