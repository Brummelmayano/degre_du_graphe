# degre_du_graphe

Le travail étant l’implémentation sur le degré d’un sommet, il y'a une fonction pour la representation du graphe,
quatre fonctions qui nous permettrons des calculer les différents
degré des sommets selon le cas et une autres fonctions pour la conversion :

1. Liste ou dictionnaire d’adjacence (nommé adjacency_dict() dans le
programme ) :
Pour représenter le graphe dans notre programme, Nous avons
personnellement opté pour la représentation par listes d’adjacence.

2. Degrés (nommé degrees() dans le programme ): le degré d’un sommet
c’est l’ensemble d’arêtes
relié à ce sommet.

3. Demi-degrés extérieur (d+G(x)) (nommé out_degrees() ): c’est le nombre
d’arcs ayant le sommet x comme extrémité initiale.

4. Demi-degrés intérieur (d-G (x)) (nommé in_degrees()) : c’est le nombre
d’arcs ayant le sommet x comme extrémité terminale.

5. Degré totale d’un sommet (nommé total_degrees() ) : c’est la somme de
demi-degré extérieur et intérieur noté dG (x) = d+G(x) + d-G (x).

6. Fonction pour la conversion ( nommé convert()): cette fonction a pour rôle
de convertir le tuple ( graphe) de la librairie collection.namedtuple en
graphe de la librairie networkx.

environement: Anaconda/jupyter notebook
