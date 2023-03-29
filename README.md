# meta_learning
Projet IA321 - Meta-learning 


## Problèmes 1 et 2 codes
- Le fichier problème_1_code.ipynb contient les codes utilisés pour tester les différentes algorithmes sur le premier problème défini dans le rapport
- Le fichier problème_2_TPE_BO_PSO_CMAES_code.ipynb contient les codes utilisés pour tester les algorithmes TPE, BO, PSO et CMAES
- Le fichier graphiques.ipynb contient le codes utilisés pour générer les graphiques et produirent les statistques des techniques testés.
- Le fichier RL_PPO_2envs.ipynb : Notebook pour l’environnement avec variation continue et l’environnement avec contexte (PPO).

## Implémentation d'un scheduler via un Agent Rl
- Le code RL_SAC_2403.ipynb contient l'implémentation du meta scheduler lorsque la policy de l'agent RL est établi par l'algorithme SAC.
- Le code RL_PPO_v2_alter_act.ipynb contient l'implémentation du meta scheduler lorsque la policy de l'agent est établi par l'algorithme PPO.

Chacun de ces fichiers génére deux documents .csv: l'un contient les rewards à chaque step de l'environnement, le second nommé output.csv contient les accuracy et les learning rate défini par l'agent RL lors de l'entrainement du ResNet18.
