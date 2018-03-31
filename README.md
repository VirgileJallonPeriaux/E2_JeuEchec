# Réalisation d'un jeu d'échec en *Expression2*

### Garry's Mod
Sorti fin 2004, *Garrys's Mod* est un jeu multijoueur de type "sand box" (bac à sable).
Le joueur y est libre de manipuler, assembler et créer des objets de divers types grâce au moteur de jeu Source.
Une communauté de développeurs s'est donnée pour mission de faire évoluer le jeu en proposant aux joueurs de nouvelles extensions ("addons").
La plupart sont développées sous forme de scripts LUA et une mineure partie sous forme de DLL C++.
Parmi les nombreuses extensions existantes, une se démarque des autres : le Wire.

### L'extension *Wire*
De loin l'extension la plus complète disponible sur Garry's Mod, elle propose notamment deux idées clefs :

##### Les Gates (Portes logiques)
Elles permettent au joueur d'utiliser dans le jeu des portes logiques et de construire des algorithmes simples en reliant différentes "portes" entre elles. Simples d'utilisation, elles permettent notamment d'effectuer des opérations mathématiques sur des nombres.
De manière un peu plus complexe, les gates permettent aussi de manipuler des vecteurs 3D (x,y,z), des chaînes de caractères, des array...


##### L'Expression 2 (E2)
L'Expression 2 est un langage de programmation interprété disponible depuis le jeu.
Il permet au joueur de programmer via une IHM proposant une coloration syntaxique et une autocomplétion.
Bien que très permissif, l'E2 reste limité en terme de POO : on ne peut pas créer de classe ni en étendre une déjà existante.
Il est toutefois possible de créer ses propres méthodes en les programmant dans un script LUA.

https://github.com/wiremod/wire/wiki/Expression-2
interprété
