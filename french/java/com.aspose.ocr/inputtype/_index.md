---
title: "InputType"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Types d'images/documents pour le traitement/la reconnaissance"
type: docs
weight: 38
url: /fr/java/com.aspose.ocr/inputtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum InputType extends Enum<InputType>
```

Types d'images/documents pour le traitement/la reconnaissance.
## Champs

| Champ | Description |
| --- | --- |
| [Base64](#Base64) | Chaîne base64 contenant l'image ou le chemin vers le fichier .txt avec le contenu base64. |
| [Directory](#Directory) | Chemin vers le répertoire. |
| [PDF](#PDF) | Document PDF numérisé depuis un fichier ou depuis InputStream. |
| [SingleImage](#SingleImage) | Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage. |
| [TIFF](#TIFF) | Document TIFF multipage, TIF depuis un fichier ou depuis InputStream. |
| [URL](#URL) | Lien sur l'image. |
| [Zip](#Zip) | Nom complet de l'archive ZIP. |

### Base64 {#Base64}
```
public static final InputType Base64
```


Chaîne base64 contenant l'image ou le chemin vers le fichier .txt avec le contenu base64. Prend en charge GIF, PNG, JPEG, BMP, TIFF.

### Directory {#Directory}
```
public static final InputType Directory
```


Chemin vers le répertoire. Les archives et dossiers imbriqués ne sont pas pris en charge. Prend en charge GIF, PNG, JPEG, BMP, TIFF. Le nombre d'images traitées par défaut est toutes.

### PDF {#PDF}
```
public static final InputType PDF
```


Document PDF numérisé depuis un fichier ou depuis InputStream.

### SingleImage {#SingleImage}
```
public static final InputType SingleImage
```


Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF, InputStream, BufferedImage.

### TIFF {#TIFF}
```
public static final InputType TIFF
```


Document TIFF multipage, TIF depuis un fichier ou depuis InputStream.

### URL {#URL}
```
public static final InputType URL
```


Lien sur l'image. Prend en charge GIF, PNG, JPEG, BMP, TIFF.

### Zip {#Zip}
```
public static final InputType Zip
```


Nom complet de l'archive ZIP. Les archives et dossiers imbriqués ne sont pas pris en charge. Prend en charge GIF, PNG, JPEG, BMP, TIFF, JFIF. Le nombre d'images traitées par défaut est toutes.
