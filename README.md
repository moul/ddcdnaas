ddcdnaas
========

[![GuardRails badge](https://badges.production.guardrails.io/moul/ddcdnaas.svg)](https://www.guardrails.io)

Distribution-de-cadeaux-de-Noël As A Service


init.sh:
--------

- chaque joueur apporte un cadeau à moins de 20€
- emballer les cadeaux au milieu de la table avec des numéros
- écrire des numéros sur autant de petits bouts de papier qu’il y a de cadeaux et les donner aux participants, ils indiqueront l’ordre, pour les plus disciplinés, cette étape est facultative


Workflow:
---------

- le numéro 1 tire un cadeau et l’ouvre
- le numéro 2 prend un autre cadeau, l'ouvre et choisi de le garder ou de voler un des cadeaux ouverts avant par une autre personne
- c'est ensuite le tour du numéro 3 qui peut garder son cadeau ou voler celui du numéro 1 ou du numéro 2..

- lorsque tous les participants ont ouvert un cadeau, on reprend au numéro 1, qui a alors la possibilité soit de passer son tour, soit de voler n'importe quel cadeau n'ayant pas déjà été volé 3 fois.
- c'est ensuite le tour du numéro 2..

Condition d'arrêt:
------------------

- Plus personne ne souhaite voler de cadeau, ou bien tous les cadeaux ont été volés déjà 3 fois

Exceptions:
-----------

- un cadeau ne peut être volé plus de 3 fois, une personne volant un cadeau pour la 3ème fois le garde définitivement
