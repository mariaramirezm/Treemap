## Treemap

#Information sur le Treemap

Aussi appelé « Carte Proportionnelle », un TreeMap est la représentation de données hiérarchiques dans un espace limité divisé en rectangles auxquels une taille et un ordre sont assignés en fonction d’une variable quantitative. Cette technique de visualisation d'information est construite à partir d’un « Tree Diagram » et permet à l'utilisateur final de reconnaître facilement des motifs graphiques pouvant traduire des relations complexes au sein des données, relations difficiles à déceler autrement.

Les différents niveaux hiérarchiques son visualisées comme rectangles dedans autres rectangles. Chaque conjoint représente soit une colonne soit une expression d’un tableau de données. Chaque rectangle individuel d’un niveau hiérarchique représente une catégorie d’une colonne et sa quantité fixe la taille de son are en proportion avec les autres quantités qui appartient au même père de l’arbre.

Quand une catégorie n’a pas une quantité assignée l’are est distribué de façon équitable entre toutes les catégories qui appartient au même père de l’arbre.

Pour créer une carte proportionnelle, il faut définir un algorithme d’assemblage pour diviser un rectangle en sous-rectangles avec des surfaces définies. Dans l’idéal, un algorithme de carte proportionnelle devrait créer des rectangles de proportions similaires, tout en préservant la signification de l’ordre de données représentées, et toute modification devrait refléter les modifications de ces données.
Malheureusement ces propriétés s'opposent : tandis que les proportions sont optimisées, l’ordre de placement devient en moins prévisible. Tandis que l’ordre est préservé, les proportions entre les rectangles sont dégradées.

À ce jour six principaux algorithmes de carte proportionnelle rectangulaire ont été développés :

<table border="0">
  <tr>
    <td>
      <img src="C:\Users\maria\Desktop\universidad\Master\Segundo\MOS\Visualisation des donnees\Tarea 1\Captura.PNG" style="width: 100px;">
    </td>
  </tr>
</table>

