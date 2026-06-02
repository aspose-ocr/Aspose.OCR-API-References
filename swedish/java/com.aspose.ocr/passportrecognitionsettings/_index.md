---
title: "PassportRecognitionSettings"
second_title: "Aspose.OCR för Java API-referens"
description: "Inställningar för passigenkänning innehåller element som möjliggör anpassning av igenkänningsprocessen"
type: docs
weight: 23
url: /sv/java/com.aspose.ocr/passportrecognitionsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.ocr.ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/)
```
public class PassportRecognitionSettings extends ReceiptRecognitionSettings
```

Inställningar för passigenkänning innehåller element som möjliggör anpassning av igenkänningsprocessen
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PassportRecognitionSettings()](#PassportRecognitionSettings) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Tillåtet teckenset. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Tillåtet teckenset. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem. |
| [setCountry(Country country)](#setCountry-com.aspose.ocr.models.Country) | Ange mallen för passigenkänning och för att extrahera nyckelorden. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ställer in svartlista för igenkänningssymboler. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Anger nivån för språkdetektion för textigenkänning. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Hämtar eller ställer in antalet trådar för bearbetning. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Tillåter dig att använda ytterligare algoritmer specifikt för igenkänning av små teckensnitt. |
### PassportRecognitionSettings() {#PassportRecognitionSettings}
```
public PassportRecognitionSettings()
```





### setAllowedCharacters(CharactersAllowedType allowedCharacters) {#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType}
```
public void setAllowedCharacters(CharactersAllowedType allowedCharacters)
```


Tillåtet teckenset. Bestämmer vilken typ av tecken som är tillåtna för igenkänningsresultatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowedCharacters | [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) | innehåller enum @see [CharactersAllowedType](../../com.aspose.ocr.models/charactersallowedtype/) värde. |

### setAllowedCharacters(String allowedCharacters) {#setAllowedCharacters-java.lang.String}
```
public void setAllowedCharacters(String allowedCharacters)
```


Tillåtet teckenset. Bestämmer arrayen av tecken som är tillåtna för igenkänningsresultatet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| allowedCharacters | java.lang.String | innehåller en array av tecken. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| automaticColorInversion | boolean | innehåller booleskt värde - en automaticColorInversion är inställd. |

### setCountry(Country country) {#setCountry-com.aspose.ocr.models.Country}
```
public void setCountry(Country country)
```


Ange mallen för passigenkänning och för att extrahera nyckelorden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| country | [Country](../../com.aspose.ocr.models/country/) | passportrik. |

### setIgnoredCharacters(String characters) {#setIgnoredCharacters-java.lang.String}
```
public void setIgnoredCharacters(String characters)
```


Ställer in svartlista för igenkänningssymboler.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| characters | java.lang.String | Tecken som exkluderas från igenkänning. |

### setLanguage(Language language) {#setLanguage-com.aspose.ocr.models.Language}
```
public void setLanguage(Language language)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| language | [Language](../../com.aspose.ocr.models/language/) | Ställer in språket som används för OCR. Fler språk (ingen) som standard. |

### setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel) {#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel}
```
public void setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)
```


Anger nivån för språkdetektion för textigenkänning. Fungerar endast om det valda språket är Language.MULTILANGUAGE, Language.AUTO eller Language.UNIVERSAL. Denna process är tidskrävande och saktar av den övergripande igenkänningen avsevärt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) | enum‑värde för att ställa in nivå (Paragraph, Word, Page). |

### setThreadsCount(int threadsCount) {#setThreadsCount-int}
```
public void setThreadsCount(int threadsCount)
```


Hämtar eller ställer in antalet trådar för bearbetning. Som standard betyder 0 att bilden kommer att bearbetas med ett antal trådar lika med antalet processorer du har. ThreadsCount = 1 betyder att bilden bearbetas i huvudtråden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threadsCount | int | antalet trådar som kommer att skapas för parallell igenkänning av bildfragment. |

### setUpscaleSmallFont(boolean upscaleSmallFont) {#setUpscaleSmallFont-boolean}
```
public void setUpscaleSmallFont(boolean upscaleSmallFont)
```


Tillåter dig att använda ytterligare algoritmer specifikt för igenkänning av små teckensnitt. Användbart för bilder med små tecken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| upscaleSmallFont | boolean | innehåller booleskt värde - en upscaleSmallFont är inställd. |
