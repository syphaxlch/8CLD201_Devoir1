# Déploiement d'une VM Azure avec Load Balancer et Autoscaling

## Introduction
Ce projet automatise le déploiement de deux machines virtuelles (VM) avec un Load Balancer Azure et des capacités d'autoscaling. La configuration est gérée via des pipelines Azure DevOps et le code est stocké sur GitHub. L'infrastructure est déployée à l'aide de modèles ARM, et les secrets sont stockés en toute sécurité dans Azure Key Vault.

## Objectifs du projet
L'objectif est de déployer une infrastructure évolutive avec des machines virtuelles Azure, un équilibrage de charge et un scaling automatique basé sur l'utilisation du CPU. Le projet utilise Azure DevOps pour les pipelines CI/CD et Azure Key Vault pour la gestion des secrets.

## 📸 Captures d’écran

Voici quelques captures pour illustrer les étapes et le résultat du déploiement :

### Pipeline Azure DevOps – Exécution réussie
<img src="https://github.com/user-attachments/assets/b1d8e4ea-f31d-4474-8ce9-00ddcf72fe9b" alt="Site Web Déployé" width="60%" />

### Machines virtuelles dans le portail Azure
<img src="https://github.com/user-attachments/assets/29e03cd1-5471-446f-bd8d-9f5843a39e60" alt="Site Web Déployé" width="60%" />

### Site Web déployé sur les machines virtuelles
<img src="https://github.com/user-attachments/assets/c81ae9f9-aa69-4d2c-80be-095052c625e9" alt="Site Web Déployé" width="60%" />

## Structure du projet
Le dépôt contient les fichiers suivants :

- **Modèles ARM** pour le déploiement de l'infrastructure (VM, Load Balancer, etc.)
- **Script PowerShell (PS1)** pour l'initialisation de l'environnement
- **Fichiers YAML** pour les pipelines DevOps (CI/CD)
- **Fichiers JSON** pour les paramètres de déploiement et la configuration

## Conclusion
Ce projet fournit une solution complète pour déployer une infrastructure évolutive sur Azure avec des machines virtuelles, un Load Balancer, et un scaling automatique. Il utilise des pratiques modernes d'intégration et de déploiement continu avec Azure DevOps et GitHub, tout en garantissant la sécurité des secrets grâce à Azure Key Vault.

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
