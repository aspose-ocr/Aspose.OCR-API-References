---
title: "DetectAreasMode"
second_title: "Référence API d'Aspose.OCR pour Java"
description: 
type: docs
weight: 28
url: /fr/java/com.aspose.ocr.models/detectareasmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum DetectAreasMode extends Enum<DetectAreasMode>
```
## Champs

| Champ | Description |
| --- | --- |
| [CURVED_TEXT](#CURVED-TEXT) | Redresse automatiquement les lignes de texte courbes dans l'image, améliorant la précision de la reconnaissance et permettant de récupérer et d'extraire davantage de texte. |
| [FORMULA](#FORMULA) | Détecte tous les blocs contenant des formules mathématiques. |
| [LEAN](#LEAN) | Priorise la vitesse et réduit la consommation de ressources en omettant la prise en charge des mises en page complexes. |
| [MULTICOLUMN](#MULTICOLUMN) | Détecte de grands blocs de texte formatés en colonnes. |
| [TABLE](#TABLE) | Détecte les structures tabulaires dans l'image et extrait le texte des cellules individuelles. |
| [UNIVERSAL](#UNIVERSAL) | Détecte tous les blocs de texte dans l'image, y compris le texte clairsemé et irrégulier sur les photos. |

### CURVED_TEXT {#CURVED-TEXT}
```
public static final DetectAreasMode CURVED_TEXT
```


Redresse automatiquement les lignes de texte courbes dans l'image, améliorant la précision de la reconnaissance et permettant de récupérer et d'extraire davantage de texte. Nécessite une puissance de traitement et une RAM importantes.

### FORMULA {#FORMULA}
```
public static final DetectAreasMode FORMULA
```


Détecte tous les blocs contenant des formules mathématiques.

### LEAN {#LEAN}
```
public static final DetectAreasMode LEAN
```


Priorise la vitesse et réduit la consommation de ressources en omettant la prise en charge des mises en page complexes. Convient uniquement aux images simples avec quelques lignes de texte, sans illustrations ni mise en forme.

### MULTICOLUMN {#MULTICOLUMN}
```
public static final DetectAreasMode MULTICOLUMN
```


Détecte de grands blocs de texte formatés en colonnes. Meilleur choix pour les mises en page à plusieurs colonnes comme les pages de livres, les articles ou les contrats.

### TABLE {#TABLE}
```
public static final DetectAreasMode TABLE
```


Détecte les structures tabulaires dans l'image et extrait le texte des cellules individuelles. Recommandé pour les feuilles de calcul numérisées, les rapports et autres documents basés sur des tableaux.

### UNIVERSAL {#UNIVERSAL}
```
public static final DetectAreasMode UNIVERSAL
```


Détecte tous les blocs de texte dans l'image, y compris le texte clairsemé et irrégulier sur les photos. Une option polyvalente pour la plupart des images, sauf pour les tableaux et les mises en page à plusieurs colonnes.

