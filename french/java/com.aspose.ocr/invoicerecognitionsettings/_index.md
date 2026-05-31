---
title: "InvoiceRecognitionSettings"
second_title: "Référence API d'Aspose.OCR pour Java"
description: "Paramètres pour la reconnaissance de factures. Contient des éléments qui permettent de personnaliser le processus de reconnaissance."
type: docs
weight: 17
url: /fr/java/com.aspose.ocr/invoicerecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class InvoiceRecognitionSettings extends ReceiptRecognitionSettings
```

Paramètres pour la reconnaissance de factures. Contient des éléments qui permettent de personnaliser le processus de reconnaissance.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [InvoiceRecognitionSettings()](#InvoiceRecognitionSettings) | Constructeur par défaut : définir autoSkew sur true. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Ensemble de caractères autorisés. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Ensemble de caractères autorisés. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Détecter les images avec du texte blanc sur fond sombre/noir et choisir automatiquement un algorithme OCR spécial pour celles‑ci. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Définit la liste noire pour les symboles de reconnaissance. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Spécifie le niveau de détection de la langue pour la reconnaissance de texte. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Obtient ou définit le nombre de threads pour le traitement. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Vous permet d'utiliser des algorithmes supplémentaires spécifiquement pour la reconnaissance de petites polices. |
### InvoiceRecognitionSettings() {#InvoiceRecognitionSettings}
```
public InvoiceRecognitionSettings()
```


Constructeur par défaut : définir autoSkew sur true.



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
| allowedCharacters | java.lang.String | contient un tableau de caractères. |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | valeur d'énumération pour définir le niveau (Paragraph, Word, Page). |

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
| upscaleSmallFont | boolean | contient une valeur booléenne - un upscaleSmallFont est défini. |
