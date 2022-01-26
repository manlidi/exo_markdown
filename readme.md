1-Les widgets

        Un widget est une extension d’application, souvent intégrée dans une application déjà installée sur votre téléphone. 

        Les widgets sont immuables. C'est-à-dire qu'ils ne peuvent pas être modifiés. Toutes les propriétés qu'ils contiennent sont définitives et ne peuvent être définies que lorsque le widget est initialisé. Cela les maintient légers afin qu'il soit peu coûteux de les recréer lorsque l'arborescence des widgets change. Il existe deux types de widgets : sans état et avec état.


2- Les catégories de widgets en Flutter
       
     Dans Flutter , il existe deux principaux types de widgets : Widgets Flutter sans état et Widgets Flutter avec état

3- La liste de chaque catégorie

          Flutter est livré avec une suite de widgets de base puissants, dont les suivants sont couramment utilisés:

          -Widgets Flutter sans état
          Les widgets sans état sont des widgets qui ne stockent aucun état. C'est-à-dire qu'ils ne stockent pas les valeurs susceptibles de changer.

                1)Par exemple, une icône est sans état ; vous définissez l'image de l'icône lorsque vous la créez, puis elle ne change plus.

                2)Un widget Texte est également sans état. Si vous souhaitez modifier la valeur du texte, il vous suffit de créer un tout nouveau widget avec le nouveau texte. Les widgets Text Flutter ne stockent pas de propriété de texte modifiable

                3)Raised Button

         -Widgets Flutter avec état
         Le deuxième type de widget est appelé un widget avec état. Cela signifie qu'il peut suivre les modifications et mettre à jour l'interface utilisateur en fonction de ces modifications. Le widget avec état lui-même est immuable, mais il crée un objet State qui garde une trace des modifications. Lorsque les valeurs de l'objet State changent, il crée un tout nouveau widget avec les valeurs mises à jour. Ainsi, le widget léger est recréé mais l'état persiste à travers les changements.
