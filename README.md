# meta_learning
Projet IA en Meta-learning

##Implémentation d'un scheduler via un Agent Rl
- Le code RL_SAC_2403.ipynb contient l'implémentation du meta scheduler lorsque la policy de l'agent RL est établi par l'algorithme SAC.
- Le code RL_PPO_v2_alter_act.ipynb contient l'implémentation du meta scheduler lorsque la policy de l'agent est établi par l'algorithme PPO.

Chacun de ces fichiers génére deux documents .csv: l'un contient les rewards à chaque step de l'environnement, le second nommé output.csv contient les accuracy et les learning rate défini par l'agent RL lors de l'entrainement du ResNet18.
