# Mon Application Sudoku Interactive

Une application web interactive de Sudoku conçue pour créer, remplir et tester des grilles librement directement depuis votre navigateur. Développée dans le cadre de projets de création de contenu et de résolution de puzzles en vidéo.

## Fonctionnalités principales

L'application intègre toutes les fonctionnalités nécessaires pour poser et résoudre vos grilles :
* **Grille interactive 9x9** : Navigation fluide et sélection intuitive des cases.
* **Pavé numérique et modes multiples** :
  * **Mode Chiffre** : Pour placer les solutions ou les chiffres initiaux.
  * **Mode Notes Centrales** : Pour placer des chiffres temporaires au centre de la case.
  * **Mode Notes de Coin** : Pour placer des candidats dans les coins de la case (les notes centrales et de coin peuvent cohabiter et s'effacent automatiquement lorsqu'un chiffre définitif est placé).
  * **Mode Couleurs** : Permet de basculer le pavé en 9 couleurs pour surligner vos cases.
* **Gestion intelligente (Bouton Poubelle)** : Supprime uniquement les données du mode sélectionné (ou nettoie toute la case si aucune donnée active n'est ciblée).
* **Verrouillage (Bouton Cadenas)** : Permet de verrouiller les chiffres de départ pour créer votre propre grille personnalisée (les chiffres verrouillés deviennent noirs et insupprimables, tandis que les chiffres saisis ensuite s'affichent dans une autre couleur).
* **Historique complet (Undo / Redo)** : Boutons Annuler et Rétablir (similaires à `Ctrl+Z` et `Ctrl+Y`).
* **Contrôles rapides** : Bouton de réinitialisation totale (*Reset*) et fonction de vérification (*Check*).
