---
title: Dtaxback
publishDate: 2023-08-18 15:00:00
img: /assets/dtaxback.jpg
img_alt: Icone d'application Dtaxback
description: |
  Stage chez Dtaxback pour leur application de détaxation fiscale en Flutter
tags:
  - Flutter
  - Angular
  - Firebase
  - Jira
  - Agile
---

## Développement d'une application mobile

### Contexte

Lors de l'été 2023, j'ai eu l'occasion de pouvoir réaliser un stage chez Dtaxback. Le but était d'aider l'équipe à avancer sur la conception de features et de régler les problèmes existants qui ont été remontés.

### La détaxe

Le principe est simple : toute personne réalisant des achats en France qui n'est pas résident européen à le droit de se faire rembourser la TVA sur ses achats.
L'application permet à l'utilisateur de rentrer ses factures et de générer à la fin de son voyage un bordereau de détaxation à présenter à la douane. S'il est validé, la somme est reversée à l'entreprise et la majeure partie du montant est remboursée à l'utilisateur.

### Missions

J'ai eu l'occasion de réaliser différente features aussi bien du côté application que pour le back-office. L'une d'elles consistait à implémenter la vérification des emails de nos utilisateurs, qui jusque-là pouvait s'enregistrer et utiliser l'application sans grandes restrictions. Je n'avais déjà pas beaucoup d'expérience en Flutter, il m'a fallu aussi apprendre à utiliser Firebase. J'ai tout de même réussi à l'implémenter et le résultat est tout à fait convenable. Suite à cela, il a fallu faire une petite refonte du comportement de la méthode de connexion/inscription de l'application.

Une fois que nous pouvions faire la différence entre les utilisateurs vérifiés et ceux qui ne le sont pas, j'ai mis en place une Cloud Function de mailing qui permet de notifier par mail les utilisateurs qui ont des documents (passeport et/ou preuve de résidence) qui sont sur le point de ne plus être à jour. Cette Cloud Function s'exécute chaque jour et envoie un mail de notification si le/les documents d'un ou plusieurs utilisateurs remplissent certaines conditions.

### Environnement

Ce fut aussi l'occasion pour moi d'expérimenter la méthode agile. Je n'en avais jamais vraiment eu l'occasion par le passé donc pour la 1re fois, j'ai utilisé Jira pour la répartition des tâches du sprint. Chaque matin, un "Daily call" était fait en petit comité pour savoir ce qui a été fait la veille et ce qu'il y a à faire pour la journée.

À chaque fin de sprint, une review était faite pour discuter de ce qui s'est bien passé ou non, ce qu'il est prévu de faire pour le prochain sprint avec un plan d'action sur lequel se tenir.