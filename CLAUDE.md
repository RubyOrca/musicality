# 🎹 Projet : L'Odyssée des Notes Magiques
> **Concept :** Jeu vidéo éducatif 2D pour apprendre les bases du piano.
> **Public cible :** Enfants de 6 ans (CP / 1ère Primaire).
> **Objectif :** Associer les touches du piano aux sons et apprendre "Au Clair de la Lune".

---

## 🎨 1. Univers Visuel et Narration
* **Le Héros :** "Octave", un petit chat mélomane qui a perdu ses couleurs.
* **L'Histoire :** Pour redonner des couleurs au monde d'Octave, l'enfant doit retrouver les "Pierres de Notes" en jouant les bonnes touches.
* **Code Couleur (Standard International) :**
    - **DO** : Rouge 🔴
    - **RÉ** : Orange 🟠
    - **MI** : Jaune 🟡
    - **FA** : Vert 🟢
    - **SOL** : Bleu 🔵
    - **LA** : Violet 🟣
    - **SI** : Rose 💗

---

## 🕹️ 2. Mécaniques de Jeu (Gameplay)

### Niveau 1 : La Chasse aux Touches (Apprentissage)
- **Écran :** Un clavier de piano s'affiche en bas. Des bulles colorées tombent du ciel.
- **Action :** L'enfant doit cliquer sur la touche correspondante (ou appuyer sur une touche du clavier MIDI/PC) quand la bulle touche le clavier.
- **Apprentissage :** Identification visuelle du groupe de "2 touches noires" pour repérer le **DO**.

### Niveau 2 : Le Chant des Étoiles (Mémorisation)
- **Écran :** Octave saute de plateforme en plateforme. Chaque plateforme est une note.
- **Action :** Le jeu joue un son (ex: SOL). L'enfant doit cliquer sur la bonne note pour faire sauter Octave. S'il réussit, la plateforme s'illumine de sa couleur.

### Niveau 3 : Le Grand Concert (Mélodie)
- **Objectif :** Jouer "Au Clair de la Lune".
- **Interface :** Une partition simplifiée défile (type *Guitar Hero* mais très lent).
- **Partition Visuelle :**
    1. 🔴 🔴 🔴 🟠 | 🟡 (pause) 🟠
    2. 🔴 🟡 🟠 🟠 | 🔴 (fin)

---

## 🛠️ 3. Spécifications Techniques (Pour le développement)

### Assets nécessaires :
- **Sons :** Échantillons de piano propre (format .wav) pour chaque note (Do3 à Do4).
- **Visuels :** - Sprite "Clavier" avec touches interactives.
    - Animation du personnage "Octave".
    - Fond d'écran évolutif (du gris vers la couleur).

### Logique de contrôle :
- **Input Souris/Tactile :** Clic direct sur les touches à l'écran.
- **Input Clavier PC :** Touches `A, S, D, F, G, H, J` mappées sur `Do, Ré, Mi, Fa, Sol, La, Si`.
- **Option MIDI :** Support des claviers maîtres USB pour une expérience réelle.

---

## 📈 4. Progression Pédagogique
1.  **Découverte :** On explore le son de chaque touche librement.
2.  **Association :** On lie le nom de la note (écrit en gros) à sa couleur et son emplacement.
3.  **Rythme :** On apprend à tenir une note longue vs une note courte (symbolisé par la taille des bulles).
4.  **Récompense :** À la fin de la mélodie, une animation festive se déclenche et Octave récupère son chapeau de magicien.

---

## 📝 5. Guide pour l'Enfant (À lire par le parent)
*"Bienvenue dans le monde d'Octave ! Pour aider ton ami, regarde bien les deux touches noires sur le piano. Juste à côté, c'est la maison du Dragon Rouge (le DO). Appuie dessus pour commencer l'aventure !"*

---
*Fichier généré pour la conception d'un outil d'éveil musical ludique.*