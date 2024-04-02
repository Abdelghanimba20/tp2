# tp2
J'ai installé IntelliJ Ultimate sur mon système et créé un projet Spring Initializer avec les dépendances JPA, H2, Spring Web et Lombock. J'ai développé une entité JPA nommée Product avec les attributs requis : id (Long), name (String), price (double) et quantity (int). Pour configurer l'unité de persistance, j'ai modifié le fichier application.properties. Ensuite, j'ai mis en place l'interface JPA Repository en utilisant Spring Data et j'ai testé diverses opérations de gestion des produits telles que l'ajout, la consultation de tous les produits, la consultation d'un produit spécifique, la recherche de produits, la mise à jour et la suppression.

Pour migrer de H2 Database vers MySQL, j'ai répété les mêmes opérations en ajustant la configuration pour utiliser MySQL comme base de données au lieu de H2.

Ensuite, j'ai étendu mes connaissances en reprenant l'exemple du patient et en développant des classes associées utilisant les relations one-to-many, many-to-many et one-to-one.
