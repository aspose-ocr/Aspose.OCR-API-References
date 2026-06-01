---
title: "AsposeOCR"
second_title: "Riferimento API di Aspose.OCR per Java"
description: "Classe principale per riconoscere il testo dalle immagini"
type: docs
weight: 10
url: /it/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Classe principale per riconoscere il testo dalle immagini.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Costruttore pubblico. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [DebugMode](#DebugMode) | Abilita la modalità di debug. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Directory in cui verranno salvati i risultati di debug. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Calcola gli angoli di inclinazione di un'immagine. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Verifica se due immagini contengono lo stesso testo. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Verifica se due immagini contengono lo stesso testo. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Verifica se due immagini contengono lo stesso testo. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Corregge il testo (sostituisce le parole errate). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Corregge il testo (sostituisce le parole errate). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Trova automaticamente le aree problematiche di un'immagine che possono influire significativamente sulla precisione dell'OCR. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Analizza l'immagine e identifica i diversi tipi di aree di contenuto al suo interno. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Analizza il testo sull'immagine per determinare le lingue in cui è scritto. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Rileva le aree di testo nelle immagini. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Rileva le regioni di tabelle nelle immagini. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Verifica se l'immagine contiene il frammento di testo fornito con una ricerca senza distinzione tra maiuscole e minuscole. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Verifica se l'immagine contiene il frammento di testo fornito con una ricerca senza distinzione tra maiuscole e minuscole. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Verifica se l'immagine contiene il frammento di testo fornito. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Verifica se il testo dell'immagine corrisponde all'espressione regolare fornita. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Verifica se il testo dell'immagine corrisponde all'espressione regolare fornita. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Riconosce immagini con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Riconosce immagini con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Riconosce targhe automobilistiche con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Rileva simboli nelle immagini. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Rileva simboli nelle immagini. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Riconosce il testo su immagini di buona qualità. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Riconosce formule matematiche dalle immagini di input fornite. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Riconosce il testo scritto a mano nelle immagini. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Riconosce carte d'identità con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Riconosce fatture con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Riconosce il passaporto con la possibilità di specificare. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Riconosce le ricevute con la possibilità di specificare Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Rileva tabelle e struttura, riconosce le celle di testo. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult con correzione ortografica. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Costruttore pubblico.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Abilita la modalità debug. Quando è attiva, il sistema salva i risultati intermedi dell'elaborazione delle immagini, come le immagini preelaborate e le immagini con rettangoli disegnati intorno alle linee di testo.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Directory in cui verranno salvati i risultati di debug. Se non impostata, verrà utilizzata per impostazione predefinita la directory di lavoro corrente.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Calcola gli angoli di inclinazione di un'immagine. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - ArrayList di angoli di inclinazione in gradi [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Verifica se due immagini contengono lo stesso testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath1 | java.lang.String | Percorso della prima immagine. |
| fullPath2 | java.lang.String | Percorso della seconda immagine. |

**Returns:**
boolean - True se le immagini hanno lo stesso testo (90% di somiglianza).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Verifica se due immagini contengono lo stesso testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath1 | java.lang.String | Percorso della prima immagine. |
| fullPath2 | java.lang.String | Percorso della seconda immagine. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |

**Returns:**
boolean - True se le immagini hanno lo stesso testo (90% di somiglianza).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Verifica se due immagini contengono lo stesso testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath1 | java.lang.String | Percorso della prima immagine. |
| fullPath2 | java.lang.String | Percorso della seconda immagine. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |
| ignoreCase | boolean | True - indica una ricerca case-insensitive. |

**Returns:**
boolean - True se le immagini hanno lo stesso testo (90% di somiglianza).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Corregge il testo (sostituisce le parole errate).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo per la correzione. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dizionario da utilizzare [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Testo con parole sostituite.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Corregge il testo (sostituisce le parole errate).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo per la correzione. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Dizionario da utilizzare [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Percorso completo del dizionario utente (dizionario di frequenza). Formato del file del dizionario: file di testo semplice in codifica UTF-8. La parola e la frequenza della parola sono separate da una virgola, la parola è prevista nella prima colonna e la frequenza nella seconda colonna. Ogni coppia parola-frequenza è su una riga separata. Una riga è definita come una sequenza di caratteri seguita da un ritorno a capo (\"\\n\"), un ritorno a capo (\"\\r\"), o un ritorno a capo immediatamente seguito da un ritorno a capo (\"\\r\\n\"). Ogni parola è prevista in minuscolo. |

**Returns:**
java.lang.String - Testo con parole sostituite.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Trova automaticamente le aree problematiche di un'immagine che possono influire significativamente sull'accuratezza dell'OCR. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | I tipi di difetti da riconoscere [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList di [DefectOutput](../../com.aspose.ocr/defectoutput/) con aree di testo o linee rilevate.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analizza l'immagine e identifica i diversi tipi di aree di contenuto al suo interno. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Aree di contenuto rilevate. ArrayList di [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analizza il testo sull'immagine per determinare le lingue in cui è scritto. Questo consente di selezionare la lingua di riconoscimento più adatta e aiuta nelle successive attività di elaborazione del testo, come il controllo ortografico o la traduzione. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Restituisce un elenco delle lingue più probabili, ordinate per probabilità. ArrayList di [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Rileva le aree di testo nelle immagini. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Determina quali rettangoli restituire - linea o paragrafi. |
| isDetectAreas | boolean | Abilita il rilevamento automatico delle aree di testo. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList di [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) con aree di testo o linee rilevate.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Rileva le regioni di tabelle nelle immagini. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList di [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) con aree di tabella rilevate.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Verifica se l'immagine contiene il frammento di testo fornito con una ricerca senza distinzione tra maiuscole e minuscole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso dell'immagine. |
| text | java.lang.String | Frammento di testo per la ricerca nell'immagine. |

**Returns:**
boolean - True se l'immagine contiene il frammento di testo. False - l'immagine non contiene il frammento di testo.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Verifica se l'immagine contiene il frammento di testo fornito con una ricerca senza distinzione tra maiuscole e minuscole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso dell'immagine. |
| text | java.lang.String | Frammento di testo per la ricerca nell'immagine. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |

**Returns:**
boolean - True se l'immagine contiene il frammento di testo. False - l'immagine non contiene il frammento di testo.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Verifica se l'immagine contiene il frammento di testo fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso dell'immagine. |
| text | java.lang.String | Frammento di testo per la ricerca nell'immagine. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |
| ignoreCase | boolean | True - indica una ricerca case-insensitive. |

**Returns:**
boolean - True se l'immagine contiene il frammento di testo. False - l'immagine non contiene il frammento di testo.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Verifica se il testo dell'immagine corrisponde all'espressione regolare fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso dell'immagine. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern oggetto con il pattern e le opzioni forniti. |

**Returns:**
boolean - True se il testo dell'immagine corrisponde all'espressione regolare fornita.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Verifica se il testo dell'immagine corrisponde all'espressione regolare fornita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath | java.lang.String | Percorso dell'immagine. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern oggetto con il pattern e le opzioni forniti. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |

**Returns:**
boolean - True se il testo dell'immagine corrisponde all'espressione regolare fornita.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath1 | java.lang.String | Percorso della prima immagine. |
| fullPath2 | java.lang.String | Percorso della seconda immagine. |

**Returns:**
float - 0 indica che i testi sono completamente diversi; 1 indica che i testi sono identici.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath1 | java.lang.String | Percorso della prima immagine. |
| fullPath2 | java.lang.String | Percorso della seconda immagine. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |

**Returns:**
float - 0 indica che i testi sono completamente diversi; 1 indica che i testi sono identici.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullPath1 | java.lang.String | Percorso della prima immagine. |
| fullPath2 | java.lang.String | Percorso della seconda immagine. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Impostazioni di riconoscimento. |
| ignoreCase | boolean | True - indica una ricerca case-insensitive. |

**Returns:**
float - 0 indica che i testi sono completamente diversi; 1 indica che i testi sono identici.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Riconosce immagini con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Riconosce immagini con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Riconosce targhe automobilistiche con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Rileva simboli nelle immagini. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList di [Character](../../com.aspose.ocr.models/character/) con i dati dei simboli rilevati per ogni immagine.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Rileva simboli nelle immagini. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Il contenitore con le sorgenti.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Determina il tipo di rete neurale utilizzata per il rilevamento delle aree. |
| language | [Language](../../com.aspose.ocr.models/language/) | Lingua utilizzata per l'OCR. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList di [Character](../../com.aspose.ocr.models/character/) con i dati dei simboli rilevati.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Riconosce il testo su immagini di buona qualità. Non utilizza la correzione automatica dell'inclinazione dell'immagine né il rilevamento delle aree di testo. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Istanza di [OcrInput](../../com.aspose.ocr/ocrinput/). |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList con il testo riconosciuto.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Riconosce formule matematiche dalle immagini di input fornite. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| detectAreas | boolean | Se impostato su true, rileva e isola automaticamente le regioni di formula prima di eseguire il riconoscimento. Se false, elabora l'intera immagine come una formula. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Riconosce testo scritto a mano su immagini. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Il contenitore con le sorgenti. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Riconosce carte d'identità con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Riconosce fatture con la possibilità di specificare: supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Riconosce passaporti con la possibilità di specificare. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Riconosce le ricevute con la possibilità di specificare Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Rileva tabelle e struttura, riconosce le celle di testo. Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, cartella, array, archivio zip, URL, base64.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). istanza. |
| language | [Language](../../com.aspose.ocr.models/language/) | Determina l'alfabeto utilizzato durante il riconoscimento. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - oggetti OCRTablePage con i testi riconosciuti nelle tabelle. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |
| embeddedFontPath | java.lang.String | Facoltativamente. Percorso completo al font dell'utente. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |
| embeddedFontPath | java.lang.String | Facoltativamente. Percorso completo al font dell'utente. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult con correzione ortografica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Valore enum [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |
| embeddedFontPath | java.lang.String | Facoltativamente. Percorso completo al font dell'utente. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fullFileName | java.lang.String | Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Formato documento (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Elenco di [RecognitionResult](../../com.aspose.ocr/recognitionresult/). oggetti. |
| embeddedFontPath | java.lang.String | Facoltativamente. Percorso completo al font dell'utente. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Riduci le dimensioni del file PDF abbassando la qualità delle immagini di sfondo. Per impostazione predefinita, la qualità originale dell'immagine viene conservata. |

### close() {#close}
```
public void close()
```