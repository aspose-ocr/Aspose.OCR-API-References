---
title: CarPlateRecognitionSettings
second_title: Aspose.OCR for Java API Reference
description: Settings for the car number recognition Contains elements that allow customizing the recognition process
type: docs
weight: 12
url: /java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Settings for the car number recognition Contains elements that allow customizing the recognition process
## Constructors

| Constructor | Description |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Default constructor: set autoSkew true. |
## Methods

| Method | Description |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Allowed characters set. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detect images with white text on dark/black background and automatically choose a special OCR algorithm for them. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Sets blacklist for recognition symbols. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setRetainImageForExport(boolean retainImageForExport)](#setRetainImageForExport-boolean) | Sets whether the preprocessed source image is retained in the recognition result. |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Default constructor: set autoSkew true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Allowed characters set. Determines the type of characters allowed for recognition result.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | contains enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) value. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detect images with white text on dark/black background and automatically choose a special OCR algorithm for them.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| automaticColorInversion | boolean | contains boolean value - a automaticColorInversion is set. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Sets blacklist for recognition symbols.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| characters | java.lang.String | Characters excluded from recognition. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Sets the language used for OCR. Multi-language (none) by default. |

### setRetainImageForExport(boolean retainImageForExport) {#setRetainImageForExport-boolean}
```
public void setRetainImageForExport(boolean retainImageForExport)
```


Sets whether the preprocessed source image is retained in the recognition result. Disabled ( false ) by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| retainImageForExport | boolean |  true  to retain the image for legacy export APIs. |