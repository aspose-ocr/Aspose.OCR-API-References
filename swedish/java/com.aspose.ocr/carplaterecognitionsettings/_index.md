---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR för Java API-referens"
description: "Inställningar för bilnummerigenkänning innehåller element som möjliggör anpassning av igenkänningsprocessen"
type: docs
weight: 12
url: /sv/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Inställningar för bilnummerigenkänning innehåller element som möjliggör anpassning av igenkänningsprocessen
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Standardkonstruktor: sätt autoSkew till true. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Tillåtet teckenset. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ställer in svartlista för igenkänningssymboler. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Standardkonstruktor: sätt autoSkew till true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Tillåtet teckenset. Bestämmer vilken typ av tecken som är tillåtna för igenkänningsresultatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | innehåller enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) värde. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| automaticColorInversion | boolean | innehåller booleskt värde - en automaticColorInversion är inställd. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Ställer in svartlista för igenkänningssymboler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| characters | java.lang.String | Tecken som exkluderas från igenkänning. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Ställer in språket som används för OCR. Fler språk (ingen) som standard. |

