---
title: "RecognitionSettings"
second_title: "Aspose.OCR för Java API-referens"
description: "Inställningar för bildigenkänning"
type: docs
weight: 27
url: /sv/java/com.aspose.ocr/recognitionsettings/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionSettings
```

Inställningar för bildigenkänning. Innehåller element som möjliggör anpassning av igenkänningsprocessen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RecognitionSettings()](#RecognitionSettings) | Standardkonstruktor: sätt recognitionAreas till null, linesFiltration till false, autoSkew till false, recognizeSingleLine till false. |
| [RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)](#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean) | Konstruktor tillåter att sätta alla alternativ. |
| [RecognitionSettings(boolean recognizeSingleLine)](#RecognitionSettings-boolean) | Konstruktor tillåter att sätta recognizeSingleLine. |
| [RecognitionSettings(ReceiptRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings) |  |
| [RecognitionSettings(InvoiceRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings) |  |
| [RecognitionSettings(IDCardRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings) |  |
| [RecognitionSettings(PassportRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings) |  |
| [RecognitionSettings(CarPlateRecognitionSettings recSettings)](#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setAllowedCharacters(CharactersAllowedType allowedCharacters)](#setAllowedCharacters-com.aspose.ocr.models.CharactersAllowedType) | Tillåtet teckenset. |
| [setAllowedCharacters(String allowedCharacters)](#setAllowedCharacters-java.lang.String) | Tillåtet teckenset. |
| [setAutomaticColorInversion(boolean automaticColorInversion)](#setAutomaticColorInversion-boolean) | Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem. |
| [setDetectAreasMode(DetectAreasMode detectAreasMode)](#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode) | Bestämmer typen av neuralt nätverk som används för områdesdetektering. |
| [setIgnoredCharacters(String characters)](#setIgnoredCharacters-java.lang.String) | Ställer in svartlista för igenkänningssymboler. |
| [setLanguage(Language language)](#setLanguage-com.aspose.ocr.models.Language) |  |
| [setLanguageDetectionLevel(LanguageDetectionLevel languageDetectionLevel)](#setLanguageDetectionLevel-com.aspose.ocr.models.LanguageDetectionLevel) | Anger nivån för språkdetektion för textigenkänning. |
| [setLinesFiltration(boolean linesFiltration)](#setLinesFiltration-boolean) | Tillåter att känna igen text i tabeller (regioner omgivna av linjer). |
| [setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)](#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle) | Ställer in listan över textområden för bearbetning. |
| [setRecognizeSingleLine(boolean recognizeSingleLine)](#setRecognizeSingleLine-boolean) | Ställer in enradig bildigenkänning. |
| [setThreadsCount(int threadsCount)](#setThreadsCount-int) | Hämtar eller ställer in antalet trådar för bearbetning. |
| [setUpscaleSmallFont(boolean upscaleSmallFont)](#setUpscaleSmallFont-boolean) | Tillåter dig att använda ytterligare algoritmer specifikt för igenkänning av små teckensnitt. |
### RecognitionSettings() {#RecognitionSettings}
```
public RecognitionSettings()
```


Standardkonstruktor: sätt recognitionAreas till null, linesFiltration till false, autoSkew till false, recognizeSingleLine till false.

### RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine) {#RecognitionSettings-java.util.ArrayList-java.awt.Rectangle--boolean}
```
public RecognitionSettings(ArrayList<Rectangle> recognitionAreas, boolean recognizeSingleLine)
```


Konstruktor tillåter att sätta alla alternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rektanglar för igenkänning. |
| recognizeSingleLine | boolean | Sant om bilden innehåller endast en rad. |

### RecognitionSettings(boolean recognizeSingleLine) {#RecognitionSettings-boolean}
```
public RecognitionSettings(boolean recognizeSingleLine)
```


Konstruktorn tillåter att sätta recognizeSingleLine. Standardvärden i detta fall: detectAreas - false, autoSkew = false, recognitionAreas - null.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recognizeSingleLine | boolean | Sant om bilden innehåller endast en rad. |

### RecognitionSettings(ReceiptRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.ReceiptRecognitionSettings}
```
public RecognitionSettings(ReceiptRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recSettings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) |  |

