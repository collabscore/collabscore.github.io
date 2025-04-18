---
title: Annotateurs
layout: home
nav_order: 1
permalink: annotateur.html
---

# Présentation générale des tâches d'annotation

Chaque annotateur se voit attribuer des *tâches* 
à effectuer via des interfaces qui ont
en commun de présenter l'interprétation
de l'OMR et de permettre aux utilisateur d'effectuer
certaines corrections. Ces tâches s'effectuent
dans le cadre de campagnes déclenchées par les
administrateurs de CollabScore. 

## Les campagnes

Les tâches sont
distribuées par les administateurs de CollabScore
dans des *campagnes d'annotation* qui s'appliquent
à un ensemble d'œuvres. Un administrateur peut par
exemple lancer une campagne sur le corpus des mélodies
de C. Saint-Saëns, et impliquer un ensemble d'annotateurs
sur cette campagne. En général, une campagne de ce type
produira une tâche par œuvre, chaque tâche étant
affectée à un seul annotateur. 

Il existe cependant
d'autres possibilités: un administrateur peut créer
plusieuts tâches pour une même œuvre, de manière à 
pouvoir synthétiser les corrections faites 
par chaque annotateur. 

Il existe essentiellement trois types de campagnes, correspondant
à des tâches qui sont conçues pour se succéder
dans un ordre strict. Chaque tâche s'effectue à une 
certaine granularité (tout le document, ou seulement une
page, etc.), et concerne une partie des éléments
de la notation musicale. 

## La campagne d'instrumentation

La première est intitulée **"Instrumentation"**. Elle permet 
de vérifier que les parties instrumentales ont bien été identifiées,
et de s'assurer que chaque portée est bien affectée à la
bonne partie. Il s'agit d'une condition préalable à la
bonne interprétation du contenu musical. 
**[Cette campagne est décrite en détail ici]({% link pages/phase1.md %})**.
 
 
## La campagne des contextes de lecture

La seconde campagne porte sur le **contexte de lecture**. le but
est de vérifier la bonne reconnaissance des clés, armures et métriques.
Toute erreur sur l'un de ces éléments a en effet un impact
sur l'interprétation des symboles musicaux (notes, silences, etc.).
 **[Cette campagne est décrite en détail ici]({% link pages/phase2.md %})**.
 

## La campagne des objets musicaux

Enfin, en supposant les parties bien identifiées et localisées sur les portées (phase 1), et 
les éléments d'interprétation corrects (phase 2), 
la campagne de phase 3, intitulée **Objets musicaux**
propose  à l'utilisateur de corriger 
les éléments locaux.

  - Durée, hauteur, altération des notes
  - Durée des silences
  - Eventuellement ajout ou suppression d'éléments

**[Cette campagne est décrite en détail ici]({% link pages/phase3.md %})**.
 