# PHP

![PHP Logo](img/php.png)



---



## Qu'est ce que c'est ?

PHP est un langage de script et de programmation

Il est en général utilisé pour réaliser des sites web.

Il partage un certain nombre de caractéristiques avec JavaScript  
(haut niveau, interprété, typage dynamique).



---



## Fonctionnement

PHP s'éxecute dans un serveur Web et interprète les pages PHP à la demande.

<!-- TODO Schema, y'en a un bien sur wikipedia -->



---



## Syntaxe


Le code PHP est écrit entre les balises PHP :

```php
<?php
  // Le code PHP ici.
?>
```

Le reste du code n'est pas interprété par PHP.



---



## L'instruction `echo`

L'instruction `echo` permet d'écrire dans la page.

Tout le texte hors des balises PHP est également écrit dans la page.



---


## Hello World en PHP

```
<!DOCTYPE html>
<html>
<head>
  <title>PHP : Hello World</title>
</head>
<body>
<?php
  echo "Hello World";
?>
</body>
</html>

```