# Rocket Shooter

## Comment jouer 

### Le jeu
    Il s'agit d'un platformer ou le but est de parvenir à la fin du niveau en ayant récupéré toutes les clés et/ou détruit toutes les cibles.
    Pour ce faire, vous disposez d'une arme pouvant tirer deux projectiles : un attirant et un repoussant.

    Lancer le jeu à partir du niveau EmptyHUD.

    Bonne chance et bon amusement !

### Commandes Clavier Souris / Manette
    - Caméra : Souris / Stick droit
    - Déplacements : ZQSD / Stick gauche
    - Saut : Espace / Bouton du bas
    - Projectile repoussant : Clic gauche / Bouton de gauche
    - Projectile attirant : Clic droit / Bouton de droite
    - Recommencer : R / Bouton spécial gauche
    - Pause : P / Bouton spécial droit

    Les touches sont paramétrables (voir plus bas dans le menu d'options)

## Implémentation
    - Mécanique principale de tir avec deux projectiles

    - Clés à ramasser / Cibles à détruire
    - Zone de fin de niveau : passe au niveau suivant si toutes les clés sont collectées et cibles détruites (indication visuelle : rouge --> vert)
  
    - Plateforme mouvantes
        -> bouge si contact avec joueur
        -> bouge tout le temps

    - Piques / Murs rouges (mouvants ou pas) / Zone de mort --> tuent le joueur --> respawn du niveau
    
    - 1 Timer par niveau avec sauvegarde du meilleur temps

    - Maps :
        - Tutoriel
        - Level 1, explorant l'horizontalité du jeu
        - Level 2, explorant la verticalité du jeu
        - Level 3, besoin de précision (il est trop dur, Arnaud ne sait pas créer des niveaux faciles ;) )
        - Level 4, parcours avec chemin disparaissant
        - Level 5, niveau d'exploration
        - Level 6, niveau introduisant et exploitant les cibles

    - Audio : 
        Pickup des clés/cibles / Fin du niveau
        Musique menu / Musique Level + ajustement option

    - HUD : 
        - Timer par niveau / Crosshair (dans le niveau)
        - Menu principal 
        - Sélection de niveaux
        - Meilleurs temps par niveau
        - Menu de pause
        - Options :
            - Volume principal
            - Choix de fenêtrage (bug un peu)
            - Choix de résolution (bug un peu)
            - Choix de luminosité sur le niveau courant (pas sauvegardé)
            - Touches paramétrables

    - Trainée sur les missiles (niagara system) + Particules Explosion sur le tir repoussant


## Licences
    Crosshair : "https://www.flaticon.com/free-icons/crosshair" 
    Asset audio libre de droit (Interface & Item Sounds Pack)
    Musiques libres de droit

    Rocket Shooter © 2023 by TEISSANDIER Alban and GOETZ Arnaud is licensed under CC BY-NC-SA 4.0 


