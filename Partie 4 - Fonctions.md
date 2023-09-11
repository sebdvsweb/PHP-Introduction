# PHP-Partie-4-Fonctions
Les Fonctions

D'accord, Hamza. Voici une explication simple des fonctions, des boucles et des conditions en PHP :

## Fonctions

Une fonction en PHP, c'est comme une machine qui fait une tâche spécifique. Tu lui donnes des ingrédients (les paramètres), elle fait son travail et te donne le résultat.


Voici comment on déclare une fonction en PHP :

```php
function nomDeLaFonction($parametre) {
    // Code à exécuter
    return $resultat;
}
```

Et voici comment on utilise une fonction :

```php
$resultat = nomDeLaFonction($ingredient);
```

Par exemple, on peut créer une fonction qui calcule la moyenne de deux nombres :

```php
function calculerMoyenne($nombre1, $nombre2) {
    $somme = $nombre1 + $nombre2;
    $moyenne = $somme / 2;
    return $moyenne;
}

$moyenne = calculerMoyenne(10, 20);
echo $moyenne; // Affiche 15
```

### A vous de jouer ! 

## Exercice 1
Faire une fonction qui retourne **true**.

## Exercice 2
Faire une fonction qui prend en paramètre une chaine de caractères et qui retourne cette même chaine.

## Exercice 3
Faire une fonction qui prend en paramètre deux chaines de caractères et qui revoit la concaténation de ces deux chaines

## Exercice 4
Faire une fonction qui prend en paramètre deux nombres. La fonction doit retourner :
- **Le premier nombre est plus grand** si le premier nombre est plus grand que le deuxième
- **Le premier nombre est plus petit** si le premier nombre est plus petit que le deuxième
- **Les deux nombres sont identiques** si les deux nombres sont égaux

## Exercice 5
Faire une fonction qui prend en paramètre un nombre et une chaine de caractères et qui renvoit la concaténation de ces deux paramètres.

## Exercice 6
Faire une fonction qui prend trois paramètres : **le nom, le prénom et l'âge d'une personne**. Elle doit renvoyer une chaine de la forme :  
"Bonjour" + **nom** + **prénom** + ",tu as" + **age** + "ans".

## Exercice 7
Faire une fonction qui prend deux paramètres : **l'âge et le genre d'une personne**. Le genre peut être :
- Homme
- Femme  

La fonction doit renvoyer en fonction des paramètres :
- **Vous êtes un homme et vous êtes majeur**
- **Vous êtes un homme et vous êtes mineur**
- **Vous êtes une femme et vous êtes majeur**
- **Vous êtes une femme et vous êtes mineur**

Gérer tous les cas.

## Exercice 8
Faire une fonction qui prend en paramètre trois nombres et qui renvoit la somme de ces nombres.  
Tous les paramètres doivent avoir une valeur par défaut.