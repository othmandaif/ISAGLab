# ISAGlab

![Uploading logo.png…]()

isagLab est une application de bureau qui permet d'écrire et d'exécuter des algorithmes en pseudo-code, dans la syntaxe francophone classique enseignée dans les filières informatiques (Algorithme / Début / Fin, Variable, Pour...Faire, Tant que, Si...Alors...Sinon, etc.).

L'objectif est simple : offrir aux étudiants un outil léger pour tester leurs algorithmes sans avoir à apprendre un vrai langage de programmation au préalable. On écrit l'algorithme comme on l'apprend en cours, on l'exécute, et on voit directement le résultat.

## Pourquoi ce projet

Beaucoup d'étudiants qui débutent en algorithmique ont du mal à faire le lien entre ce qu'ils écrivent sur papier et un programme qui tourne réellement. isagLab comble cet écart : le pseudo-code n'est plus seulement une étape avant le "vrai" code, il devient exécutable, avec des retours immédiats en cas d'erreur de logique ou de syntaxe.

Ce projet a été développé dans le cadre de la formation à l'**ISTA Arts Graphiques de Casablanca**, par **Othmane Daif**.

## Aperçu

<img width="1920" height="1131" alt="image" src="https://github.com/user-attachments/assets/4fab17ec-b686-4e7e-8177-cd797b59e69d" />

<img width="1920" height="1121" alt="image" src="https://github.com/user-attachments/assets/aa59107d-920a-4700-8255-cb30e241a106" />

<img width="1920" height="1123" alt="image" src="https://github.com/user-attachments/assets/343915f8-5e50-4115-b0e3-b9fa776de58f" />

<img width="1920" height="1130" alt="image" src="https://github.com/user-attachments/assets/2ac58bf4-4d58-4bec-b7d3-89218eef84de" />

## Fonctionnalités

- Éditeur dédié à l'écriture de pseudo-code, avec coloration syntaxique
- Exécution pas à pas ou complète de l'algorithme
- Affichage clair des résultats et des erreurs (syntaxe, logique, types)
- Prise en charge des structures de base : conditions, boucles, tableaux, fonctions/procédures
- Interface simple, pensée pour des débutants, sans configuration à faire

## Installation

isagLab est disponible pour Windows.

1. Allez dans la section [Releases](../../releases) de ce dépôt
2. Téléchargez le fichier `isagLab-Setup.exe` de la dernière version
3. Lancez l'installateur et suivez les instructions
4. Une fois installé, lancez isagLab depuis le menu Démarrer ou le raccourci sur le bureau

Aucune dépendance à installer séparément, tout est inclus dans l'installateur.

## Exemple rapide

Voici à quoi ressemble un algorithme simple dans isagLab :

```
Algorithme CalculMoyenne
Variables
    note1, note2, note3, moyenne : réel
Début
    Ecrire("Entrez trois notes :")
    Lire(note1)
    Lire(note2)
    Lire(note3)
    moyenne <- (note1 + note2 + note3) / 3
    Ecrire("La moyenne est : ", moyenne)
Fin
```

## Technologies utilisées

isagLab est développé en Python. L'interface graphique et le moteur d'interprétation du pseudo-code ont été construits spécifiquement pour ce projet.

## Public visé

Cet outil s'adresse principalement aux étudiants qui découvrent l'algorithmique, ainsi qu'aux formateurs qui souhaitent illustrer des concepts en cours sans passer par un vrai langage de programmation. Il peut aussi servir de support de révision avant un module de programmation.

## Contribuer / signaler un problème

Le projet est encore en évolution. Si vous rencontrez un bug, si une fonctionnalité vous manque, ou si vous avez une suggestion, n'hésitez pas à ouvrir une [issue](../../issues). Les retours des étudiants et formateurs sont les bienvenus, c'est aussi comme ça que l'outil s'améliore.

## Licence

Ce projet est distribué sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Auteur

**Othmane Daif**
Développé au sein de l'ISTA Arts Graphiques de Casablanca.
