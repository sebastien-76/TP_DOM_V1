# ECF DOM
ECF pour le TP Dev web PopSchool 08/2023 sur le DOM 

## Description
Dans cet exercice, l'utilisateur est un enseignant qui doit pouvoir noter ses élèves. Il faudra,donc, un tableau avec en colonne 1 le nom des élèves (une dizaine d'élèves), en colonne 2 le nom du devoir.
Il doit pouvoir évaluer par note ou par couleur. Il peut vouloir évaluer certains devoirs par note et d'autres devoirs par couleur, mais il n'y pas de relation entre le système de notation par couleur ou par note tradi0onnelle. Un devoir est, soit évalué par note, soit par couleur.
Les notes traditionnelles seront de 1 à 5. On ne peut mettre que ces 5 valeurs. Si l'utilisateur tape autre chose, il faut remeIre la valeur à vide. Pour les couleurs, il doit pouvoir mettre 4 couleurs (rouge, orange, jaune, vert). S'il note par couleur, les inputs devront tous être en couleur verte par défaut et il faudra mettre le focus sur le premier input.
Ensuite, lorsque l'utilisateur tapera sur les touches 1, 2, 3, 4, on remplira la case de la couleur correspondante.
Avec la touche 1, on mettra la couleur rouge, la 2 la couleur orange, la 3 la couleur jaune et 4 la couleur verte. Il faut que le chiﬀre disparaisse avant de passer à la case suivante. On ne doit voir que la couleur sur les cases.
Il faut donc un bouton pour que l'utilisateur nous dise avant de commencer s'il note en couleur ou par note. 
Avant son choix, il ne doit pas pouvoir noter, donc les inputs doivent être cachés.
En fonction de son choix, il faudra tout d'abord que les inputs s'aﬃchent et que le focus soit automatiquement positionné sur le premier input (soit le premier élève en réalité). Il faudra gérer les évènements pour qu'il puisse évaluer et que le focus passe automa0quement sur la case du dessous, donc sur l'élève suivant. Mais si la touche saisie ne correspond pas à celle
que nous avons déterminé, rien ne doit se passer, nous ne devons pas passer le focus sur l'élève suivant.

## Requis
- HTML
- CSS
- Javascript
- Github