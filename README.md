# data-lifecycle-pr2
Projecte per la pràctica 2 de l'assignatura Tipologia i Cicle de Vida de les Dades (UOC, 2022)

## Dataset

[*Red wine quality*](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

## Descripció del dataset

El data set conté informació de diverses variants del vi portugués “Vinho Verde”, incloent variables quantitatives com medicions Fisico-químiques i sensorials (qualitat del vi).  Tanmateix per raons de privacitat i secret comercial s’exclouen dades comercials com la marca, el preu o el tipus de raïm emprat en l’elaboració dels vins. 

Aquest data set pot ser emprat per determinar quins factors fisicoquímics defineixen un bon vi, responent a les següents preguntes: 

- Hi ha una combinació específica en les propietats Fisico-químiques que facin un vi de la millor qualitat? 
- És un factor o hi ha diversos? 
- Com és relacionen entre sí? 
- Quines són les seves distribucions estadístiques?


Integració i selecció de les dades d’interès a analitzar. 

El dataset conté 12 variables, on les 11 primeres poden considerar-se els inputs (factors Fisico-químics) i la última l’output (valoració de la qualitat del vi basada en una experiència sensorial).

Donat que resulta fonamental conèixer el domini de les dades que pretenem analitzar i modelitzar passem a descriure-les a continuació:

1. Fixed acitidy. La majoria dels àcids en el vi són fixos, és a dir, no s’evaporen fàcilment
1. Volatile acidity. La quantitat d’àcid acètic en el vi, que en altes quantitats, pot provocar un gust desagradable.
1. Citric acidity. Concentrat en petites quantitats, pot aportar frescor i sabor als vins
1. Residual sugar. La quantitat de sucre remanent un cop finalitzada la fermentació. Resulta estrany trobar vins amb menys d’un gram per litre i vins amb més de 45 grams/litre són considerats dolços. 
1. Chlorides. Quantitat de sal en el vi.
1. Free sulfur dioxide. SO2 en forma lliure existent en equilibri amb el SO2 mol·lecular (dissolt com un gas).
1. Total sulfur dioxide. Quantitat total SO2. En concentracions superiors als 50 ppm té presència en el gust i l'olfacte.
1. Density. Densitat del líquid en relació a la quantitat d’alcohol i sucre.
1. pH. Descriu quan àcid o bàsic és un vi d’una escala des de 0 (molt àcid) a 14 (molt bàsic). La majoria de vins es situen entre 3 i 4. 
1. Sulphates. Quantitat d'additiu que actua com a antibacterià i antioxidant.
1. Alcohol. Percentatge d'alcohol present al vi. 
1. Quality. Variable output qualitativa basada en dades sensorials, en una escala del 0 al 10. 

Per l’anàlisi que volem realitzar considerem que podem mantenir les 12 variables, per tant, no farem cap subselecció.
