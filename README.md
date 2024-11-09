# Déploiement d'une VM Azure avec Load Balancer et Autoscaling

## Introduction
Ce projet automatise le déploiement de deux machines virtuelles (VM) avec un Load Balancer Azure et des capacités d'autoscaling. La configuration est gérée via des pipelines Azure DevOps et le code est stocké sur GitHub. L'infrastructure est déployée à l'aide de modèles ARM, et les secrets sont stockés en toute sécurité dans Azure Key Vault.

## Objectifs du projet
L'objectif est de déployer une infrastructure évolutive avec des machines virtuelles Azure, un équilibrage de charge et un scaling automatique basé sur l'utilisation du CPU. Le projet utilise Azure DevOps pour les pipelines CI/CD et Azure Key Vault pour la gestion des secrets.

## Structure du projet
Le dépôt contient les fichiers suivants :

- **Modèles ARM** pour le déploiement de l'infrastructure (VM, Load Balancer, etc.)
- **Script PowerShell (PS1)** pour l'initialisation de l'environnement
- **Fichiers YAML** pour les pipelines DevOps (CI/CD)
- **Fichiers JSON** pour les paramètres de déploiement et la configuration

### Étapes de déploiement
1. Clonez ce dépôt sur votre machine locale ou ouvrez-le directement dans GitHub.
2. Assurez-vous que les fichiers de configuration sont correctement définis pour votre environnement.
3. Configurez les pipelines CI/CD dans Azure DevOps en utilisant les fichiers YAML fournis.
4. Déployez l'infrastructure en exécutant les pipelines. Vous pouvez valider le déploiement en vérifiant que les machines virtuelles sont correctement provisionnées et que l'autoscaling fonctionne comme prévu.

## Conclusion
Ce projet fournit une solution complète pour déployer une infrastructure évolutive sur Azure avec des machines virtuelles, un Load Balancer, et un scaling automatique. Il utilise des pratiques modernes d'intégration et de déploiement continu avec Azure DevOps et GitHub, tout en garantissant la sécurité des secrets grâce à Azure Key Vault.

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
