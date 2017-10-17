tarting-web-developpment

# Deux parties dans les commentaires


## code html


j'ai eu du mal pour la partie `<div class="maincontent">` :
J'ai pris du temps et essayé plusieurs options


l'image et le texte, les div flottantes sortaient de leur contenu.

** Solution 1**
J'ai enveloppé le texte et le titre d'un div

** Solution 2**
J'ai mis une balise `<div class="clear">` avec la propriété  clear: both;



## css

j'ai mis une taille fixe en pixel pour le `<div id="wrapper">`
car en % c'est illisible sur portable

#Utilisation de Flex pour le float

Pour la `<ul>`j'ai utilisé la propriété **display:flex** car c'est conseillé pour plusieurs images.
