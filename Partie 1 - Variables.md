# PHP-Partie-1-Variables
Variables et types de données

Une variable en PHP, c'est comme une boîte dans laquelle tu peux stocker une valeur. Tu peux donner un nom à cette boîte pour pouvoir la retrouver plus tard.

Voici comment on déclare une variable en PHP :

```php
$nomDeLaVariable = valeur;
```

Et voici comment on affiche le resultat d'une variable sur une page :

```php
echo $nomDeLaVariable;
```

Par exemple, on peut créer une variable qui stocke ton âge :

```php
$age = 20;
echo $age; // Affiche 20
```

On peut aussi créer une variable qui stocke ton prénom :

```php
$prenom = "John";
echo $prenom; // Affiche "John"
```

Et on peut même utiliser des variables pour faire des calculs :

```php
$nombre1 = 10;
$nombre2 = 20;
$somme = $nombre1 + $nombre2;
echo $somme; // Affiche 30
```

## Les types de données dans les variables

Une variable est un conteneur pour stocker une valeur. Cette valeur peut être de différents types :

- **Entiers** (`int`) : Ce sont des nombres sans décimales. Par exemple, `$age = 20;`.

- **Flottants** (`float`) : Ce sont des nombres avec des décimales. Par exemple, `$prix = 9.99;`.

- **Chaînes de caractères** (`string`) : Ce sont des séquences de caractères. Par exemple, `$nom = "John";`.

- **Booléens** (`bool`) : Ce sont des valeurs de vérité. Ils ne peuvent être que `true` (vrai) ou `false` (faux). Par exemple, `$estMajeur = true;`.

- **Tableaux** (`array`) : Ce sont des collections de valeurs. Par exemple, `$couleurs = array("rouge", "vert", "bleu");`.

- **Objets** (`object`) : Ce sont des instances de classes. Par exemple, `$voiture = new Voiture();`.

- **NULL** : C'est une valeur spéciale qui représente une variable sans valeur. Par exemple, `$inconnu = NULL;`.

On déclare une variable avec le symbole `$` suivi du nom de la variable. On peut ensuite utiliser cette variable dans notre code en la rappelant par son nom.


### A vous de jouer ! 

## Exercice 1
Créer une variable **name** et l'initialiser avec la valeur de votre choix.  Afficher son contenu.

## Exercice 2
Créer trois variables **lastname** , **firstname** et **age** et les initialiser avec les valeurs de votre choix.  **Attention** age est de type entier.  Afficher leur contenu.

## Exercice 3
Créer une variable **km**. L'initialiser à 1. Afficher son contenu.  
Changer sa valeur par 3. Afficher son contenu.  
Changer sa valeur par 125. Afficher son contenu.

## Exercice 4
Créer une variable de type string, une variable de type int, une variable de type float, une variable de type booléan et les initialiser avec une valeur de votre choix.  
Les afficher.

## Exercice 5
Créer une variable de type int. L'initialiser avec **rien**. Afficher sa valeur.  
Donner une valeur à cette variable et l'afficher.

## Exercice 6
Créer une variable **name** et l'initialiser avec la valeur de votre choix.  
Afficher : "Bonjour" + **name** + ", comment vas tu ?".

## Exercice 7
Créer trois variables **lastname** , **firstname** et **age** et les initialiser avec les valeurs de votre choix.  **Attention** age est de type entier.  
Afficher : "Bonjour" + **lastname** + **firstname** + ",tu as" + **age** + "ans".

## Exercice 8
Créer 3 variables.  
Dans la première mettre le résultat de l'opération **3 + 4**.  
Dans la deuxième mettre le résultat de l'opération **5 * 20**.  
Dans la troisième mettre le résultat de l'opération **45 / 5**.  
Afficher le contenu des variables.
