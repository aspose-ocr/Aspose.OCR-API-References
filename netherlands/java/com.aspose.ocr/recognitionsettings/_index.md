---
title: "RecognitionSettings"
second_title: "Aspose.OCR for Java API-referentie"
description: "Instellingen voor de beeldherkenning"
type: docs
weight: 27
url: /nl/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Instellingen voor de beeldherkenning. Bevat elementen die het aanpassen van het herkenningsproces mogelijk maken.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Standaardconstructor: stel recognitionAreas in op null, linesFiltration op false, autoSkew op false, recognizeSingleLine op false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Constructor maakt het mogelijk alle opties in te stellen. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Constructor maakt het mogelijk recognizeSingleLine in te stellen. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Toegestane tekenset. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Toegestane tekenset. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detecteer afbeeldingen met witte tekst op een donkere/zwart achtergrond en kies automatisch een speciaal OCR‑algoritme hiervoor. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Bepaalt het type neuraal netwerk dat wordt gebruikt voor gebiedsdetectie. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Stelt de zwarte lijst in voor herkenningssymbolen. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Specificeert het niveau van taaldetectie voor teksterkenning. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Maakt het mogelijk tekst in tabellen te herkennen (regio's omgeven door lijnen). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Stelt de lijst met tekstgebieden in voor verwerking. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Stelt eenregelige beeldherkenning in. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Haalt op of stelt het aantal threads in voor verwerking. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Staat toe extra algoritmen te gebruiken specifiek voor herkenning van kleine lettertypen. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Standaardconstructor: stel recognitionAreas in op null, linesFiltration op false, autoSkew op false, recognizeSingleLine op false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Constructor maakt het mogelijk alle opties in te stellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rechthoeken voor herkenning. |
| recognizeSingleLine | boolean | True als de afbeelding slechts één regel bevat. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Constructor maakt het mogelijk om recognizeSingleLine in te stellen. Standaardwaarden in dit geval: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognizeSingleLine | boolean | True als de afbeelding slechts één regel bevat. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Toegestane tekenset. Bepaalt het type tekens dat is toegestaan voor het herkenningsresultaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | bevat enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) waarde. |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Toegestane tekenset. Bepaalt de array van tekens die zijn toegestaan voor het herkenningsresultaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| allowedCharacters | java.lang.String | bevat een tekenreeks. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detecteer afbeeldingen met witte tekst op een donkere/zwart achtergrond en kies automatisch een speciaal OCR‑algoritme hiervoor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| automaticColorInversion | boolean | bevat een booleaanse waarde - een automaticColorInversion is ingesteld. True standaard. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Bepaalt het type neuraal netwerk dat wordt gebruikt voor gebiedsdetectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | bevat enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) waarde. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Stelt de zwarte lijst in voor herkenningssymbolen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| characters | java.lang.String | Tekens uitgesloten van herkenning. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Stelt de taal in die wordt gebruikt voor OCR. Standaard meertalig (geen). |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Specificeert het niveau van taaldetectie voor teksterkenning. Werkt alleen als de geselecteerde taal Language.MULTILANGUAGE, Language.AUTO of Language.UNIVERSAL is. Dit proces kost veel tijd en vertraagt de algehele herkenning aanzienlijk.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Maakt het mogelijk tekst in tabellen te herkennen (regio's omgeven door lijnen).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linesFiltration | boolean | false - verbetert de prestaties en detecteert geen tabellen en verwijdert lijnen; anders - true. Standaard uitgeschakeld (false). |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Stelt de lijst met tekstgebieden in voor verwerking. Hiermee kunt u handmatig de gebieden met tekst opgeven voor nauwkeurigere herkenning. Als aangepaste gebieden zijn ingesteld [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} niet NONE of [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} eigenschappen worden genegeerd. Schakelt DetectAreas en AutoSkew uit.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rechthoeken voor herkenning. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Stelt herkenning van éénregelige afbeeldingen in. Standaard uitgeschakeld (false). Schakel alle verwerkingsstappen uit die verband houden met het splitsen in regels. Stel deze parameter in op true als uw afbeelding slechts één regel bevat. Schakelt [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) instellingen uit, zodat alle gebiedsinstellingen worden genegeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| recognizeSingleLine | boolean | True voor éénregelige afbeelding |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Haalt op of stelt het aantal threads in voor verwerking. Standaard betekent 0 dat de afbeelding wordt verwerkt met een aantal threads gelijk aan het aantal processoren. ThreadsCount = 1 betekent dat de afbeelding wordt verwerkt in de hoofdthread.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| threadsCount | int | het aantal threads dat zal worden aangemaakt voor parallelle herkenning van afbeeldingsfragmenten. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Staat toe extra algoritmen te gebruiken specifiek voor herkenning van kleine lettertypen. Handig voor afbeeldingen met kleine tekens.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| upscaleSmallFont | boolean | bevat een booleaanse waarde - een upscaleSmallFont is ingesteld. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String