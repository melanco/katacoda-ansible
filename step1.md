Ce scénario Ansible vous démontrera comment écrire un playbook basé sur un inventaire simple pour démontrer le fonctionnement.

## Task
Commencez par vous faire un inventaire simple qui contient les machines suivantes.

machine01
machine02

`echo machine01\n machine02 > inventory`{{execute}}

Inspectez l'inventaire. 

`cat inventory`{{execute}}

Ce fichier représente les machines sur lesquelles votre playbook va s'exécuter. Le playbook en question s'exécutera en ordre sur l'inventaire donné.
