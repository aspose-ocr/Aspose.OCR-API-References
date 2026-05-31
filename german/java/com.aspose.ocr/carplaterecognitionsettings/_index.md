---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Einstellungen für die Kfz‑Nummernerkennung enthalten Elemente, die die Anpassung des Erkennungsprozesses ermöglichen."
type: docs
weight: 12
url: /de/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Einstellungen für die Kfz‑Nummernerkennung enthalten Elemente, die die Anpassung des Erkennungsprozesses ermöglichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Standardkonstruktor: setze autoSkew auf true. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Erlaubte Zeichenmenge. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Erkennen Sie Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählen Sie automatisch einen speziellen OCR‑Algorithmus dafür. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Legt die Blacklist für Erkennungssymbole fest. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Standardkonstruktor: setze autoSkew auf true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Erlaubte Zeichenmenge. Bestimmt die Art der Zeichen, die für das Erkennungsergebnis zulässig sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | enthält enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) Wert. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Erkennen Sie Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählen Sie automatisch einen speziellen OCR‑Algorithmus dafür.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| automaticColorInversion | boolean | enthält booleschen Wert – ein automaticColorInversion ist gesetzt. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Legt die Blacklist für Erkennungssymbole fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| characters | java.lang.String | Von der Erkennung ausgeschlossene Zeichen. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Legt die für OCR verwendete Sprache fest. Standardmäßig Mehrsprachig (keine). |

