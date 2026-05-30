# ⚔️ Arène Au Trésor

Un minuteur interactif pour le jeu d'animation **Arène Au Trésor**, inspiré de l'Index dans Warframe.

## 🎮 Présentation du jeu

Deux équipes s'affrontent — l'équipe **Rouge** et l'équipe **Bleue** — en ramassant des points sur le terrain et en les déposant dans une banque. Chaque dépôt influence le chronomètre et fait grimper le score de l'équipe.

- Durée d'un match : **5 à 10 minutes** (chrono initial : 5 min)
- L'équipe **Bleue** augmente le chrono en déposant des points (+10s par dépôt)
- L'équipe **Rouge** diminue le chrono en déposant des points (−10s par dépôt)

## 🏆 Conditions de victoire

Avant le match, choisir un objectif parmi **50 / 75 / 100 points**.

- La première équipe à atteindre l'objectif **gagne immédiatement**
- Si le chrono tombe à zéro, **l'équipe avec le plus de points gagne**

## ⚔️ Règle de combat

Lorsqu'un joueur touche un adversaire, celui-ci doit lui **remettre tous les points qu'il porte** sur lui. Il doit également retourner à la banque de son équipe pour recommencer à jouer. Ces points peuvent ensuite être déposés à la banque par le joueur qui les a récupérés.

## 💰 Système de points et bonus

Les points sont ramassés sur le terrain puis déposés à la banque. Plus un joueur dépose de points en une fois, plus il reçoit de bonus :

| Points déposés | Bonus | Total obtenu |
|:--------------:|:-----:|:------------:|
| 1              | +0    | 1            |
| 5              | +2    | 7            |
| 10             | +4    | 14           |
| 15             | +8    | 23           |
| 20+            | +10   | 30+          |

> Le bonus est plafonné à **+10** à partir de 20 points. Par exemple, déposer 35 points rapporte 35 + 10 = **45 points**.

## 🖥️ Utilisation du minuteur

1. Ouvrir `countdown.html` dans un navigateur
2. Choisir l'objectif de points (50 / 75 / 100)
3. Cliquer sur **Démarrer**
4. Saisir le nombre de points déposés dans le champ de l'équipe concernée
5. Cliquer sur **Déposer** — le score et le chrono se mettent à jour automatiquement
6. Le minuteur annonce le vainqueur dès qu'un objectif est atteint ou que le temps est écoulé
