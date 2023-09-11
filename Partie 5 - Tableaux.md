# PHP-Partie-5-Tableaux
Les Tableaux
## Petit tips 
En PHP, un tableau est une structure de données qui permet de stocker plusieurs valeurs dans une seule variable. 

C'est un peu comme une boîte où tu peux ranger plusieurs paires de chaussures.

Il existe deux types de tableaux en PHP : les tableaux indexés et les tableaux associatifs.

1. **Tableaux indexés** : Les valeurs sont stockées dans un ordre précis et chaque valeur a un index correspondant. **L'index commence toujours à 0**. Par exemple :

```php
$couleurs = ["rouge", "vert", "bleu"];
echo $couleurs[0]; // Affiche "rouge"
echo $couleurs[1]; // Affiche "vert"
echo $couleurs[2]; // Affiche "bleu"
```

2. **Tableaux associatifs** : Chaque valeur est associée à une clé. La clé peut être un nombre ou une chaîne de caractères. On parle ici d'un format clé => valeur
Par exemple :

```php
$ages = ["John" => 35, "Jane" => 27, "Bob" => 55];
echo $ages["John"]; // Affiche 35, On accède à la valeur qui est 35 grâce à la clé "John" 
```

Pour parcourir un tableau, on peut utiliser une boucle `foreach`. Par exemple :

```php
$ages = ["John" => 35, "Jane" => 27, "Bob" => 55];
foreach ($ages as $key => $age) {
    echo $key . "est agé de " . $age ." ans" . "<br>";  // Ici je crée une phrase en mettant bout à bout des chaines de caractère ainsi que des variables contenant une valeur, nous appelons ça la concaténation
}
```

Ce code affiche l'age de la personne sur une nouvelle ligne.

A ton tour d'utiliser des tableaux 😎!

### A vous de jouer ! 

## Exercice 1
Créer un tableau **months** et l'initialiser avec les valeurs suivantes :
- **janvier**
- **février**
- **mars**
- **avril**
- **mai**
- **juin**
- **juillet**
- **aout**
- **septembre**
- **octobre**
- **novembre**
- **décembre**

## Exercice 2
Avec le tableau de l'exercice 1, afficher la valeur de la troisième ligne de ce tableau.

## Exercice 3
Avec le tableau de l'exercice , afficher la valeur de l'index 5.

## Exercice 4
Avec le tableau de l'exercice 1, modifier le mois de **aout** pour lui ajouter l'accent manquant.

## Exercice 5
Créer un tableau associatif avec comme index le numéro des départements des Hauts de France et en valeur leur nom.

## Exercice 6
Avec le tableau de l'exercice 5, afficher la valeur de l'index 59.

## Exercice 7
Avec le tableau de l'exercice 5, ajouter la ligne correspondant au département de la ville de Reims.

## Exercice 8
Avec le tableau de l'exercice 1 et une boucle, afficher toutes les valeurs de ce tableau.

## Exercice 9
Avec le tableau de l'exercice 5, afficher toutes les valeurs de ce tableau.

## Exercice 10
Avec le tableau de l'exercice 5, afficher toutes les valeurs de ce tableau ainsi que les clés associés.  
Cela pourra être, par exemple, de la forme : **"Le département" + nom du département + "a le numéro" + numéro du département**