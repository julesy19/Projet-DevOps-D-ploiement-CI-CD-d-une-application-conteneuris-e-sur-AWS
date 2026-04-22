# 🚀 Babo App – Déploiement CI/CD avec Docker et AWS

## 📌 Description
Babo App est une application web développée avec Flask, conteneurisée avec Docker et déployée automatiquement sur AWS via un pipeline CI/CD.

Ce projet illustre la mise en place d’un workflow DevOps complet, depuis le développement local jusqu’au déploiement dans le cloud.

---

## 🛠️ Technologies utilisées

- Python (Flask)
- Docker
- Git & GitHub
- GitHub Actions (CI/CD)
- AWS (ECR, ECS Fargate)
- Gunicorn

---

## ⚙️ Fonctionnalités

- Application web simple avec Flask
- Conteneurisation avec Docker
- Build automatique de l’image Docker
- Push vers Amazon ECR
- Déploiement automatique sur Amazon ECS
- Gestion des logs et debugging (Gunicorn, réseau, ports)

---

## 🐳 Exécution en local

### 1. Cloner le projet
```bash
git clone https://github.com/TON-USERNAME/babo-app.git
cd babo-app
