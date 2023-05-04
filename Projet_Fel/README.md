# Projet_Fel
Stage développeuse intégratrice web (Epitech) - Ecole des Mines de Saint-Etienne Gardanne

1 - Création d'un repository Git keithleygui afin de pouvoir récupérer le travail sur le git dont voici l'adresse : https://github.com/Jessica4488/Projet_Fel

2 - Pour lancer l'interface:
#Installer Python 3.9 pas de version supérieure ou antérieure ainsi que les packaging associés
#Cloner le repository dans l'éditeur de code de votre choix 
#Trouver le chemin du fichier test nommé keithleygui avec le terminal powershell selon où il sera enregistré
#Lancer l'interface en écrivant dans le powershell : python3.9 Project_Fel.py
#L'interface s'ouvre dans une nouvelle fenêtre Python
#Connecter l'ordinateur à un SMU afin de pouvoir tester le code et y apporter les modifications nécessaires à son fonctionnement final

3 - Utilisation de l'interface :
L'interface comporte plusieurs sections dont certaines sont fonctionnelles et d'autres non.
Le code backend à intégrer se situe dans les fichiers suivants:

#pyqtplot_canvas_time.py (sert à créer une courbe sinusoïdale selon le temps)

#main.py (sert à modifier l'interface en frontend et backend)
exemple: main.py ligne 60

self.sense_type = self.addSelectionField(
            "ON / OFF:", ["On", "Off"]
        )

Cette ligne permet la création du bouton ON/OFF en frontend mais il faut intégrer le backend afin qu'il soit fonctionnel lors de la connection au SMU.

Conclusion:
Plusieurs boutons ayant été créés ne sont pas fonctionnel ainsi que la courbe de temps, le travail consistera à coder cela afin de finaliser l'interface graphique.

