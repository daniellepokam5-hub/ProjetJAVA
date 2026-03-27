# ☕ Java MySQL Connection Project

## 📌 Description

Ce projet Java a pour objectif de démontrer comment établir une connexion entre une application Java et une base de données **MySQL (Navicat)**.

Il met en pratique :

* La configuration d’un connecteur JDBC
* La connexion à une base de données locale
* L’exécution de requêtes SQL simples

---

## 🛠 Technologies utilisées

* **Java (JDK 17)**
* **Eclipse IDE (version 17)**
* **MySQL Server**
* **Navicat for MySQL**
* **JDBC Driver : mysql-connector-j-9.6.0.jar**

---

## ⚙️ Installation et configuration

### 1. Prérequis

Avant de lancer le projet, assurez-vous d’avoir :

* Java JDK 17 installé
* Eclipse IDE configuré
* MySQL installé et en cours d’exécution
* Navicat (optionnel, pour gérer la base)

---

### 2. Configuration du connecteur JDBC

1. Télécharger le driver :

   * `mysql-connector-j-9.6.0.jar`

2. Dans Eclipse :

   * Clic droit sur le projet → **Build Path**
   * **Add External JARs**
   * Ajouter le fichier `.jar`

---

### 3. Configuration de la base de données

Créer une base de données (ex : `CinemaDB`) dans MySQL/Navicat.

Exemple :

```sql
CREATE DATABASE CinemaDB;
```
<img width="1117" height="475" alt="image" src="https://github.com/user-attachments/assets/91839cc3-4f36-47fc-ad89-3af61463f2bb" />

## ❗ Problème rencontré

Lors du développement, un problème de compatibilité est apparu avec le driver :

* ❌ `mysql-connector-5.0.5-bin.jar` → **incompatible avec Eclipse 17 / Java 17**
* ✅ Solution : utiliser **`mysql-connector-j-9.6.0.jar`**

---
<img width="1473" height="877" alt="image" src="https://github.com/user-attachments/assets/62c4d071-161b-4eb6-a1e7-974ddf834593" />

## 🎯 Ce que j’ai appris

* Comprendre le rôle des drivers JDBC
* Gérer les problèmes de compatibilité entre versions
* Configurer correctement un projet Java avec une base de données
* Diagnostiquer et résoudre des erreurs techniques
## 👨‍💻 Auteur

Projet réalisé dans le cadre d’apprentissage du développement Java et des bases de données.

