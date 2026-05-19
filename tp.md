# TP mise en pratique

## Organisation

Durée : **3 demi-journées**  
Format : **travail en groupe**  
Objectif : **concevoir, développer et livrer un mini-projet applicatif en respectant Scrum**

Chaque groupe choisit librement son projet, à condition qu’il soit réalisable en 3 demi-journées.


## Equipes

Travail en équipe obligatoire. Voici la composition :

### Equipe 1 (https://github.com/ArthurPoncin/agile-devops-tp)
- Nathan (PO)
- Jihad (SM)
- Thomas (abs)
- Aurélien
- Arthur

### Equipe 2 (LIEN_GITHUB)
- Habibou
- Quentin
- Thibault
- Fatoumata
- Anass
- Youssef

### Equipe 3 (LIEN_GITHUB)
- Eliott
- Timeo
- Wessim
- Loric
- Jordan

### Equipe 4 (https://github.com/KillianGascon/Agilit--GestionEvents)
- Pierre (PO)
- Killian (SM)
- Alexandre
- Fiona
- Alexis

### Equipe 5 (https://github.com/Sblaaaf/DEVIA-AGILE-GR5)
- Renaud (PO)
- Théo (SM)
- Matthieu
- Martin
- Foidjou

## 🎯 Objectif du TP

Mettre en pratique la méthodologie **Scrum** à travers la réalisation d’un **projet de développement libre**.

Le but principal n’est pas de produire une application parfaite.

Le but est de :

- respecter Scrum
- produire des livrables propres
- travailler en équipe
- versionner le travail
- livrer une démo fonctionnelle
- justifier ses choix techniques


## 🎬 Contexte

Vous êtes une équipe de développement.

Votre mission est de concevoir et développer un mini-projet applicatif libre.

Exemples possibles :

- application de gestion de tâches
- mini CRM
- plateforme de réservation
- application de quiz
- dashboard météo / finance / statistiques
- outil de génération de contenu
- mini e-commerce
- application de gestion d’événements
- API REST avec interface front
- application SaaS simplifiée
- outil interne pour une entreprise fictive

Le formateur joue le rôle du **client**.

Le client (moi 😇) pourra :

- modifier une priorité
- ajouter une contrainte
- demander une nouvelle fonctionnalité
- refuser une fonctionnalité mal comprise
- demander une démo à tout moment

## Attribution des rôles :

Chaque équipe doit attribuer les rôles suivants :

### Product Owner

Responsable de :

- comprendre le besoin
- prioriser les User Stories
- valider les fonctionnalités
- présenter l’avancement au client

### Scrum Master

Responsable de :

- organiser les cérémonies Scrum
- suivre les blocages
- vérifier que la méthode est respectée
- maintenir la traçabilité des comptes rendus

### Dev Team

Responsable de :

- concevoir
- développer
- tester
- documenter
- livrer

Un étudiant peut aider sur plusieurs responsabilités, mais les rôles doivent être clairement identifiés.

## 2. Choix du projet

Chaque équipe choisit un projet libre.

Le projet doit être :

- suffisamment simple pour être commencé rapidement
- suffisamment riche pour générer plusieurs User Stories
- démontrable à la fin
- réalisable en groupe
- découpable en plusieurs sprints courts

## Fiche projet à produire

Chaque groupe doit rédiger une courte fiche projet :

```md
# Nom du projet

## Description courte

## Problème résolu

## Utilisateurs cibles

## Fonctionnalités principales envisagées

## Stack technique choisie

## Contraintes identifiées

## Risques techniques
```

## Construction du Product Backlog

⚠️ tous les backlogs doivent être obligatoirement sur github project ! Attention à bien mettre vos repo en publics.

Chaque équipe doit créer un Product Backlog complet.

📌 User Stories en respectant le format:

```
En tant que …
Je veux …
Afin de …
```

Exemple :

```
En tant qu’utilisateur,
je veux créer un compte,
afin d’accéder à mon espace personnel.
```

Chaque User Story doit contenir :

- Conditions de validation
- Cas fonctionnels

## 📌 Definition of Ready (DoR)

Une User Story est prête si :

- elle est compréhensible par toute l’équipe
- elle est estimable
- elle est testable
- les critères d’acceptation sont définis
- elle est suffisamment petite pour être traitée dans un sprint
- les dépendances sont identifiées
- le PO l’a validée

## 📌 Definition of Done (DoD)

Une tâche est terminée si :

- le développement est terminé
- le code est versionné sur Git
- la fonctionnalité est testée
- les critères d’acceptation sont validés
- aucune erreur bloquante n’est connue
- le README ou la documentation est mis à jour si nécessaire
- la fonctionnalité est démontrable
- le PO l’a validée


## 4️⃣ Estimation (Planning Poker)

Chaque équipe estime les User Stories avec la suite de Fibonacci :

👉 1 – 1 – 2 – 3 – 5 – 8 – 13 – 21 - 34 - 55 - 89

Objectif

- estimer la complexité
- discuter les écarts de compréhension
- aligner l’équipe
- prioriser correctement
- éviter les User Stories trop grosses

> Une User Story estimée à 21 ou plus doit être redécoupée.

# Demi-journée 1 — Cadrage + Sprint 1

## Objectifs

- constituer les équipes
- choisir le projet
- définir le MVP
- créer le Product Backlog
- lancer le premier sprint
- produire une première base technique fonctionnelle

### Étape 1 — Création des équipes

À produire :

- composition du groupe
- rôle de chaque membre
- lien GitHub public

### Étape 2 — Cadrage du projet

À produire :

- fiche projet
- questions / réponses client
- périmètre du MVP
- stack choisie
- risques identifiés

### Étape 3 — Product Backlog initial

À produire :

- minimum 8 User Stories
- priorisation
- critères d’acceptation
- estimation initiale
- découpage en sprints

### Étape 4 — Sprint Planning 1

Chaque équipe définit :

- Sprint Goal
- User Stories sélectionnées
- Sprint Backlog
- tâches techniques
- répartition du travail
- Exemple de Sprint Goal

Mettre en place la structure du projet et livrer une première fonctionnalité démontrable.

### Étape 5 — Sprint 1

Travaux possibles :

- initialisation du projet
- création du repository Git
- choix de l’architecture
- mise en place front / back / base de données
- première fonctionnalité simple
- première route API
- première page fonctionnelle
- README initial

Étape 6 — Daily Scrum

Même sur une demi-journée, un point rapide est obligatoire.

Chaque membre répond :

### Daily Scrum — Sprint 1

#### Membre 1

- Ce que j’ai fait :
- Ce que je vais faire :
- Mes blocages :

#### Membre 2

- Ce que j’ai fait :
- Ce que je vais faire :
- Mes blocages :

etc...

## Étape 7 — Sprint Review 1

À produire :

### Sprint Review 1

#### Sprint Goal

...

#### Fonctionnalités terminées

- 
- 

#### Fonctionnalités non terminées

- 

#### Démo réalisée

Oui / Non

#### Feedback du client

- 

#### Décisions prises

- 

## Étape 8 — Sprint Retrospective 1

Format obligatoire :

### Rétrospective Sprint 1

#### Keep

- 

#### Drop

- 

#### Try

- 




## Pour les sprints suivants : répliquez !