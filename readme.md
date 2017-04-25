# Projet copie de AirBnb

Projet pour copier le site d'AirBnb.

Le plus dur a été de faire en de cacher certains éléments du html dans les formats les plus petits pour les faires resortir, de même que le changement d'image selon les dimensions qui sont simple mais long à faire.

Les étoiles pour les notations ne sont que de bêtes images, pas eu le temps de faire autrement. En faisant quelques recherche, j'ai trouvé quelque chose qui s'apparente à ça:
.rating a {
   float: right;
   color: #aaa;
   text-decoration: none;
   font-size: 3em;
   transition: color .4s;
}
.rating a:hover,
.rating a:focus,
.rating a:hover ~ a,
.rating a:focus ~ a {
   color: orange;
   cursor: pointer;
}

Des progrès à faire sur les wireframes, le html a pas mal évolué entre eux et le rendu final
