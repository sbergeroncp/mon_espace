# atelier_a

## @showdialog
Ce tutoriel a été réalisé par l'équipe d'intégration du numérique du Centre de services scolaire des Bois-Francs.

Sébastien Bergeron - Conseiller pédagogique

Journée du numérique - 3 décembre 2021

## @showdialog
Transforme le porte-nom ordinaire en un porte-nom numérique!

![CSSBF](https://github.com/sbergeroncp/tuto/blob/master/dice.png?raw=true)

## @showdialog

Prépare ton espace de travail!

## Étape 1

Supprime ``|| basic:"au démarrage" ||`` de l'espace de travail.

## Étape 2

Ajoute ``|| basic:Montrer l'icône ||`` dans le bloc ``|| basic:Toujours ||``.

Sélectionne l'icône de ton choix. 

Tu peux également choisir ``|| basic:Montrer LEDs ||`` afin de personnaliser l'icône.

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})

basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```

## @showdialog
