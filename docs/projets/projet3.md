---
tags :
  - projet
  - robot
  - arduino
---



# Bras robot qui joue aux echecs

## 1. Bras robot 6 axes

### Présentation du projet
J’ai conçu un bras robotique à 6 axes inspiré du modèle open source [**WE-R2.4 Six Axis Robot Arm**](https://www.printables.com/model/132260-we-r24-six-axis-robot-arm). Ce projet visait à recréer un modèle miniature de bras industriels observés lors de mon stage en entreprise.

---

### Aspects techniques

#### Structure et fabrication
- Structure imprimée en 3D, principalement en **PLA**, pour allier légèreté et robustesse.  

#### Électronique et contrôle
- Utilisation d’une carte **Arduino Uno** et d’une carte **CNC Shield** pour piloter les moteurs pas à pas.  

#### Programmation
- Code Arduino avec des bibliothèques [AccelStepper](https://www.airspayce.com/mikem/arduino/AccelStepper/) pour synchroniser les moteurs et gérer des séquences de mouvements complexes.  
- Contrôlé avec un logiciel crée sur [Microsoft Visual Studio](https://visualstudio.microsoft.com/fr/)

---

### Compétences acquises

- Impression 3D : Optimisation des conceptions et des paramètres pour des pièces précises et fonctionnelles.
- Électronique : Configuration de moteurs pas à pas, utilisation de la carte CNC et intégration avec Arduino.
- Programmation : Développement d'une IHM (interface homme machine) pour contrôler le robot
- Résolution de problèmes : Diagnostic et correction de problèmes mécaniques et électroniques, notamment liés aux moteurs.
---

### Conclusion
Ce projet, réalisé sur **2 ans**, a permis de reproduire le fonctionnement des bras industriels à petite échelle. Malgré les défis techniques, j’ai créé un système fonctionnel.  

**À refaire :**  
J’investirais dans des moteurs de meilleure qualité. J'ajouterai des endstops pour améliorer le calibrage et la précision. Il faut revoir la conception 3D pour réduire les tremblements et améliorer la précision.




#### Video test bras robot

<iframe width="560" height="315" src="https://www.youtube.com/embed/7l4egNXn1Wg?si=j_Jjd0feub_97iSB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" style="border-radius:10px ; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);" allowfullscreen></iframe>

### Video avec Logiciel de controle du bras robot

<iframe width="560" height="315" src="https://www.youtube.com/embed/ky7fsqnJq0o?si=hvbOnP_kcds6W_dR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" style="border-radius:10px ; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);" allowfullscreen></iframe>


## 2. Bras robot 4 axes

![setup1](images/robot_arm_V2.1.jpg){ style="border-radius:10px ; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);" width="300"}

