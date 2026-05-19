# TP mise en pratique

# Equipes

Travail en équipe obligatoire. Voici la composition :

## Equipe 1 (https://github.com/maximeraud/Agile_Kube)
- Kylian
- Maxime
- Elios
- Alexandre

## Equipe 2 (https://github.com/AnythingLegalConsidered/EPSI-B3-ASRBD-Agile-G2)
- Ianis
- Blaise
- Zaid
- Ojvind

## Equipe 3 (https://github.com/ewanlenogue/Agile_GRP_3)
- Ismaël
- Ewan
- Florent
- Ariel

# 🎯 Objectif du TP

Mettre en pratique la méthodologie Scrum à travers un projet Systèmes & Réseaux (Kubernetes).

👉 Le but principal n’est pas technique
👉 Le but est de respecter Scrum + produire les livrables

# 🎬 Contexte

Vous êtes une équipe DevOps.

Votre mission est de déployer une plateforme Kubernetes capable d’héberger :

- une application web
- une API
- des services exposés

⚠️ Le client (moi 😇) pourra modifier les besoins à tout moment.


# 1️⃣ Création des équipes

Groupes de 4 à 6 étudiants.

Attribution des rôles :

🧑‍💼 1 Product Owner
🧑‍🔧 1 Scrum Master
👨‍💻 Dev Team (reste du groupe)


# 2️⃣ Présentation du besoin

Le formateur joue le rôle du client.

👉 Les équipes doivent :

- Poser des questions
- Clarifier les besoins
- Identifier les premières fonctionnalités

## Questions & réponses :

Questions du 19/03 à 10h41 (groupe 1) :

- Quelles technologies ? Symfony & PHP en back, React en Front
- Quels ports ? allons-y pour le plus sécurisé tant qu'on peut avoir des certificats SSL
- Ai-je une IP dédiée ? oui j'en aurais une mais je ne la connais pas pour l'instant
- Combien d'utilisateurs ? 1.000 en simultané
- Est-ce que j'aurais besoin d'une partie de logs ? oui -> obligatoire !
- Besoins spécifiques par rapport aux logs ? non, pas à ma connaissance
- Besoin de monitoring ? oui si c'est une application avec une interface.
- Deadline pour la fin du projet ? le 8 Avril à 12h.
- Est-ce que l'application doit être consultable depuis l'extérieur ou uniquement en interne à une entreprise ? Extérieur !
- INFO : Pas d'image fournie, il faut prendre des images symfony + react existantes pour faire les tests.

# 3️⃣ Construction du Product Backlog

Les étudiants doivent produire :

📌 User Stories en respectant le format:

```
En tant que …
Je veux …
Afin de …
```

Exemples (Kubernetes)

- En tant qu’admin, je veux déployer un cluster Kubernetes afin d’héberger mes services
- En tant qu’utilisateur, je veux accéder à une application web exposée
- En tant qu’admin, je veux scaler les pods afin de gérer la charge

Chaque User Story doit contenir :

- Conditions de validation
- Cas fonctionnels

## 📌 Definition of Ready (DoR)

Une User Story est prête si :

- Compréhensible
- Estimable
- Testable
- Critères définis

## 📌 Definition of Done (DoD)

Une tâche est terminée si :

- Fonctionnelle
- Testée
- Déployée (Kubernetes)
- Documentée


# 4️⃣ Estimation (Planning Poker)

Chaque équipe estime les User Stories avec la suite de Fibonacci :

👉 1 – 1 – 2 – 3 – 5 – 8 – 13 – 21 - 34 - 55 - 89

Objectif

- Estimer la complexité
- Aligner l’équipe



# 5️⃣ Sprint 1 (0,5 jour)

## 🎯 Définition du Sprint Goal

Exemple :
👉 “Mettre en place un cluster Kubernetes fonctionnel et déployer une première application”

## 📌 Étapes

### 1. Sprint Planning

Sélection des User Stories

Création du Sprint Backlog

👉 ⚠️ Garder une trace (capture / outil)

### 2. Exécution du Sprint

Travaux possibles :

- Installation cluster (minikube / k3s)
- Déploiement Pod / Deployment
- Service simple

### 3. Daily Scrum (toutes les heures)

Chaque membre répond :

- Ce que j’ai fait
- Ce que je vais faire
- Mes blocages

👉 Compte rendu obligatoire

### 4. Sprint Review (15 minutes avant la fin du sprint)

Le PO présente le travail réalisé

Démo (si possible)

👉 Compte rendu obligatoire

### 5. Sprint Retrospective

Format :

✅ Keep
❌ Drop
🔁 Try

# 6️⃣ Sprint 2 (0,5 jour)

🎯 Sprint Goal (exemple)

👉 “Rendre les services accessibles depuis l’extérieur”

Travaux possibles :

- Service NodePort / LoadBalancer
- Ingress
- Tests d’accès

👉 Même organisation que Sprint 1

# 6️⃣ Sprint 3 (0,5 jour)

🎯 Sprint Goal (exemple)

👉 “Structurer et sécuriser l’infrastructure”

Travaux possibles :

- ConfigMap / Secret
- Segmentation logique
- Gestion des configs

👉 Même organisation

# 6️⃣ Sprint 4 (0,5 jour)

🎯 Sprint Goal (exemple)

👉 “Rendre la plateforme scalable et robuste”

Travaux possibles :

- Autoscaling (HPA)
- Résilience
- Monitoring (optionnel)

👉 Même organisation





# 📦 Livrables à rendre

## 📌 Product Backlog complet

- User Stories
- Critères d’acceptation
- Priorisation

## 📌 Pour chaque Sprint :

- Estimations (Planning Poker)
- Sprint Goal
- Sprint Backlog
- DoR & DoD
- Daily Scrum (comptes rendus)
- Review (compte rendu)
- Rétrospective

# ‼️ IMPORTANT ‼️

Chaque document doit être versionné sur GIT

Chaque livrable doit avoir une date claire

Le repository GIT sur lequel vous allez tout mettre doit être en public !

# 📧 Rendu

Envoyez moi le lien du repo GIT de votre groupe dans teams, dans la conversation de ce jour.
Deadline : je mettrais les notes sur les travaux rendus pour le dernier cours, avant l'heure de fin.

# Évaluation

- Qualité des livrables Scrum
- Respect de la méthodologie
- Traçabilité (Git)
- Cohérence des choix techniques
- Travail d’équipe