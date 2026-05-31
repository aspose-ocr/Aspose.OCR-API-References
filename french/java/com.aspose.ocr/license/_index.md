---
title: "Licence"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Fournit des méthodes pour licencier le composant"
type: docs
weight: 21
url: /fr/java/com.aspose.ocr/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |

| [setLicense(File licenseFile)](#setLicense-java.io.File) | Licence le composant. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream) | Licence le composant. |
| [setLicense(String licenseFilePath)](#setLicense-java.lang.String) | Licence le composant. |
| [isValid()](#isValid--) | Vérifiez la licence. |
### License() {#License}
```
public License()
```


Initialise une nouvelle instance de cette classe.


### setLicense(File licenseFile) {#setLicense-java.io.File}
```
public static void setLicense(File licenseFile)
```


Licence le composant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseFile | java.io.File | représentation du chemin d'accès du fichier |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream}
```
public static void setLicense(InputStream stream)
```


Licence le composant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Un flux qui contient la licence. |

### setLicense(String licenseFilePath) {#setLicense-java.lang.String}
```
public static void setLicense(String licenseFilePath)
```


Licence le composant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseFilePath | java.lang.String | Peut être un nom de fichier complet ou court. Utilisez une chaîne vide pour passer en mode d'évaluation. |



### isValid() {#isValid--}
```
public static boolean isValid()
```


Vérifiez la licence.

**Returns:**
booléen - Valeur booléenne indiquant si la licence est valide.
