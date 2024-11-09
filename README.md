#Déploiement d'une VM Azure avec Load Balancer et Autoscaling
##Introduction
Ce projet automatise le déploiement de deux machines virtuelles (VM) avec un Load Balancer Azure et des capacités d'autoscaling. 
La configuration est gérée via des pipelines Azure DevOps et le code est stocké sur GitHub.
L'infrastructure est déployée à l'aide de modèles ARM, et les secrets sont stockés en toute sécurité dans Azure Key Vault.
##Objectifs du projet
L'objectif est de déployer une infrastructure évolutive avec des machines virtuelles Azure,
un équilibrage de charge et un scaling automatique basé sur l'utilisation du CPU. 
Le projet utilise Azure DevOps pour les pipelines CI/CD et Azure Key Vault pour la gestion des secrets.
##Structure du projet
Le dépôt contient les fichiers suivants :
- **Modèles ARM** pour le déploiement de l'infrastructure (VM, Load Balancer, etc.)
- **Script PowerShell (PS1)** pour l'initialisation de l'environnement
- **Fichiers YAML** pour les pipelines DevOps (CI/CD)
- **Fichiers JSON** pour les paramètres de déploiement et la configuration

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
