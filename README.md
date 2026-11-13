Réponses aux questions : 

**1 - Dans .en-cours en colonne, pourquoi align-items: center centre-t-il horizontalement, alors qu'en ligne il centre verticalement ?**
>> .en-cours est en flex-direction column. justify-content s'occupe de l'axe principal (le vertical), 
align-items s'occupe de l'axe secondaire (l'horizontal)


**2 - Que se passe-t-il pour la barre de progression si tu retires flex-grow ? Et si tu le mets aussi sur les deux temps ?**
>> Si l'on retire flex-grow, il ne prendra plus le pourcentage de place qui lui est dédié. 
 Même logique si l'on mets flex-grow sur les deux temps, et tout dépends de la valeur qu'on leur attribut. 
 Si on mets un flex-grow à 1 sur un élément et un 2 sur un autre l'autre pourra prendre le double de l'espace du 1er. 


**3 - Pourquoi commencer par le mobile et ajouter le grand écran dans une media query min-width, plutôt que l'inverse ?**
>> C'est plus moderne. On préviligie les téléphones car la plupart des lectures sont sur ce format. 
 Gérer par la suite des écrans plus grand reste essentiel pour une responsive propre. (768px, 1024px, 1440px, etc...)
