# LAMA - Laser Anti Moustique Autonome

## Description

LAMA (**Laser Anti Moustique Autonome**) est un projet personnel qui vise à développer mes compétences en Arduino et imagerie numérique autour d'un projet fun et UTILE. L'objectif du projet LAMA est de créer un système autonome pour détecter, viser et traiter les moustiques avec un tir laser.

## Fonctionnalités principales

- **Détection avancée** : Utilisation d'algorithmes de traitement de l'image pour détecter des moustiques dans un espace
- **Neutralisation ciblée** : Émission de lasers précis pour éliminer les nuisibles tout en respectant l'environnement.
- **Autonomie complète** : Fonctionnement sans supervision humaine.

> Noter que ce projet n'a pas pour objectif d'être réutilisé à des fins militaires ou autre contexte pouvant amener à des situations dangeureuses pour des êtres humains.

## Utilisation prévue

1. Positionnez le système LAMA dans la zone ciblée.
2. Allumez l'appareil.
3. Laissez LAMA opérer en toute autonomie.

> Il s'agit de l'objectif final, l'utilisation va peut-être changer en fonction des différentes contraintes techniques rencontrées au cours du projet

## Liste du matériel

La liste de matériel est vouée à changer au cours de l'évolution du projet

1. Capteur ultrason HC-SR04
2. Board Arduino
3. Servo moteur
4. Laser (à benchmarker)
5. Système de visée pour le laser (également à benchmarker)

## Différentes étapes du projet

1. Réaliser un sonar rotatif via le capteur HC-SR04
    - **1 :** Mode Statique
    - **2 :** Mode rotatif
    - **3 :** Suivi de cible
        > transfert de données entre le capteur et le servo pour garder la cible au centre du champs de vision

2. Tester le tir de précision avec un laser pour des cibles immobiles

    > L'idée c'est de donner des coordonnées au laser pour qu'il puisse s'orienter et tirer

3. Envoi de coordonnées entre le sonar rotatif et le laser

    > Transformer les données du sonar en coordonées pour les envoyer au laser