### RecognitionSettings(InvoiceRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.InvoiceRecognitionSettings}
```
public RecognitionSettings(InvoiceRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recSettings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) |  |

### RecognitionSettings(IDCardRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.IDCardRecognitionSettings}
```
public RecognitionSettings(IDCardRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recSettings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) |  |

### RecognitionSettings(PassportRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.PassportRecognitionSettings}
```
public RecognitionSettings(PassportRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recSettings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) |  |

### RecognitionSettings(CarPlateRecognitionSettings recSettings) {#RecognitionSettings-com.aspose.ocr.CarPlateRecognitionSettings}
```
public RecognitionSettings(CarPlateRecognitionSettings recSettings)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recSettings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) |  |




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
| allowedCharacters | java.lang.String | innehåller en teckensträng. |

### setAutomaticColorInversion(boolean automaticColorInversion) {#setAutomaticColorInversion-boolean}
```
public void setAutomaticColorInversion(boolean automaticColorInversion)
```


Detektera bilder med vit text på mörk/svart bakgrund och automatiskt välja en speciell OCR-algoritm för dem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| automaticColorInversion | boolean | innehåller ett booleskt värde - en automaticColorInversion är satt. Sant som standard. |

### setDetectAreasMode(DetectAreasMode detectAreasMode) {#setDetectAreasMode-com.aspose.ocr.models.DetectAreasMode}
```
public void setDetectAreasMode(DetectAreasMode detectAreasMode)
```


Bestämmer typen av neuralt nätverk som används för områdesdetektering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | innehåller enum @see [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) värde. |

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
| languageDetectionLevel | [LanguageDetectionLevel](../../com.aspose.ocr.models/languagedetectionlevel/) |  |

### setLinesFiltration(boolean linesFiltration) {#setLinesFiltration-boolean}
```
public void setLinesFiltration(boolean linesFiltration)
```


Tillåter att känna igen text i tabeller (regioner omgivna av linjer).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| linesFiltration | boolean | false - möjliggör ökad prestanda och upptäcker inte tabeller samt tar bort rader; annars - true. Inaktiverad (false) som standard. |

### setRecognitionAreas(ArrayList<Rectangle> recognitionAreas) {#setRecognitionAreas-java.util.ArrayList-java.awt.Rectangle}
```
public void setRecognitionAreas(ArrayList<Rectangle> recognitionAreas)
```


Ställer in listan med textområden för bearbetning. Tillåter att manuellt specificera områden med text för mer exakt igenkänning. Om anpassade områden är satta [setDetectAreasMode(DetectAreasMode)](../../com.aspose.ocr/recognitionsettings/\#setDetectAreasMode-DetectAreasMode) (DetectAreasMode)\} inte NONE eller [PreprocessingFilter.AutoSkew()](../../com.aspose.ocr/preprocessingfilter/\#AutoSkew) (boolean)\} egenskaper kommer att ignoreras. Inaktiverar DetectAreas och AutoSkew.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recognitionAreas | java.util.ArrayList<java.awt.Rectangle> | Rektanglar för igenkänning. |

### setRecognizeSingleLine(boolean recognizeSingleLine) {#setRecognizeSingleLine-boolean}
```
public void setRecognizeSingleLine(boolean recognizeSingleLine)
```


Ställer in igenkänning av enradig bild. Inaktiverad (false) som standard. Inaktiverar alla bearbetningssteg som är kopplade till att dela upp i rader. Sätt denna parameter till true om din bild endast innehåller en rad. Inaktiverar [setRecognitionAreas(ArrayList)](../../com.aspose.ocr/recognitionsettings/\#setRecognitionAreas-ArrayList) inställningar, så att alla områdesinställningar ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| recognizeSingleLine | boolean | Sant för enradig bild |

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
| upscaleSmallFont | boolean | innehåller ett booleskt värde - en upscaleSmallFont är satt. |

### toString() {#toString}
```
public String toString()
```




**Returns:**
java.lang.String