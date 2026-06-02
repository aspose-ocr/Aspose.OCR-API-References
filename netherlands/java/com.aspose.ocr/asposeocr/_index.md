---
title: "AsposeOCR"
second_title: "Aspose.OCR for Java API-referentie"
description: "Hoofdklasse voor het herkennen van tekst uit afbeeldingen"
type: docs
weight: 10
url: /nl/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Hoofdklasse voor het herkennen van tekst uit afbeeldingen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Publieke constructor. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [DebugMode](#DebugMode) | Schakelt debugmodus in. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Map waarin debugresultaten worden opgeslagen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Berekent de scheefstandhoeken van een afbeelding. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Controleer of twee afbeeldingen dezelfde tekst bevatten. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Controleer of twee afbeeldingen dezelfde tekst bevatten. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Controleer of twee afbeeldingen dezelfde tekst bevatten. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corrigeert tekst (vervangt verkeerd gespelde woorden). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Corrigeert tekst (vervangt verkeerd gespelde woorden). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Zoekt automatisch problematische gebieden van een afbeelding die de nauwkeurigheid van OCR aanzienlijk kunnen beïnvloeden. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Analyseert de afbeelding en identificeert de verschillende soorten inhoudsgebieden erin. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Analyseert de tekst op de afbeelding om de talen waarin deze is geschreven te bepalen. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Detecteert tekstgebieden op afbeeldingen. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Detecteert tabelgebieden op afbeeldingen. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Controleer of de afbeelding het opgegeven tekstfragment bevat met een hoofdletterongevoelige zoekopdracht. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Controleer of de afbeelding het opgegeven tekstfragment bevat met een hoofdletterongevoelige zoekopdracht. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Controleer of de afbeelding het opgegeven tekstfragment bevat. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Controleer of de tekst van de afbeelding overeenkomt met de opgegeven reguliere expressie. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Controleer of de tekst van de afbeelding overeenkomt met de opgegeven reguliere expressie. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Herken afbeelding met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Herken afbeelding met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Herken kentekenplaat met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Detecteert symbolen op afbeeldingen. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Detecteert symbolen op afbeeldingen. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Herken tekst op een afbeelding van goede kwaliteit. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Herken wiskundige formules van de opgegeven invoerafbeeldingen. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Herken handgeschreven tekst op afbeeldingen. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Herken identiteitskaart met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Herken factuur met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Herkent paspoort met de mogelijkheid om te specificeren. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Herkenning van bonnetjes met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Detecteert tabellen en structuur, herkent tekstcellen. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten met spellingscontrolecorrectie. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Publieke constructor.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Schakelt de debug-modus in. Wanneer ingeschakeld, slaat het systeem tussenresultaten van beeldverwerking op, zoals voorbewerkte afbeeldingen en afbeeldingen met getekende tekstregel-rechthoeken.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Map waarin debugresultaten worden opgeslagen. Indien niet ingesteld, wordt standaard de huidige werkmap gebruikt.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Berekent de scheefstandhoeken van een afbeelding. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - ArrayList van scheefstandhoeken in graden [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Controleer of twee afbeeldingen dezelfde tekst bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pad naar de eerste afbeelding. |
| fullPath2 | java.lang.String | Pad naar de tweede afbeelding. |

**Returns:**
boolean - Waar als afbeeldingen dezelfde tekst hebben (90% overeenkomst).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Controleer of twee afbeeldingen dezelfde tekst bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pad naar de eerste afbeelding. |
| fullPath2 | java.lang.String | Pad naar de tweede afbeelding. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |

**Returns:**
boolean - Waar als afbeeldingen dezelfde tekst hebben (90% overeenkomst).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Controleer of twee afbeeldingen dezelfde tekst bevatten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pad naar de eerste afbeelding. |
| fullPath2 | java.lang.String | Pad naar de tweede afbeelding. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |
| ignoreCase | boolean | Waar - betekent een hoofdletterongevoelige zoekopdracht. |

**Returns:**
boolean - Waar als afbeeldingen dezelfde tekst hebben (90% overeenkomst).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Corrigeert tekst (vervangt verkeerd gespelde woorden).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor correctie. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Te gebruiken woordenboek [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Tekst met vervangen woorden.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Corrigeert tekst (vervangt verkeerd gespelde woorden).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Tekst voor correctie. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Te gebruiken woordenboek [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Volledig pad naar het gebruikerswoordenboek (frequentiewoordenboek). Formaat van het woordenboekbestand: platte tekstbestand in UTF-8-codering. Woord en woordfrequentie worden gescheiden door een komma; het woord wordt verwacht in de eerste kolom en de frequentie in de tweede kolom. Elk woord-frequentie-paar staat op een aparte regel. Een regel wordt gedefinieerd als een reeks tekens gevolgd door een regeleinde ("\\n"), een carriage return ("\\r"), of een carriage return direct gevolgd door een regeleinde ("\\r\\n"). Elk woord wordt verwacht in kleine letters. |

**Returns:**
java.lang.String - Tekst met vervangen woorden.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Automatisch problematische gebieden van een afbeelding vinden die de nauwkeurigheid van OCR aanzienlijk kunnen beïnvloeden. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | De typen defecten die herkend moeten worden [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList van [DefectOutput](../../com.aspose.ocr/defectoutput/) met gedetecteerde tekstgebieden of -regels.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analyseert de afbeelding en identificeert de verschillende soorten inhoudsgebieden daarin. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Gedetecteerde inhoudsgebieden. ArrayList van [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analyseert de tekst op de afbeelding om de talen waarin deze is geschreven te bepalen. Dit maakt het mogelijk de meest geschikte herkenningstaal te selecteren en helpt bij verdere tekstverwerkingstaken zoals spellingscontrole of vertaling. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Retourneert een lijst van de meest waarschijnlijke talen, gerangschikt op waarschijnlijkheid. ArrayList van [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Detecteert tekstgebieden op afbeeldingen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Bepaalt welke rechthoeken moeten worden geretourneerd - regel of alinea's. |
| isDetectAreas | boolean | Schakel automatische detectie van tekstgebieden in. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList van [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) met gedetecteerde tekstgebieden of regels.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Detecteert tabelgebieden op afbeeldingen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList van [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) met gedetecteerde tabelgebieden.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Controleer of de afbeelding het opgegeven tekstfragment bevat met een hoofdletterongevoelige zoekopdracht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding. |
| text | java.lang.String | Tekstfragment voor zoeken op de afbeelding. |

**Returns:**
True als de afbeelding het tekstfragment bevat. False - afbeelding bevat het tekstfragment niet.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Controleer of de afbeelding het opgegeven tekstfragment bevat met een hoofdletterongevoelige zoekopdracht.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding. |
| text | java.lang.String | Tekstfragment voor zoeken op de afbeelding. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |

**Returns:**
True als de afbeelding het tekstfragment bevat. False - afbeelding bevat het tekstfragment niet.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Controleer of de afbeelding het opgegeven tekstfragment bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding. |
| text | java.lang.String | Tekstfragment voor zoeken op de afbeelding. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |
| ignoreCase | boolean | Waar - betekent een hoofdletterongevoelige zoekopdracht. |

**Returns:**
True als de afbeelding het tekstfragment bevat. False - afbeelding bevat het tekstfragment niet.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Controleer of de tekst van de afbeelding overeenkomt met de opgegeven reguliere expressie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern-object met het opgegeven patroon en opties. |

**Returns:**
boolean - True als de afbeeldingstekst overeenkomt met de opgegeven reguliere expressie.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Controleer of de tekst van de afbeelding overeenkomt met de opgegeven reguliere expressie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath | java.lang.String | Pad naar de afbeelding. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern-object met het opgegeven patroon en opties. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |

**Returns:**
boolean - True als de afbeeldingstekst overeenkomt met de opgegeven reguliere expressie.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pad naar de eerste afbeelding. |
| fullPath2 | java.lang.String | Pad naar de tweede afbeelding. |

**Returns:**
float - 0 betekent dat de teksten volledig verschillend zijn; 1 betekent dat de teksten identiek zijn.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pad naar de eerste afbeelding. |
| fullPath2 | java.lang.String | Pad naar de tweede afbeelding. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |

**Returns:**
float - 0 betekent dat de teksten volledig verschillend zijn; 1 betekent dat de teksten identiek zijn.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pad naar de eerste afbeelding. |
| fullPath2 | java.lang.String | Pad naar de tweede afbeelding. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Herkenningsinstellingen. |
| ignoreCase | boolean | Waar - betekent een hoofdletterongevoelige zoekopdracht. |

**Returns:**
float - 0 betekent dat de teksten volledig verschillend zijn; 1 betekent dat de teksten identiek zijn.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Herken afbeelding met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Herken afbeelding met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Herken kentekenplaat met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Detecteert symbolen op afbeeldingen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList van [Character](../../com.aspose.ocr.models/character/) met gedetecteerde symboolgegevens voor elke afbeelding.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Detecteert symbolen op afbeeldingen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | De container met bronnen.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Bepaalt het type neuraal netwerk dat wordt gebruikt voor gebiedsdetectie. |
| language | [Language](../../com.aspose.ocr.models/language/) | Taal die wordt gebruikt voor OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList van [Character](../../com.aspose.ocr.models/character/) met gedetecteerde symboolgegevens.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Herkent tekst op een afbeelding van goede kwaliteit. Maakt geen gebruik van automatische correctie van beeldscheefstand en detectie van tekstgebieden. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) instantie. |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList met herkende tekst.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Herkent wiskundige formules uit de opgegeven invoerafbeeldingen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| detectAreas | boolean | Indien ingesteld op true, detecteert en isoleert automatisch formulesegmenten voordat herkenning wordt uitgevoerd. Indien false, wordt de volledige afbeelding als een formule verwerkt. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Herkent handgeschreven tekst op afbeeldingen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). De container met bronnen.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Herken identiteitskaart met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Herken factuur met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Herkent paspoorten met de mogelijkheid om te specificeren. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Herkenning van bonnetjes met de mogelijkheid om te specificeren Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip-archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Detecteert tabellen en structuur, herkent tekstcellen. Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, map, array, zip‑archief, URL, base64.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). instantie. |
| language | [Language](../../com.aspose.ocr.models/language/) | Bepaalt het alfabet dat tijdens herkenning wordt gebruikt. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - OCRTablePage-lijstobjecten met herkende teksten in tabellen. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten met spellingscontrolecorrectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) enumwaarde. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fullFileName | java.lang.String | Bestandsnaam met een pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Documentformaat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Lijst van [RecognitionResult](../../com.aspose.ocr/recognitionresult/). objecten. |
| embeddedFontPath | java.lang.String | Optioneel. Volledig pad naar het gebruikerslettertype. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Verminder de PDF-bestandsgrootte door de kwaliteit van achtergrondafbeeldingen te verlagen. Standaard wordt de oorspronkelijke beeldkwaliteit behouden. |

### close() {#close}
```
public void close()
```