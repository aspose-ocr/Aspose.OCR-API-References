---
title: "PassportRecognitionSettings"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Einstellungen für die Pass‑Erkennung enthalten Elemente, die die Anpassung des Erkennungsprozesses ermöglichen."
type: docs
weight: 23
url: /de/java/com.aspose.ocr/passportrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class PassportRecognitionSettings extends ReceiptRecognitionSettings
```

Einstellungen für die Pass‑Erkennung enthalten Elemente, die die Anpassung des Erkennungsprozesses ermöglichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PassportRecognitionSettings()](#PassportRecognitionSettings) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Erlaubte Zeichenmenge. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Erlaubte Zeichenmenge. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Erkennen Sie Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählen Sie automatisch einen speziellen OCR‑Algorithmus dafür. |
| [setCountry(Country country)](#setCountry-com.aspose.ocr.models.Country) | Legen Sie die Vorlage für die Passerkennung fest und extrahieren Sie die Schlüsselwörter. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Legt die Blacklist für Erkennungssymbole fest. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Gibt das Niveau der Spracherkennung für die Texterkennung an. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Liest oder setzt die Anzahl der Threads für die Verarbeitung. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Ermöglicht die Verwendung zusätzlicher Algorithmen speziell für die Erkennung kleiner Schriftarten. |
### PassportRecognitionSettings() {#PassportRecognitionSettings}
```
public PassportRecognitionSettings()
```





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Erlaubte Zeichenmenge. Bestimmt die Art der Zeichen, die für das Erkennungsergebnis zulässig sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | enthält enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) Wert. |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Erlaubte Zeichenmenge. Bestimmt das Array von Zeichen, die für das Erkennungsergebnis zulässig sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowedCharacters | java.lang.String | enthält ein Array von Zeichen. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Erkennen Sie Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählen Sie automatisch einen speziellen OCR‑Algorithmus dafür.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| automaticColorInversion | boolean | enthält booleschen Wert – ein automaticColorInversion ist gesetzt. |

### setCountry(Country country) {#setCountry-com.aspose.ocr.models.Country}
```
public void setCountry(Country country)
```


Legen Sie die Vorlage für die Passerkennung fest und extrahieren Sie die Schlüsselwörter.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| country | [Country](../../com.aspose.ocr.models/country/) | Passland. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Legt die Blacklist für Erkennungssymbole fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| characters | java.lang.String | Von der Erkennung ausgeschlossene Zeichen. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Legt die für OCR verwendete Sprache fest. Standardmäßig Mehrsprachig (keine). |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Gibt das Niveau der Spracherkennung für die Texterkennung an. Funktioniert nur, wenn die ausgewählte Sprache Language.MULTILANGUAGE, Language.AUTO oder Language.UNIVERSAL ist. Dieser Vorgang ist zeitaufwendig und verlangsamt die Gesamterkennung erheblich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | Enum-Wert zum Festlegen des Niveaus (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Liest oder setzt die Anzahl der Threads für die Verarbeitung. Standardmäßig bedeutet 0, dass das Bild mit einer Anzahl von Threads verarbeitet wird, die Ihrer Prozessoranzahl entspricht. ThreadsCount = 1 bedeutet, dass das Bild im Hauptthread verarbeitet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threadsCount | int | die Anzahl der Threads, die für die parallele Erkennung von Bildfragmenten erstellt werden. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Ermöglicht die Verwendung zusätzlicher Algorithmen speziell für die Erkennung kleiner Schriftarten. Nützlich für Bilder mit kleinformatigen Zeichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| upscaleSmallFont | boolean | enthält booleschen Wert – ein upscaleSmallFont ist gesetzt. |
