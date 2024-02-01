# **SnakeApp - Jeu de serpent en JavaFX par Surjoo Yogheshwar**

## Aperçu
SnakeApp est une application JavaFX qui implémente le jeu classique du serpent. Les joueurs contrôlent un serpent, évitant les collisions avec les bords de l'aire de jeu et leur propre corps tout en collectant des pixels rouges pour augmenter leur longueur.

## Fonctionnalités
- Contrôles directionnels à l'aide de boutons et de touches de clavier
- Aire de jeu délimitée par des bordures blanches
- Augmentation de la longueur du serpent lors de la collecte de pixels rouges
- Gestion des collisions avec les bords et le corps du serpent
- Affichage du score à la fin du jeu

## Comment jouer
- Utilisez les boutons directionnels sur le côté gauche de l'écran ou les touches fléchées du clavier pour déplacer le serpent.
- Évitez les bords de l'aire de jeu et les collisions avec votre propre corps.
- Collectez des pixels rouges pour augmenter votre score.

## Comment exécuter
1. Assurez-vous d'avoir Java installé sur votre système.
2. Compilez le code source à l'aide de la commande `javac SnakeApp.java`.
3. Exécutez l'application avec la commande `java SnakeApp`.

## Contrôles
- **Bouton Haut (Up):** Déplace le serpent vers le haut.
- **Bouton Bas (Down):** Déplace le serpent vers le bas.
- **Bouton Gauche (Left):** Déplace le serpent vers la gauche.
- **Bouton Droit (Right):** Déplace le serpent vers la droite.
- **Touches fléchées du clavier:** Même fonctionnalité que les boutons correspondants.

## Dépendances
- JavaFX : Utilisé pour la création de l'interface graphique.

## Remarques
- Le jeu utilise une boucle temporelle pour déplacer automatiquement le serpent à intervalles réguliers.
- Le score est basé sur la longueur du serpent.
- En cas de collision, le jeu affiche un message "Game Over" avec le score obtenu.

