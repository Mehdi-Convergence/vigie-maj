# Vigie

Ce depot ne sert qu'a distribuer les publications signees de Vigie.

Chaque publication porte deux fichiers :

- `vigie.exe` : le programme ;
- `manifeste.json` : sa version, l'empreinte SHA-256 du programme, et la **signature
  Ed25519** de l'ensemble.

Le programme verifie cette signature avant d'installer quoi que ce soit. Un fichier qui ne la
porte pas n'est pas installe.

Le code source n'est pas ici.
