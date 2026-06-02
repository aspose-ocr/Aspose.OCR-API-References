---
title: "CarPlateRecognitionSettings"
second_title: "Aspose.OCR for Java API-referentie"
description: "Instellingen voor de kentekenherkenning bevatten elementen die het aanpassen van het herkenningsproces mogelijk maken."
type: docs
weight: 12
url: /nl/java/com.aspose.ocr/carplaterecognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class CarPlateRecognitionSettings
```

Instellingen voor de kentekenherkenning bevatten elementen die het aanpassen van het herkenningsproces mogelijk maken.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CarPlateRecognitionSettings()](#CarPlateRecognitionSettings) | Standaardconstructor: stel autoSkew in op true. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType) | Toegestane tekenset. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detecteer afbeeldingen met witte tekst op een donkere/zwart achtergrond en kies automatisch een speciaal OCR‑algoritme hiervoor. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Stelt de zwarte lijst in voor herkenningssymbolen. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.Language) |  |
### CarPlateRecognitionSettings() {#CarPlateRecognitionSettings}
```
public CarPlateRecognitionSettings()
```


Standaardconstructor: stel autoSkew in op true.





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Toegestane tekenset. Bepaalt het type tekens dat is toegestaan voor het herkenningsresultaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) | bevat enum @see [CharactersAllowedType](../../com.aspose.ocr/charactersallowedtype/) waarde. |

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

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr/language/) | Stelt de taal in die wordt gebruikt voor OCR. Standaard meertalig (geen). |

