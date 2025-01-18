---
tags :
  - projet
  - robot
  - arduino
---



# Bras robot qui joue au echec

## 1. Bras robot 6 axes


J’ai réalisé un bras robotique à 6 axes basé sur le modèle open source WE-R2.4 Six Axis Robot Arm, trouvé en ligne. J’ai choisi ce projet pour recréer un modèle miniature inspiré des bras industriels que j’ai observés pendant mon stage en entreprise.

Aspects techniques du projet
Structure et fabrication :

La structure du bras a été imprimée en 3D, principalement en PLA, pour créer des pièces légères et résistantes.
Le design inclut une base rotative et des articulations modulaires, reproduisant les mouvements complexes des bras industriels.
L’assemblage demandait une grande précision, notamment pour garantir l’ajustement des engrenages et des supports de moteur.
Électronique et contrôle :

J’ai utilisé une carte Arduino Uno couplée à une carte CNC Shield pour gérer les moteurs pas à pas.
Les moteurs pas à pas assurent une grande précision grâce au contrôle par micro-pas.
Cependant, j’ai rencontré des problèmes sur les trois derniers axes : les moteurs utilisés étaient de qualité inférieure, avec des axes lisses, ce qui causait des glissements et réduisait la fiabilité des mouvements.
Programmation :

Le contrôle du bras repose sur un code Arduino, utilisant des bibliothèques pour synchroniser les moteurs. J’ai appris à gérer des séquences de mouvement complexes et à ajuster les vitesses pour éviter les collisions.
J’ai également expérimenté des contrôles manuels via un joystick pour tester la réactivité en temps réel.
Ce que j’ai appris
Ce projet m’a permis d’acquérir de nouvelles compétences et de renforcer mes connaissances :

Impression 3D : J’ai appris à optimiser la conception et les paramètres d’impression pour obtenir des pièces précises et fonctionnelles.
Électronique : La configuration des moteurs pas à pas, l’utilisation de la carte CNC et l’intégration de l’Arduino m’ont donné une base solide en robotique.
Programmation : J’ai développé des compétences en contrôle moteur, gestion de mouvements synchronisés et optimisation des performances du système.
Résolution de problèmes : Les difficultés liées aux moteurs de faible qualité m’ont appris à diagnostiquer et corriger des problèmes mécaniques et électroniques.
Conclusion
Ce projet, qui a pris 2 ans à réaliser, m’a permis de reproduire en miniature le fonctionnement des bras industriels. Malgré les défis rencontrés, notamment avec les moteurs, j’ai réussi à créer un système fonctionnel et polyvalent. Si je devais refaire ce projet, j’investirais dans des moteurs de meilleure qualité et des couplesurs adaptés pour améliorer la fiabilité et la précision des mouvements.



### Video test bras robot

<iframe width="560" height="315" src="https://www.youtube.com/embed/7l4egNXn1Wg?si=j_Jjd0feub_97iSB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Video avec Logiciel de controle du bras robot

<iframe width="560" height="315" src="https://www.youtube.com/embed/ky7fsqnJq0o?si=hvbOnP_kcds6W_dR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## 2. Bras robot 4 axes

![setup1](images/robot_arm_V2.1.jpg){ width="300"}

