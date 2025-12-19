# 🔁 HFSQL Backup & Replication Tool

## 📌 Description

**HFSQL Backup & Replication Tool** est un petit programme utilitaire développé sous **WINDEV** permettant d’effectuer la **sauvegarde et la réplication de bases de données HFSQL** de manière **programmée, fiable et sécurisée**.

La réplication s’effectue **par programmation**, en s’appuyant sur les **fonctions natives de sauvegarde et de restauration HyperFileSQL (HFSQL)** en mode Client/Serveur.

Cet outil vise à simplifier la gestion des sauvegardes et à réduire les risques de perte de données.

---

## 🛠️ Fonctionnalités

- Connexion au **serveur HFSQL source**
- Connexion au **serveur HFSQL de réplication**
- Sauvegarde complète d’une base HFSQL
- Restauration automatique sur le serveur cible
- Duplication avec **nouveau nom de base**
- Option de **suppression automatique de la base cible si elle existe**
- Test de connectivité (source et réplication)
- Interface graphique simple et intuitive

---

## 🧩 Principe de fonctionnement

1. Connexion au serveur HFSQL source
2. Sauvegarde programmée de la base via les fonctions HFSQL
3. Stockage temporaire de la sauvegarde
4. Connexion au serveur HFSQL de réplication
5. Restauration automatique de la base
6. Nettoyage selon les options choisies

> ⚠️ Toutes les opérations sont effectuées **sans manipulation manuelle des fichiers physiques** de la base.

---

## 🖥️ Technologies utilisées

- **WINDEV**
- **HFSQL Client/Serveur**
- Fonctions natives HFSQL :
  - Sauvegarde de base
  - Restauration de sauvegarde
  - Connexion serveur par programmation

---

## 📷 Capture d’écran

Interface principale du programme :

<img width="536" height="519" alt="Capture d&#39;écran 2025-12-19 082109" src="https://github.com/user-attachments/assets/353bcad5-0434-4f08-be13-953e49af232e" />


---

## ⚙️ Configuration requise

- Serveur **HFSQL Client/Serveur**
- Accès réseau entre les serveurs
- Droits administrateur HFSQL
- Environnement **WINDEV** pour compilation ou modification

---

## 🚀 Cas d’utilisation

- Sauvegarde quotidienne automatisée
- Réplication entre site principal et site secondaire
- Sécurisation avant maintenance ou mise à jour
- Duplication de base pour tests, formation ou audit

---

## 📄 Licence

Ce projet est distribué sous licence **MIT**.

Vous êtes libre de :
- utiliser le logiciel
- modifier le code source
- redistribuer le projet
- l’intégrer dans des projets personnels ou professionnels

Sous réserve de conserver la mention de l’auteur et de la licence.

Voir le fichier `LICENSE` pour plus de détails.

## 👤 Auteur

**Jonathan Kalema** 
Développeur Java et WINDEV/HFSQL  
Spécialiste en systèmes d’information de santé 
📍 Goma – République Démocratique du Congo

💡 Passionné par l’automatisation, la sécurisation des données et les solutions robustes en environnement contraint.


