Jacquemont Matthias
Bapaume Marco
Image 2024

Nous avons peer-programé pour ce projet.

Nous avons à chaque fois essayé plusieurs algorithmes celui qui nous parraissait le meilleur.

Pour le recalage:  nous avons utilisé une transformée de translation et une métrique de similarité basée sur les moindres carrés pour aligner les images.

Pour la segmentaion:  nous avons utilisé l'algorithme de segmentation automatique appelé "Region Growing".

Pour analyser les differences, nous avons choisi d'étidier la différence que volume qui était ce qui nous semblait le plus pertinent: en effet, en médecine, le volume est une métrique souvent utilisé dans le cas de l'analyse de l'evolution d'une tumeur car il détermine la "taille" de la tumeur et permet de prendre des décisions comme la possibilité et la pertinence d'une opération.

Les résultats semblent nous indiquer que la "taille" de la tumeur représenté par son volume à grandement diminué (environ divisé par 4)