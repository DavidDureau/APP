# TD1 MPI - Prise en main et communications point-à-point bloquantes

## Exercice I : Prise en main

**Question 1 :** Ecrire un programme MPI où chaque processus affiche :
* son rang,
* le nombre total de processus MPI,
* et la machine hôte sur laquelle il s’exécute (fonction `MPI_Get_processor_name`)
* le processus id (pid) (fonction `getpid`).
Le tester.

Les valeurs des pids sont elles identiques ? Explication ?


**Question 2 :** Rajouter la déclaration d'une variable `ma_var` et afficher l'adresse de cette variable par processus.
* Les adresses affichées sont elles identiques ? Explication ?

**Question 3 :** Rajouter une instruction `printf(« Avant MPI_Init\n »)` juste avant l’appel à `MPI_Init`.
* Combien de message `« Avant MPI_Init »` apparaît à l’écran en fonction du nombre de processus MPI ? Explication ?

