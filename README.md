# Architecture-des-ordinateurs
Projets réalisés en Automne 2022

Logiciel : MPLAB X IDE (v 5.35)

1. Système de contrôle pour un feu de circulation

•	Objectif : Concevoir un prototype fonctionnel pour un système de contrôle de feu de circulation basé sur un microcontrôleur PIC 18F4680.

•	Détails :

    o	Implémentation d'une séquence lumineuse standard (vert : 10 secondes, jaune : 3 secondes, rouge : 15 secondes).
    o	Utilisation de sous-routines et gestion du temporisateur (TMR0) pour contrôler les délais.
    o	Test du programme sur simulateur MPLAB X, suivi d'une validation sur un microcontrôleur réel.
    o	Intégration de variables modifiables pour ajuster dynamiquement les délais des différentes lumières
    
2. Modification d’un fichier exécutable avec un désassembleur

•	Objectif : Développer des compétences en ingénierie inverse en utilisant un désassembleur pour modifier un programme.

•	Détails :

    o	Familiarisation avec le désassembleur x64dbg pour extraire et analyser les instructions machine.
    o	Modification d'instructions dans un exécutable pour changer le comportement du programme.
    o	Remplacement d'une chaîne de caractères dans l'exécutable pour afficher un message personnalisé dans l'interface utilisateur.
    o	Exploration des concepts de « code caves » pour insérer de nouvelles instructions sans affecter l'intégrité du programme
    
3. Multiplication en virgule flottante (IEEE 754)

•	Objectif : Implémenter une routine en assembleur pour multiplier deux nombres en format IEEE 754.

•	Détails :

    o	Développement de sous-routines pour extraire le signe, l’exposant et la fraction des nombres.
    o	Gestion des biais d’exposants et réalisation de la multiplication des fractions.
    o	Résultat final respectant la norme IEEE 754 (signe, exposant, fraction).
    o	Tests effectués avec divers scénarios, incluant des nombres positifs et négatifs
    
4. Gestion des dépassements en virgule flottante

•	Objectif : Améliorer le programme précédent pour détecter et gérer les dépassements (« overflow » et « underflow »).

•	Détails :

    o	Ajout de sous-routines pour détecter les dépassements via le registre STATUS.
    o	Stockage des erreurs détectées dans des adresses mémoire spécifiques.
    o	Validation des résultats en simulant des dépassements avec des exemples prédéfinis
    
5. Algorithme de Booth pour la multiplication en complément à 2

•	Objectif : Implémenter l'algorithme de Booth pour multiplier des nombres sur 8 bits en complément à 2.

•	Détails :

    o	Développement en assembleur pour gérer les quatre étapes de l'algorithme de Booth.
    o	Tests avec des scénarios positifs et négatifs pour valider l’exactitude des résultats.
    o	Exploitation des registres spécifiques du PIC 18F4680 pour le traitement des calculs

I.R(07/01/2025)
