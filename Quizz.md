## Qu'est ce qu’un navigateur ?

```
Un navigateur est une fenêtre sur laquelle on peutafficher et consulter le web.
Navigateurs connus : Google Chrome, Mozilla Firefox, Safar..


```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
HTML : permet l'appel du contenu de la page web (données brutes sans aucun style)
CSS : permet la mise en forme, mise en page de la page web
JavaScript : permet l'intéraction et l'animation de la page web

```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
L'élément indique la structure d'un document HTML et indique au navigateur comment il doit
présenter le site web (ex : l'élément <nav> indique à notre document HTML qu'il s'agit de
la mise en place d'une barre de navigation et sera compris par le navigateur).
L'attribut est l'information complémentaire que peut recevoir un élément (ex : si on ajoute
à la balise <body> l'attribut style="background-color:blue;"> dont donnons l'information
que notre page sera complètemeny bleue). 
```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
Les classes peuvent caractériser plusieurs objets identiques ou non. Elle sont ajoutées à
des éléments pour lesquels nous avons besoin d'appliquer le même style en css.
Ex : si nous voulons tous nos titres <h2> nous indiquerons en html sur tous nos éléments <h2>
la classe "red" (<h2 class="red">) et dans le doc css nous appellerons cette classe pour le
lui indiquer (.h2 { color: red;}).
L'id quant à lui s'applique à un objet unique. Si nous avons besoin de mettre des ancres sur 
une même page, nous ajouterons un id à chaque section de la page dont la barre de navigation
fait référence.
```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```




```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```
L'indentation est importante car elle permet de détecter des erreurs dans notre code
(syntaxe, oubli d'une balise fermante), d'en améliorer sa lisibilité et du coup de le rendre
beau !

```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```
Le padding est la marge que l'on applique entre le contenu de l'élément et l'élément.
Le margin est la marge que l'on applique extèrieurement de l'élément.

```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
position relative : l'élément est positionné par rapport à l'élément précedent.
position absolute : l'élément est positionné par rapport au bord de la page et défile avec
la page.
position static : c'est la valeur par défaut c'est à dire en fonction de l'ordre d'arrivée
des éléments.
```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
La variable est l'espace de stockage permettant d'enregister des données (chaîne de caractères ou
des chiffres par exemple).
En Js, la variable déclarée sera nécessaire pour que l'ordinateur enregistre les données
et puisse les traiter.


```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```
Lorsque nous déclarons une variable, il est nécessaire d'en spécifier le type :
Type booléen : pour avoir un résultat logique (true pour vrai ou false pour faux)
Type nombre : pour représenter des nombre
Type chaîne de caractères (string) : pour représenter des données textuelles

```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```
"if" sert à exprimer une condition.



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```




```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
Une requête HTTP est un ensemble de lignes envoyé au serveur par le navigateur pour
restituer la demande faite par l'utilisateur.


```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```




```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```




```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```
Les codes en 200 : indiquent le bon déroulement de la requête
Les codes en 300 : indiquent que la ressource demandée n'est plus à l'adresse indiquée
Les codes en 400 : indiquent que le requête est incorrecte

```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Scrum Master : son rôle est celui de facilitateur au sein d’une équipe. Il doit s’assurer
de la compréhension de la méthode par son équipe ainsi que de sa mise en œuvre. Il est
donc responsable du bon déroulement et de la réalisation des tâches.

Product Owner : c'est la seule personne responsable pour la gestion du Product Backlog. Il
est le représentant des clients et utilisateurs du produit. Son rôle est de maximiser la
valeur du produit et du travail de l’équipe de développement.
```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```
git init "nom_du_projet" : crée en local à partir du nom spécifié
git checkout -b "nom_branch" : crée en local une nouvelle branche et se positionne dessus
git clone url : télécharge un projet avec tout son historique via l'url

```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```




```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```




```


