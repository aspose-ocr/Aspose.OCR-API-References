---
title: "AsposeOCR"
second_title: "Aspose.OCR för Java API-referens"
description: "Huvudklass för att känna igen text från bilder"
type: docs
weight: 10
url: /sv/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Huvudklass för att känna igen text från bilder.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Publik konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [DebugMode](#DebugMode) | Aktiverar felsökningsläge. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Katalog där felsökningsresultat kommer att sparas. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Beräknar snedvinklarna för en bild. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Kontrollera om två bilder innehåller samma text. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Kontrollera om två bilder innehåller samma text. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Kontrollera om två bilder innehåller samma text. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Korrigerar text (ersätter felstavade ord). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Korrigerar text (ersätter felstavade ord). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Hittar automatiskt problematiska områden i en bild som kan påverka OCR‑noggrannheten avsevärt. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Analyserar bilden och identifierar de olika typerna av innehållsområden i den. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Analyserar texten på bilden för att bestämma vilka språk den är skriven på. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Detekterar textområden på bilder. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Detekterar tabellregioner på bilder. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Kontrollera om bilden innehåller det angivna textfragmentet med en skiftlägesokänslig sökning. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Kontrollera om bilden innehåller det angivna textfragmentet med en skiftlägesokänslig sökning. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Kontrollera om bilden innehåller det angivna textfragmentet. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Kontrollera om bildens text matchar det angivna reguljära uttrycket. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Kontrollera om bildens text matchar det angivna reguljära uttrycket. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Känner igen bild med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Känner igen bild med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Känner igen registreringsskylt med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Detekterar symboler på bilder. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Detekterar symboler på bilder. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Känner igen text på bild av god kvalitet. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Känner igen matematiska formler från de angivna inmatningsbilderna. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Känner igen handskriven text på bilder. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Känner igen ID‑kort med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Känner igen faktura med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Känner igen pass med möjlighet att specificera. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Känner igen kvitton med möjlighet att specificera Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip-arkiv, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Detektera tabeller och struktur, känner igen textceller. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt med stavningskontrollkorrektion. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Publik konstruktor.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Aktiverar felsökningsläge. När det är aktiverat sparar systemet mellansteg i bildbehandlingen, såsom förbehandlade bilder och bilder med ritade rektanglar för textlinjer.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Katalog där felsökningsresultat sparas. Om den inte är angiven används standardmässigt den aktuella arbetskatalogen.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Beräknar snedvinklar för en bild. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip-arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - ArrayList med snedvinklar i grader [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Kontrollera om två bilder innehåller samma text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath1 | java.lang.String | Sökväg till den första bilden. |
| fullPath2 | java.lang.String | Sökväg till den andra bilden. |

**Returns:**
boolean - Sant om bilderna har samma text (90 % likhet).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Kontrollera om två bilder innehåller samma text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath1 | java.lang.String | Sökväg till den första bilden. |
| fullPath2 | java.lang.String | Sökväg till den andra bilden. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |

**Returns:**
boolean - Sant om bilderna har samma text (90 % likhet).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Kontrollera om två bilder innehåller samma text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath1 | java.lang.String | Sökväg till den första bilden. |
| fullPath2 | java.lang.String | Sökväg till den andra bilden. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |
| ignoreCase | boolean | Sant - betyder en skiftlägesokänslig sökning. |

**Returns:**
boolean - Sant om bilderna har samma text (90 % likhet).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Korrigerar text (ersätter felstavade ord).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text för korrigering. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Ordbok att använda [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Text med ersatta ord.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Korrigerar text (ersätter felstavade ord).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Text för korrigering. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Ordbok att använda [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Fullständig sökväg till användarordboken (frekvensordbok). Filformat för ordboken: Vanlig textfil i UTF-8‑kodning. Ord och ordfrekvens separeras med kommatecken, ordet förväntas i den första kolumnen och frekvensen i den andra kolumnen. Varje ord‑frekvens‑par på en separat rad. En rad definieras som en sekvens av tecken följd av en radmatning ("\\n"), ett vagnretur ("\\r"), eller ett vagnretur omedelbart följt av en radmatning ("\\r\\n"). Alla ord förväntas vara i gemener. |

**Returns:**
java.lang.String - Text med ersatta ord.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Hitta automatiskt problematiska områden i en bild som kan påverka OCR‑noggrannheten avsevärt. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip-arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Typerna av defekter som ska kännas igen [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList av [DefectOutput](../../com.aspose.ocr/defectoutput/) med upptäckta textområden eller rader.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analyserar bilden och identifierar de olika typerna av innehållsområden i den. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Upptäckta innehållsområden. ArrayList av [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analyserar texten på bilden för att bestämma vilka språk den är skriven på. Detta möjliggör att välja det mest lämpliga igenkänningsspråket och hjälper i vidare textbehandlingsuppgifter såsom stavningskontroll eller översättning. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Returnerar en lista över de mest sannolika språken, rangordnade efter sannolikhet. ArrayList av [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Detekterar textområden på bilder. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Bestämmer vilka rektanglar som ska returneras - linje eller stycken. |
| isDetectAreas | boolean | Aktivera automatisk detektering av textområden. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList av [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) med upptäckta textområden eller rader.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Detekterar tabellregioner på bilder. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList av [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) med upptäckta tabellområden.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Kontrollera om bilden innehåller det angivna textfragmentet med en skiftlägesokänslig sökning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden. |
| text | java.lang.String | Textfragment för sökning på bilden. |

**Returns:**
boolean - Sant om bilden innehåller textfragment. Falskt - bilden innehåller inte textfragment.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Kontrollera om bilden innehåller det angivna textfragmentet med en skiftlägesokänslig sökning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden. |
| text | java.lang.String | Textfragment för sökning på bilden. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |

**Returns:**
boolean - Sant om bilden innehåller textfragment. Falskt - bilden innehåller inte textfragment.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Kontrollera om bilden innehåller det angivna textfragmentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden. |
| text | java.lang.String | Textfragment för sökning på bilden. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |
| ignoreCase | boolean | Sant - betyder en skiftlägesokänslig sökning. |

**Returns:**
boolean - Sant om bilden innehåller textfragment. Falskt - bilden innehåller inte textfragment.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Kontrollera om bildens text matchar det angivna reguljära uttrycket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern-objekt med det angivna mönstret och alternativen. |

**Returns:**
boolean - Sant om bildtexten matchar det angivna reguljära uttrycket.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Kontrollera om bildens text matchar det angivna reguljära uttrycket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath | java.lang.String | Sökväg till bilden. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern-objekt med det angivna mönstret och alternativen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |

**Returns:**
boolean - Sant om bildtexten matchar det angivna reguljära uttrycket.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath1 | java.lang.String | Sökväg till den första bilden. |
| fullPath2 | java.lang.String | Sökväg till den andra bilden. |

**Returns:**
float - 0 betyder att texterna är helt olika; 1 betyder att texterna är identiska.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath1 | java.lang.String | Sökväg till den första bilden. |
| fullPath2 | java.lang.String | Sökväg till den andra bilden. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |

**Returns:**
float - 0 betyder att texterna är helt olika; 1 betyder att texterna är identiska.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullPath1 | java.lang.String | Sökväg till den första bilden. |
| fullPath2 | java.lang.String | Sökväg till den andra bilden. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Inställningar för igenkänning. |
| ignoreCase | boolean | Sant - betyder en skiftlägesokänslig sökning. |

**Returns:**
float - 0 betyder att texterna är helt olika; 1 betyder att texterna är identiska.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Känner igen bild med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Känner igen bild med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Känner igen registreringsskylt med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Detekterar symboler på bilder. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList av [Character](../../com.aspose.ocr.models/character/) med data för upptäckta symboler för varje bild.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Detekterar symboler på bilder. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Behållaren med källor.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Bestämmer typen av neuralt nätverk som används för områdesdetektering. |
| language | [Language](../../com.aspose.ocr.models/language/) | Språk som används för OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList av [Character](../../com.aspose.ocr.models/character/) med data för upptäckta symboler.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Känner igen text på bild av god kvalitet. Använder inte automatisk korrigering av bildskevhet och detektering av textområden. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/)‑instans. |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList med igenkänd text.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Känner igen matematiska formler från de angivna inmatningsbilderna. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| detectAreas | boolean | Om den är satt till true detekteras och isoleras formelområden automatiskt innan igenkänning utförs. Om den är false behandlas hela bilden som en formel. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Känner igen handskriven text på bilder. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Behållaren med källor.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Känner igen ID‑kort med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Känner igen faktura med möjlighet att specificera stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Känner igen pass med möjlighet att specificera. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Känner igen kvitton med möjlighet att specificera Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip-arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Detektera tabeller och struktur, känner igen textceller. Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, mapp, array, zip‑arkiv, URL, base64.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instans. |
| language | [Language](../../com.aspose.ocr.models/language/) | Bestämmer alfabetet som används under igenkänning. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - OCRTablePage‑listobjekt med igenkänd text i tabeller. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream för att spara igenkänningsresultat i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt med stavningskontrollkorrektion.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) enum‑värde. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lista över [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objekt. |
| embeddedFontPath | java.lang.String | Valfritt. Fullständig sökväg till användarens teckensnitt. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### close() {#close}
```
public void close()
```