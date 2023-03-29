# Code de conduite du projet AndroNav

Nous, en tant que membres de la communauté AndroNav, nous engageons à maintenir un environnement respectueux et accueillant pour tous. Nous adoptons ce code de conduite pour définir des attentes claires de comportement pour tous les membres du projet. Nous encourageons tous les contributeurs à lire et à suivre ces directives.

## Version de d'Android Studio et de l'émulateur

Pour contribuer au projet AndroNav, vous devez utiliser la version suivante de Graddle: 7.5, la version d'Android Studio: 2022.1.1.21 (Electric Eel).

Nous utilisons l'émulateur d'Android Studio pour tester l'application, l'emulateur Pixel 4 API 30 (disposant des services Google Play).

## Convention de nommage

Nous utilisons la convention de nommage suivante pour les noms de variables, de fonctions et de classes:

- Les noms de variables et de fonctions doivent respecter la convention de nommage camelCase.

```kotlin
val myVariable = "Hello World!"

fun myFunction() {
    // ...
}
```

- Les noms de classes doivent respecter la convention de nommage PascalCase.

```kotlin
class MyClass {
    // ...
}
```

- Les noms de ressources doivent être en minuscules et séparés par des underscores.

```xml
<resources>
    <string name="my_string">Hello World!</string>
</resources>
```

## Convention de codage

Nous utilisons la convention de codage suivante pour le codage:

- Chaques fonction doit être documentée avec un bloc de commentaire au-dessus de la fonction.

```kotlin
/**
 * This function does something.
 *
 * @param param1 The first parameter.
 * @param param2 The second parameter.
 * @return The return value.
 */
fun doSomething(param1: String, param2: String): String {
    // ...
}
```

- Les noms de variables doivent être des noms de mots, pas des abréviations.

```kotlin
// Mauvais
val lat = 45.0

// Bon
val latitude = 45.0
```

- Les attributs d'une classe doivent être privés et doivent être accédés par des fonctions publiques.

```kotlin
// Mauvais
class MyClass {
    var myVariable = "Hello World!"
}

// Bon
class MyClass {
    private var myVariable = "Hello World!"

    fun getMyVariable(): String {
        return myVariable
    }

    fun setMyVariable(myVariable: String) {
        this.myVariable = myVariable
    }
}
```

## GitFlow

Nous utilisons GitFlow pour notre processus de développement. Cela signifie que toutes les fonctionnalités et les correctifs doivent être développés sur une branche de fonctionnalité séparée, qui est ensuite fusionnée dans la branche de développement. Toutes les demandes de fusion doivent être examinées par un autre développeur avant d'être fusionnées dans la branche de développement.

## Comportement attendu

Tous les membres du projet AndroNav doivent:

- Traiter tous les autres membres avec respect et considération, indépendamment de leur sexe, de leur orientation sexuelle, de leur race, de leur religion ou de toute autre caractéristique personnelle.
- Communiquer de manière constructive et éviter les attaques personnelles ou le langage offensant.
- Respecter la vie privée et les informations personnelles des autres membres du projet.
- Accepter avec grâce les critiques constructives.
- Faire preuve d'empathie envers les autres membres de la communauté.

Les comportements inappropriés comprennent, sans s'y limiter:

- L'intimidation, le harcèlement ou les commentaires offensants sur les caractéristiques personnelles.
- Les attaques personnelles ou le langage offensant.
- Le spamming ou le trolling.
- La divulgation d'informations privées sans consentement.
- Toute autre forme de comportement inapproprié ou non professionnel.

Les membres du projet AndroNav qui ne respectent pas ces attentes de comportement peuvent être temporairement ou définitivement exclus de la communauté.

## Signaler des comportements inappropriés

Si vous êtes témoin ou victime de comportements inappropriés de la part d'un membre du projet AndroNav, veuillez contacter immédiatement un administrateur du projet. Tous les rapports seront traités avec confidentialité et seront examinés dans les plus brefs délais.

## Attribution

Ce code de conduite est adapté du [Contributor Covenant](https://www.contributor-covenant.org), version 2.0, disponible à l'adresse https://www.contributor-covenant.org/version/2/0/code_of_conduct.html.
