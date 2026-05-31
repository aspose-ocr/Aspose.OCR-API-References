---
title: "CarPlateRecognitionSettings"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Paramètres pour la reconnaissance du numéro de voiture. Contient des éléments qui permettent de personnaliser le processus de reconnaissance."
type: docs
weight: 12
url: /fr/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Paramètres pour la reconnaissance du numéro de voiture. Contient des éléments qui permettent de personnaliser le processus de reconnaissance.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Constructeur par défaut : définir autoSkew sur true. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Ensemble de caractères autorisés. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Détecter les images avec du texte blanc sur fond sombre/noir et choisir automatiquement un algorithme OCR spécial pour celles‑ci. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Définit la liste noire pour les symboles de reconnaissance. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Constructeur par défaut : définir autoSkew sur true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Ensemble de caractères autorisés. Détermine le type de caractères autorisés pour le résultat de reconnaissance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | contient la valeur d'énumération @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/). |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Détecter les images avec du texte blanc sur fond sombre/noir et choisir automatiquement un algorithme OCR spécial pour celles‑ci.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| automaticColorInversion | boolean | contient une valeur booléenne - un automaticColorInversion est défini. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Définit la liste noire pour les symboles de reconnaissance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| characters | java.lang.String | Caractères exclus de la reconnaissance. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Définit la langue utilisée pour l'OCR. Multilingue (aucune) par défaut. |

