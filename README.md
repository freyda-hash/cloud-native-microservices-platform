# cloud-native-microservices-platform

Projet de plateforme cloud-native pour une boutique en ligne basée sur une architecture microservices.

## Objectif
Déployer et gérer une application distribuée avec Kubernetes en utilisant Helm, ArgoCD et GitOps pour une livraison continue fiable.

## Ce que j’ai réalisé
- Conception d’un environnement Kubernetes local avec Kind
- Packaging d’applications microservices avec Helm charts
- Gestion des applications via ArgoCD pour le déploiement GitOps
- Configuration de services cloud-native : frontend, catalogue, panier, commande, paiement, recommandation, monnaie, publicité, e-mail, expédition
- Utilisation de `helm-values/` pour séparer les valeurs de configuration par service
- Prise en charge de services d’infrastructure (Redis) et de namespaces automatisés

## Structure
- `argocd/` : applications ArgoCD par service
- `charts/` : Helm chart partagé pour les microservices
- `helm-values/` : fichiers de valeurs Helm par service
- `kustomize/` : manifests Kubernetes personnalisés
- `manifests/` : manifests de base pour les composants d’infrastructure
- `kind-config.yaml` : configuration du cluster Kind

## Compétences démontrées
Kubernetes, Helm, ArgoCD, GitOps, architecture microservices, déploiement cloud-native, automatisation des releases.
