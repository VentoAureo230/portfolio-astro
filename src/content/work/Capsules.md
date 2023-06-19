---
title: Capsules Pédagogique - Etayage
publishDate: 2023-02-28 15:00:00
img: /assets/capsule.jpg
img_alt: Image du site de capsules pédagogique
description: |
  Réalisation d'un site contenant des capsules pédagogique lors du stage de 2ème année pour Etayage.
tags:
  - PicoCMS
  - NextCloud
  - PhP
  - Twig
  - Documentation
---

## Développement d'une plateforme interne à l'entreprise

### Contexte

Mon stage a consisté essentiellement à la création de contenu pédagogique lors des 3 premières semaines de mon stage, pour alimenter le site et se faire un avis lors de la mise en commun du travail. 
À la suite de cela, le reste du stage visait à développer ce site en appréhendant les outils que l’on allait utiliser pour le mettre ligne.

### Les capsules

Les capsules pédagogiques sont des tutoriels qui couvrent un sujet en particulier. Nous avons co-écrit les tutoriels sur PhP et MySQL et j’ai personnellement rédigé celui de Symfony ainsi que celui de NextCloud. Axel a rédigé ceux sur Apache, l’introduction à l’installation d’un LAMP et Pico CMS.
L’idée derrière ces capsules est que chaque utilisateur qui les consulte puisse prendre en main rapidement la technologie, que ce soit de l’initiation à l’utilisation des outils ou bien l’installation sur un poste de travail. Ces tutoriels sont à destination des étudiants qui travaille à Etayage ou bien peuvent servir de support lors d’atelier pédagogique pour un client.
Rédiger ces tutoriels implique que l’on doit se mettre dans la peau du lecteur et de bien rendre explicites les procédures décrites en apportant des informations, des conseils et en la documentant visuellement avec des captures d’écran. Tout doit être fait rendre la lecture et l’apprentissage du sujet facile pour le lecteur.

Ayant rédigé certains tutoriels, je me suis aussi rendu compte que j’avais quelques lacunes techniques et la rédaction de ceux-là m’a permis de faire un point sur mes compétences et mon savoir pour mieux maîtriser ces technologies. J’ai aussi pu rencontrer quelques difficultés et c’est quelque chose que je peux préciser dans le tutoriel.

### Environnement

Cet environnement est basé sur NextCloud en utilisant Pico CMS pour la création du site web.

NextCloud est un logiciel libre de site d’hébergement de fichier et une plateforme de collaboration. On retrouve une bibliothèque d’application qui permet de personnaliser son NextCloud en fonction de ses besoins, et c’est Pico CMS qui va gérer la création de site.

Pour faire tourner NextCloud, il faut un serveur Apache et PhP sur sa machine Linux de préinstaller. On peut trouver une copie de l’application sur le site officiel de NextCloud, puis on configure un virtualhost avec Apache et une base de données avec MySQL ou MariaDB et une fois que tout est paramétré, on ouvre NextCloud à l’adresse de l’hôte et on termine l’installation depuis la page web.
