---
title: "RecognitionSettings"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Paramètres pour la reconnaissance d'image"
type: docs
weight: 27
url: /fr/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Paramètres pour la reconnaissance d'image. Contient des éléments qui permettent de personnaliser le processus de reconnaissance.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Constructeur par défaut : définir recognitionAreas à null, linesFiltration à false, autoSkew à false, recognizeSingleLine à false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Le constructeur permet de définir toutes les options. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Le constructeur permet de définir recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Ensemble de caractères autorisés. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Ensemble de caractères autorisés. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Détecter les images avec du texte blanc sur fond sombre/noir et choisir automatiquement un algorithme OCR spécial pour celles‑ci. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Détermine le type de réseau neuronal utilisé pour la détection des zones. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Définit la liste noire pour les symboles de reconnaissance. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Spécifie le niveau de détection de la langue pour la reconnaissance de texte. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Permet de reconnaître le texte dans les tableaux (régions entourées de lignes). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Définit la liste des zones de texte à traiter. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Définit la reconnaissance d'image à ligne unique. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Obtient ou définit le nombre de threads pour le traitement. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Vous permet d'utiliser des algorithmes supplémentaires spécifiquement pour la reconnaissance de petites polices. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Constructeur par défaut : définir recognitionAreas à null, linesFiltration à false, autoSkew à false, recognizeSingleLine à false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Le constructeur permet de définir toutes les options.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rectangles pour la reconnaissance. |
| recognizeSingleLine | boolean | Vrai si l'image ne contient qu'une seule ligne. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Le constructeur permet de définir recognizeSingleLine. Valeurs par défaut dans ce cas : detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognizeSingleLine | boolean | Vrai si l'image ne contient qu'une seule ligne. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Ensemble de caractères autorisés. Détermine le type de caractères autorisés pour le résultat de reconnaissance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | contient la valeur d'énumération @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Ensemble de caractères autorisés. Détermine le tableau de caractères autorisés pour le résultat de reconnaissance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| allowedCharacters | java.lang.String | contient une chaîne de caractères. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Détecter les images avec du texte blanc sur fond sombre/noir et choisir automatiquement un algorithme OCR spécial pour celles‑ci.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| automaticColorInversion | boolean | contient une valeur booléenne - une automaticColorInversion est définie. Vrai par défaut. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Détermine le type de réseau neuronal utilisé pour la détection des zones.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | contient la valeur d'énumération @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Définit la liste noire pour les symboles de reconnaissance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| characters | java.lang.String | Caractères exclus de la reconnaissance. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Définit la langue utilisée pour l'OCR. Multilingue (aucune) par défaut. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Spécifie le niveau de détection de la langue pour la reconnaissance de texte. Fonctionne uniquement si la langue sélectionnée est Language.MULTILANGUAGE, Language.AUTO ou Language.UNIVERSAL. Ce processus est long et ralentit considérablement la reconnaissance globale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Permet de reconnaître le texte dans les tableaux (régions entourées de lignes).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| linesFiltration | boolean | false - permet d'augmenter les performances et ne pas détecter les tableaux et supprimer les lignes ; sinon - true. Désactivé (false) par défaut. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Définit la liste des zones de texte à traiter. Permet de spécifier manuellement les zones contenant du texte pour une reconnaissance plus précise. Si des zones personnalisées sont définies [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\\} différent de NONE ou [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\\#AutoSkew) (boolean)\\} les propriétés seront ignorées. Désactive DetectAreas et AutoSkew.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rectangles pour la reconnaissance. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Définit la reconnaissance d'image à ligne unique. Désactivé (false) par défaut. Désactive toutes les étapes de traitement associées à la division en lignes. Réglez ce paramètre sur true si votre image ne contient qu'une seule ligne. Désactive les paramètres [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\\#setRecognitionAreas-ArrayList) , de sorte que tous les paramètres de zones seront ignorés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| recognizeSingleLine | boolean | Vrai pour une image à ligne unique |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Obtient ou définit le nombre de threads pour le traitement. Par défaut, 0 signifie que l'image sera traitée avec un nombre de threads égal à celui de vos processeurs. ThreadsCount = 1 signifie que l'image sera traitée dans le thread principal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threadsCount | int | le nombre de threads qui seront créés pour la reconnaissance parallèle des fragments d'image. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Vous permet d'utiliser des algorithmes supplémentaires spécifiquement pour la reconnaissance de petites polices. Utile pour les images contenant des caractères de petite taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| upscaleSmallFont | boolean | contient une valeur booléenne - une upscaleSmallFont est définie. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String