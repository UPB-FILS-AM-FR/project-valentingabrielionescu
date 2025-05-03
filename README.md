# 🚦 Mini Feu de Signalisation Intelligent avec Arduino Uno

## Description du Projet

Ce projet simule un feu de signalisation intelligent à l'aide d'une carte Arduino Uno. Il automatise les cycles du feu tricolore pour les voitures (vert, jaune, rouge) et réagit lorsqu’un piéton appuie sur un bouton, arrêtant temporairement la circulation. Un buzzer indique qu’il est possible de traverser, et un écran LCD peut afficher des messages comme “Attendez...” ou “Traversez !”.

## Pourquoi ce Projet ?

- **Apprentissage pratique de l’Arduino** : Parfait pour débuter avec les composants électroniques de base et la programmation.
- **Simulation réaliste** : Ce projet reproduit un feu de circulation tel qu’on le voit dans la vie réelle.
- **Interaction utilisateur** : Le bouton simule la demande d’un piéton, introduisant la gestion des événements.
- **Facile à étendre** : Il est possible d’ajouter d’autres éléments (capteurs, Wi-Fi, plus de LEDs) pour améliorer le système.

## Principe de Fonctionnement

1. Le feu fonctionne en boucle avec les phases vert → jaune → rouge.
2. Lorsqu’un piéton appuie sur le bouton, le feu attend la fin du cycle puis passe au rouge.
3. Le feu piéton s’allume (LED verte), le buzzer émet un son, et l’écran LCD peut afficher "Traversez !".
4. Après un court délai, tout revient à la normale et le feu reprend son cycle automatique.

## Composants Utilisés

- 1× Arduino Uno  
- 1× Breadboard  
- 3× LEDs (rouge, jaune, vert) pour les voitures  
- 1× LED verte pour les piétons  
- 4× Résistances 220Ω (pour les LEDs)  
- 1× Bouton poussoir  
- 1× Résistance 10kΩ (pour le bouton)  
- 1× Buzzer  
- 1× Écran LCD 16x2 avec module I2C 
- Fils de connexion (jumper wires)  
- 1× Câble USB pour connecter l’Arduino

## Schéma de câblage

![Schéma de câblage](./schema.png)

## Références
[Tutoriel YouTube](https://www.youtube.com/watch?v=PYgPImkcu-Q&ab_channel=Asali)

 
