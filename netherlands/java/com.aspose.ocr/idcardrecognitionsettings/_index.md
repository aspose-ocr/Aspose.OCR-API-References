---
title: "IDCardRecognitionSettings"
second_title: "Aspose.OCR for Java API-referentie"
description: "Instellingen voor de ID-kaartherkenning bevatten elementen die het aanpassen van het herkenningsproces mogelijk maken."
type: docs
weight: 14
url: /nl/java/com.aspose.ocr/idcardrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class IDCardRecognitionSettings extends ReceiptRecognitionSettings
```

Instellingen voor de ID-kaartherkenning bevatten elementen die het aanpassen van het herkenningsproces mogelijk maken.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [IDCardRecognitionSettings()](#IDCardRecognitionSettings) | Standaardconstructor: stel autoSkew in op true. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Toegestane tekenset. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Toegestane tekenset. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detecteer afbeeldingen met witte tekst op een donkere/zwart achtergrond en kies automatisch een speciaal OCR‑algoritme hiervoor. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Stelt de zwarte lijst in voor herkenningssymbolen. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Specificeert het niveau van taaldetectie voor teksterkenning. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Haalt op of stelt het aantal threads in voor verwerking. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Staat toe extra algoritmen te gebruiken specifiek voor herkenning van kleine lettertypen. |
### IDCardRecognitionSettings() {#IDCardRecognitionSettings}
```
public IDCardRecognitionSettings()
```


Standaardconstructor: stel autoSkew in op true.



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
| allowedCharacters | java.lang.String | bevat een array van tekens. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detecteer afbeeldingen met witte tekst op een donkere/zwart achtergrond en kies automatisch een speciaal OCR‑algoritme hiervoor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| automaticColorInversion | boolean | bevat een booleaanse waarde - een automaticColorInversion is ingesteld. |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | enum-waarde om het niveau in te stellen (Paragraph, Word, Page). |

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

