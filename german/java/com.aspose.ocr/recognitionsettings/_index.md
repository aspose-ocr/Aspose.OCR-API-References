---
title: "RecognitionSettings"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Einstellungen für die Bilderkennung"
type: docs
weight: 27
url: /de/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Einstellungen für die Bilderkennung. Enthält Elemente, die die Anpassung des Erkennungsprozesses ermöglichen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Standardkonstruktor: setzt recognitionAreas auf null, linesFiltration auf false, autoSkew auf false, recognizeSingleLine auf false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Konstruktor ermöglicht das Setzen aller Optionen. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Konstruktor ermöglicht das Setzen von recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Erlaubte Zeichenmenge. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Erlaubte Zeichenmenge. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Erkennen Sie Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählen Sie automatisch einen speziellen OCR‑Algorithmus dafür. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Bestimmt den Typ des für die Flächenerkennung verwendeten neuronalen Netzwerks. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Legt die Blacklist für Erkennungssymbole fest. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Gibt das Niveau der Spracherkennung für die Texterkennung an. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Ermöglicht das Erkennen von Text in Tabellen (Regionen, die von Linien umgeben sind). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Legt die Liste der Textbereiche für die Verarbeitung fest. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Legt die einzeilige Bilderkennung fest. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Liest oder setzt die Anzahl der Threads für die Verarbeitung. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Ermöglicht die Verwendung zusätzlicher Algorithmen speziell für die Erkennung kleiner Schriftarten. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Standardkonstruktor: setzt recognitionAreas auf null, linesFiltration auf false, autoSkew auf false, recognizeSingleLine auf false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Konstruktor ermöglicht das Setzen aller Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rechtecke zur Erkennung. |
| recognizeSingleLine | boolean | Wahr, wenn das Bild nur eine Zeile enthält. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Konstruktor ermöglicht das Setzen von recognizeSingleLine. Standardwerte in diesem Fall: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognizeSingleLine | boolean | Wahr, wenn das Bild nur eine Zeile enthält. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | enthält eine Zeichenkette. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Erkennen Sie Bilder mit weißem Text auf dunklem/schwarzem Hintergrund und wählen Sie automatisch einen speziellen OCR‑Algorithmus dafür.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| automaticColorInversion | boolean | enthält einen booleschen Wert – automaticColorInversion ist gesetzt. Standardmäßig wahr. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Bestimmt den Typ des für die Flächenerkennung verwendeten neuronalen Netzwerks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | enthält den Enum-Wert @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/). |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Ermöglicht das Erkennen von Text in Tabellen (Regionen, die von Linien umgeben sind).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linesFiltration | boolean | false – erhöht die Leistung und erkennt keine Tabellen und entfernt Zeilen; andernfalls – true. Standardmäßig deaktiviert (false). |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Legt die Liste der Textbereiche für die Verarbeitung fest. Ermöglicht das manuelle Angeben der Bereiche mit Text für genauere Erkennung. Wenn benutzerdefinierte Bereiche gesetzt sind [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} nicht NONE oder [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} Eigenschaften werden ignoriert. Deaktiviert DetectAreas und AutoSkew.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rechtecke zur Erkennung. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Legt die Erkennung von einzeiligen Bildern fest. Standardmäßig deaktiviert (false). Deaktiviert alle Verarbeitungsschritte, die mit dem Aufteilen in Zeilen verbunden sind. Setzen Sie diesen Parameter auf true, wenn Ihr Bild nur eine Zeile enthält. Deaktiviert die Einstellungen von [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList), sodass alle Bereichseinstellungen ignoriert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| recognizeSingleLine | boolean | Wahr für einzeiliges Bild |

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
| upscaleSmallFont | boolean | enthält einen booleschen Wert – upscaleSmallFont ist gesetzt. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String