---
title: "AsposeOCR"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Hauptklasse zum Erkennen von Text aus Bildern"
type: docs
weight: 10
url: /de/java/com.aspose.ocr/asposeocr/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.AutoCloseable
```
public class AsposeOCR implements AutoCloseable
```

Hauptklasse zum Erkennen von Text aus Bildern.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [AsposeOCR()](#AsposeOCR) | Öffentlicher Konstruktor. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DebugMode](#DebugMode) | Aktiviert den Debug‑Modus. |
| [DebugModeSaveDirectory](#DebugModeSaveDirectory) | Verzeichnis, in dem Debug‑Ergebnisse gespeichert werden. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [CalculateSkew(OcrInput input)](#CalculateSkew-com.aspose.ocr.OcrInput) | Berechnet die Schrägwinkel von Bildern. |
| [CompareImageTexts(String fullPath1, String fullPath2)](#CompareImageTexts-java.lang.String-java.lang.String) | Prüft, ob zwei Bilder denselben Text enthalten. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Prüft, ob zwei Bilder denselben Text enthalten. |
| [CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Prüft, ob zwei Bilder denselben Text enthalten. |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Korrigiert Text (ersetzt falsch geschriebene Wörter). |
| [CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)](#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String) | Korrigiert Text (ersetzt falsch geschriebene Wörter). |
| [DetectDefects(OcrInput input, DefectType defectType)](#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType) | Findet automatisch problematische Bereiche eines Bildes, die die OCR‑Genauigkeit erheblich beeinträchtigen können. |
| [DetectDocumentLayout(OcrInput input)](#DetectDocumentLayout-com.aspose.ocr.OcrInput) | Analysiert das Bild und identifiziert die verschiedenen Arten von Inhaltsbereichen darin. |
| [DetectLanguages(OcrInput input)](#DetectLanguages-com.aspose.ocr.OcrInput) | Analysiert den Text im Bild, um die darin verwendeten Sprachen zu bestimmen. |
| [DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)](#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean) | Erkennt Textbereiche in Bildern. |
| [DetectTables(OcrInput images)](#DetectTables-com.aspose.ocr.OcrInput) | Erkennt Tabellenbereiche in Bildern. |
| [ImageHasText(String fullPath, String text)](#ImageHasText-java.lang.String-java.lang.String) | Prüft, ob das Bild das bereitgestellte Textfragment mit einer Groß‑/Kleinschreibung‑unabhängigen Suche enthält. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Prüft, ob das Bild das bereitgestellte Textfragment mit einer Groß‑/Kleinschreibung‑unabhängigen Suche enthält. |
| [ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)](#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Prüft, ob das Bild das bereitgestellte Textfragment enthält. |
| [ImageHasText(String fullPath, Pattern regex)](#ImageHasText-java.lang.String-java.util.regex.Pattern) | Prüft, ob der Bildtext dem bereitgestellten regulären Ausdruck entspricht. |
| [ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)](#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings) | Prüft, ob der Bildtext dem bereitgestellten regulären Ausdruck entspricht. |
| [ImageTextDiff(String fullPath1, String fullPath2)](#ImageTextDiff-java.lang.String-java.lang.String) | Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die deren Ähnlichkeit darstellt (0 bis 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings) | Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die deren Ähnlichkeit darstellt (0 bis 1). |
| [ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)](#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean) | Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die deren Ähnlichkeit darstellt (0 bis 1). |
| [Recognize(OcrInput input)](#Recognize-com.aspose.ocr.OcrInput) | Erkennt Bild mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64. |
| [Recognize(OcrInput input, RecognitionSettings settings)](#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings) | Erkennt Bild mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64. |
| [RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)](#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings) | Erkennt Kfz‑Kennzeichen mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64. |
| [RecognizeCharacters(OcrInput input)](#RecognizeCharacters-com.aspose.ocr.OcrInput) | Erkennt Symbole in Bildern. |
| [RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)](#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language) | Erkennt Symbole in Bildern. |
| [RecognizeFast(OcrInput input)](#RecognizeFast-com.aspose.ocr.OcrInput) | Erkennt Text in qualitativ hochwertigem Bild. |
| [RecognizeFormula(OcrInput input, boolean detectAreas)](#RecognizeFormula-com.aspose.ocr.OcrInput-boolean) | Erkennt mathematische Formeln aus den bereitgestellten Eingabebildern. |
| [RecognizeHandwrittenText(OcrInput input)](#RecognizeHandwrittenText-com.aspose.ocr.OcrInput) | Erkennt handgeschriebenen Text in Bildern. |
| [RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)](#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings) | Erkennt Personalausweis mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64. |
| [RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)](#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings) | Erkennt Rechnung mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64. |
| [RecognizePassport(OcrInput input, PassportRecognitionSettings settings)](#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings) | Erkennt Reisepass mit der Möglichkeit zur Angabe. |
| [RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)](#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings) | Erkennt Quittungen mit der Möglichkeit zur Angabe Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64. |
| [RecognizeTables(OcrInput input, Language language)](#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language) | Erkennt Tabellen und Struktur, erkennt Textzellen. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten. |
| [SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten mit Rechtschreibkorrektur. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten. |
| [SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)](#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode) | Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten. |
| [close()](#close) |  |

### AsposeOCR() {#AsposeOCR}
```
public AsposeOCR()
```


Öffentlicher Konstruktor.

### DebugMode {#DebugMode}
```
public static boolean DebugMode
```


Aktiviert den Debug-Modus. Wenn aktiviert, speichert das System Zwischenergebnisse der Bildverarbeitung, wie vorverarbeitete Bilder und Bilder mit gezeichneten Textzeilen-Rechtecken.

### DebugModeSaveDirectory {#DebugModeSaveDirectory}
```
public static String DebugModeSaveDirectory
```


Verzeichnis, in dem Debug-Ergebnisse gespeichert werden. Wenn nicht festgelegt, wird standardmäßig das aktuelle Arbeitsverzeichnis verwendet.

### CalculateSkew(OcrInput input) {#CalculateSkew-com.aspose.ocr.OcrInput}
```
public ArrayList<SkewOutput> CalculateSkew(OcrInput input)
```


Berechnet die Schrägwinkel von Bildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.SkewOutput> - ArrayList von Schrägwinkeln in Grad [SkewOutput](../../com.aspose.ocr.models/skewoutput/)
### CompareImageTexts(String fullPath1, String fullPath2) {#CompareImageTexts-java.lang.String-java.lang.String}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2)
```


Prüft, ob zwei Bilder denselben Text enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pfad zum ersten Bild. |
| fullPath2 | java.lang.String | Pfad zum zweiten Bild. |

**Returns:**
boolean - Wahr, wenn die Bilder denselben Text haben (90 % Ähnlichkeit).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Prüft, ob zwei Bilder denselben Text enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pfad zum ersten Bild. |
| fullPath2 | java.lang.String | Pfad zum zweiten Bild. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |

**Returns:**
boolean - Wahr, wenn die Bilder denselben Text haben (90 % Ähnlichkeit).
### CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#CompareImageTexts-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean CompareImageTexts(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Prüft, ob zwei Bilder denselben Text enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pfad zum ersten Bild. |
| fullPath2 | java.lang.String | Pfad zum zweiten Bild. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |
| ignoreCase | boolean | Wahr - bedeutet eine case-insensitive Suche. |

**Returns:**
boolean - Wahr, wenn die Bilder denselben Text haben (90 % Ähnlichkeit).
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language)
```


Korrigiert Text (ersetzt falsch geschriebene Wörter).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text für die Korrektur. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Zu verwendendes Wörterbuch [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |

**Returns:**
java.lang.String - Text mit ersetzten Wörtern.
### CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath) {#CorrectSpelling-java.lang.String-com.aspose.ocr.SpellCheck.SpellCheckLanguage-java.lang.String}
```
public String CorrectSpelling(String text, SpellCheck.SpellCheckLanguage language, String dictionaryPath)
```


Korrigiert Text (ersetzt falsch geschriebene Wörter).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Text für die Korrektur. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Zu verwendendes Wörterbuch [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/). |
| dictionaryPath | java.lang.String | Vollständiger Pfad zum Benutzerdictionary (Häufigkeitsdictionary). Dateiformat des Dictionaries: Klartextdatei in UTF-8-Kodierung. Wort und Wortfrequenz sind durch ein Komma getrennt, das Wort steht in der ersten Spalte und die Frequenz in der zweiten Spalte. Jedes Wort‑Frequenz‑Paar befindet sich in einer eigenen Zeile. Eine Zeile ist definiert als eine Zeichenfolge, gefolgt von einem Zeilenumbruch ("\\n"), einem Wagenrücklauf ("\\r") oder einem Wagenrücklauf, dem sofort ein Zeilenumbruch folgt ("\\r\\n"). Jedes Wort wird in Kleinbuchstaben erwartet. |

**Returns:**
java.lang.String - Text mit ersetzten Wörtern.
### DetectDefects(OcrInput input, DefectType defectType) {#DetectDefects-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DefectType}
```
public ArrayList<DefectOutput> DetectDefects(OcrInput input, DefectType defectType)
```


Automatisches Auffinden problematischer Bereiche eines Bildes, die die OCR‑Genauigkeit erheblich beeinträchtigen können. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| defectType | [DefectType](../../com.aspose.ocr.models/defecttype/) | Die Arten von Defekten, die erkannt werden sollen [DefectType](../../com.aspose.ocr.models/defecttype/). |

**Returns:**
java.util.ArrayList<com.aspose.ocr.DefectOutput> - ArrayList von [DefectOutput](../../com.aspose.ocr/defectoutput/) mit erkannten Textbereichen oder Zeilen.
### DetectDocumentLayout(OcrInput input) {#DetectDocumentLayout-com.aspose.ocr.OcrInput}
```
public ArrayList<LayoutOutput> DetectDocumentLayout(OcrInput input)
```


Analysiert das Bild und identifiziert die verschiedenen Arten von Inhaltsbereichen darin. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LayoutOutput> - Erfasste Inhaltsbereiche. ArrayList von [LayoutOutput](../../com.aspose.ocr.models/layoutoutput/)
### DetectLanguages(OcrInput input) {#DetectLanguages-com.aspose.ocr.OcrInput}
```
public ArrayList<LanguageDetectionOutput> DetectLanguages(OcrInput input)
```


Analysiert den Text im Bild, um die darin verwendeten Sprachen zu bestimmen. Dadurch kann die am besten geeignete Erkennungssprache ausgewählt werden und es unterstützt weitere Textverarbeitungsaufgaben wie Rechtschreibprüfung oder Übersetzung. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.LanguageDetectionOutput> - Gibt eine Liste der wahrscheinlichsten Sprachen zurück, nach Wahrscheinlichkeit sortiert. ArrayList von [LanguageDetectionOutput](../../com.aspose.ocr.models/languagedetectionoutput/)
### DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas) {#DetectRectangles-com.aspose.ocr.OcrInput-com.aspose.ocr.models.AreasType-boolean}
```
public ArrayList<RectangleOutput> DetectRectangles(OcrInput input, AreasType areasType, boolean isDetectAreas)
```


Erkennt Textbereiche in Bildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| areasType | [AreasType](../../com.aspose.ocr.models/areastype/) | Bestimmt, welche Rechtecke zurückgegeben werden sollen – Zeile oder Absatz. |
| isDetectAreas | boolean | Aktiviert die automatische Erkennung von Textbereichen. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList von [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) mit erkannten Textbereichen oder Zeilen.
### DetectTables(OcrInput images) {#DetectTables-com.aspose.ocr.OcrInput}
```
public ArrayList<RectangleOutput> DetectTables(OcrInput images)
```


Erkennt Tabellenbereiche in Bildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| images | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.RectangleOutput> - ArrayList von [RectangleOutput](../../com.aspose.ocr/rectangleoutput/) mit erkannten Tabellenbereichen.
### ImageHasText(String fullPath, String text) {#ImageHasText-java.lang.String-java.lang.String}
```
public boolean ImageHasText(String fullPath, String text)
```


Prüft, ob das Bild das bereitgestellte Textfragment mit einer Groß‑/Kleinschreibung‑unabhängigen Suche enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild. |
| text | java.lang.String | Textfragment für die Suche im Bild. |

**Returns:**
boolean – Wahr, wenn das Bild ein Textfragment enthält. Falsch – das Bild enthält kein Textfragment.
### ImageHasText(String fullPath, String text, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings)
```


Prüft, ob das Bild das bereitgestellte Textfragment mit einer Groß‑/Kleinschreibung‑unabhängigen Suche enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild. |
| text | java.lang.String | Textfragment für die Suche im Bild. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |

**Returns:**
boolean – Wahr, wenn das Bild ein Textfragment enthält. Falsch – das Bild enthält kein Textfragment.
### ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase) {#ImageHasText-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public boolean ImageHasText(String fullPath, String text, RecognitionSettings settings, boolean ignoreCase)
```


Prüft, ob das Bild das bereitgestellte Textfragment enthält.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild. |
| text | java.lang.String | Textfragment für die Suche im Bild. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |
| ignoreCase | boolean | Wahr - bedeutet eine case-insensitive Suche. |

**Returns:**
boolean – Wahr, wenn das Bild ein Textfragment enthält. Falsch – das Bild enthält kein Textfragment.
### ImageHasText(String fullPath, Pattern regex) {#ImageHasText-java.lang.String-java.util.regex.Pattern}
```
public boolean ImageHasText(String fullPath, Pattern regex)
```


Prüft, ob der Bildtext dem bereitgestellten regulären Ausdruck entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern-Objekt mit dem angegebenen Muster und den Optionen. |

**Returns:**
boolean – Wahr, wenn der Bildtext dem angegebenen regulären Ausdruck entspricht.
### ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings) {#ImageHasText-java.lang.String-java.util.regex.Pattern-com.aspose.ocr.RecognitionSettings}
```
public boolean ImageHasText(String fullPath, Pattern regex, RecognitionSettings settings)
```


Prüft, ob der Bildtext dem bereitgestellten regulären Ausdruck entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath | java.lang.String | Pfad zum Bild. |
| regex | java.util.regex.Pattern | java.util.regex.Pattern-Objekt mit dem angegebenen Muster und den Optionen. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |

**Returns:**
boolean – Wahr, wenn der Bildtext dem angegebenen regulären Ausdruck entspricht.
### ImageTextDiff(String fullPath1, String fullPath2) {#ImageTextDiff-java.lang.String-java.lang.String}
```
public float ImageTextDiff(String fullPath1, String fullPath2)
```


Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die deren Ähnlichkeit darstellt (0 bis 1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pfad zum ersten Bild. |
| fullPath2 | java.lang.String | Pfad zum zweiten Bild. |

**Returns:**
float – 0 bedeutet, dass die Texte völlig unterschiedlich sind; 1 bedeutet, dass die Texte identisch sind.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings)
```


Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die deren Ähnlichkeit darstellt (0 bis 1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pfad zum ersten Bild. |
| fullPath2 | java.lang.String | Pfad zum zweiten Bild. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |

**Returns:**
float – 0 bedeutet, dass die Texte völlig unterschiedlich sind; 1 bedeutet, dass die Texte identisch sind.
### ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase) {#ImageTextDiff-java.lang.String-java.lang.String-com.aspose.ocr.RecognitionSettings-boolean}
```
public float ImageTextDiff(String fullPath1, String fullPath2, RecognitionSettings settings, boolean ignoreCase)
```


Vergleicht die Texte der beiden Bilder und gibt eine Zahl zurück, die deren Ähnlichkeit darstellt (0 bis 1).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullPath1 | java.lang.String | Pfad zum ersten Bild. |
| fullPath2 | java.lang.String | Pfad zum zweiten Bild. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | Erkennungseinstellungen. |
| ignoreCase | boolean | Wahr - bedeutet eine case-insensitive Suche. |

**Returns:**
float – 0 bedeutet, dass die Texte völlig unterschiedlich sind; 1 bedeutet, dass die Texte identisch sind.
### Recognize(OcrInput input) {#Recognize-com.aspose.ocr.OcrInput}
```
public OcrOutput Recognize(OcrInput input)
```


Erkennt Bild mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### Recognize(OcrInput input, RecognitionSettings settings) {#Recognize-com.aspose.ocr.OcrInput-com.aspose.ocr.RecognitionSettings}
```
public OcrOutput Recognize(OcrInput input, RecognitionSettings settings)
```


Erkennt Bild mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| settings | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/) | [RecognitionSettings](../../com.aspose.ocr/recognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings) {#RecognizeCarPlate-com.aspose.ocr.OcrInput-com.aspose.ocr.CarPlateRecognitionSettings}
```
public OcrOutput RecognizeCarPlate(OcrInput input, CarPlateRecognitionSettings settings)
```


Erkennt Kfz‑Kennzeichen mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| settings | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/) | [CarPlateRecognitionSettings](../../com.aspose.ocr/carplaterecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeCharacters(OcrInput input) {#RecognizeCharacters-com.aspose.ocr.OcrInput}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input)
```


Erkennt Symbole in Bildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList von [Character](../../com.aspose.ocr.models/character/) mit erkannten Symboldaten für jedes Bild.
### RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language) {#RecognizeCharacters-com.aspose.ocr.OcrInput-com.aspose.ocr.models.DetectAreasMode-com.aspose.ocr.models.Language}
```
public ArrayList<CharacterRecognitionResult> RecognizeCharacters(OcrInput input, DetectAreasMode detectAreasMode, Language language)
```


Erkennt Symbole in Bildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | Der Container mit Quellen.[OcrInput](../../com.aspose.ocr/ocrinput/) |
| detectAreasMode | [DetectAreasMode](../../com.aspose.ocr.models/detectareasmode/) | Bestimmt den Typ des für die Flächenerkennung verwendeten neuronalen Netzwerks. |
| language | [Language](../../com.aspose.ocr.models/language/) | Für die OCR verwendete Sprache. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.CharacterRecognitionResult> - ArrayList von [Character](../../com.aspose.ocr.models/character/) mit erkannten Symboldaten.
### RecognizeFast(OcrInput input) {#RecognizeFast-com.aspose.ocr.OcrInput}
```
public ArrayList<String> RecognizeFast(OcrInput input)
```


Erkennt Text auf qualitativ hochwertigem Bild. Verwendet keine automatische Bildschräglagenkorrektur und Flächenerkennung für Text. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/) Instanz. |

**Returns:**
java.util.ArrayList<java.lang.String> - ArrayList mit erkanntem Text.
### RecognizeFormula(OcrInput input, boolean detectAreas) {#RecognizeFormula-com.aspose.ocr.OcrInput-boolean}
```
public OcrOutput RecognizeFormula(OcrInput input, boolean detectAreas)
```


Erkennt mathematische Formeln aus den bereitgestellten Eingabebildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| detectAreas | boolean | Wenn auf true gesetzt, erkennt und isoliert automatisch Formelbereiche, bevor die Erkennung durchgeführt wird. Wenn false, wird das gesamte Bild als Formel verarbeitet. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - OcrOutput list with images recognition results [OcrOutput](../../com.aspose.ocr/ocroutput/)
### RecognizeHandwrittenText(OcrInput input) {#RecognizeHandwrittenText-com.aspose.ocr.OcrInput}
```
public OcrOutput RecognizeHandwrittenText(OcrInput input)
```


Erkennt handgeschriebenen Text auf Bildern. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Der Container mit Quellen.. |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings) {#RecognizeIDCard-com.aspose.ocr.OcrInput-com.aspose.ocr.IDCardRecognitionSettings}
```
public OcrOutput RecognizeIDCard(OcrInput input, IDCardRecognitionSettings settings)
```


Erkennt Personalausweis mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| settings | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/) | [IDCardRecognitionSettings](../../com.aspose.ocr/idcardrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings) {#RecognizeInvoice-com.aspose.ocr.OcrInput-com.aspose.ocr.InvoiceRecognitionSettings}
```
public OcrOutput RecognizeInvoice(OcrInput input, InvoiceRecognitionSettings settings)
```


Erkennt Rechnung mit der Möglichkeit, die unterstützten Formate anzugeben: GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP‑Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| settings | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/) | [InvoiceRecognitionSettings](../../com.aspose.ocr/invoicerecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizePassport(OcrInput input, PassportRecognitionSettings settings) {#RecognizePassport-com.aspose.ocr.OcrInput-com.aspose.ocr.PassportRecognitionSettings}
```
public OcrOutput RecognizePassport(OcrInput input, PassportRecognitionSettings settings)
```


Erkennt Reisepässe mit der Möglichkeit zur Angabe. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| settings | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/) | [PassportRecognitionSettings](../../com.aspose.ocr/passportrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings) {#RecognizeReceipt-com.aspose.ocr.OcrInput-com.aspose.ocr.ReceiptRecognitionSettings}
```
public OcrOutput RecognizeReceipt(OcrInput input, ReceiptRecognitionSettings settings)
```


Erkennt Quittungen mit der Möglichkeit zur Angabe Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| settings | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/) | [ReceiptRecognitionSettings](../../com.aspose.ocr/receiptrecognitionsettings/). |

**Returns:**
[OcrOutput](../../com.aspose.ocr/ocroutput/) - RecognitionResult list with images recognition results [RecognitionResult](../../com.aspose.ocr/recognitionresult/)
### RecognizeTables(OcrInput input, Language language) {#RecognizeTables-com.aspose.ocr.OcrInput-com.aspose.ocr.models.Language}
```
public ArrayList<OCRTablePage> RecognizeTables(OcrInput input, Language language)
```


Erkennt Tabellen und Struktur, erkennt Textzellen. Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, InputStream, BufferedImage, Ordner, Array, ZIP-Archiv, URL, Base64.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input | [OcrInput](../../com.aspose.ocr/ocrinput/) | [OcrInput](../../com.aspose.ocr/ocrinput/). Instanz. |
| language | [Language](../../com.aspose.ocr.models/language/) | Bestimmt das bei der Erkennung verwendete Alphabet. |

**Returns:**
java.util.ArrayList<com.aspose.ocr.models.OCRTablePage> - OCRTablePage-Listenobjekte mit erkanntem Text in Tabellen. [OCRTablePage](../../com.aspose.ocr.models/ocrtablepage/)
### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |

### SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.io.OutputStream-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(OutputStream stream, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.OutputStream | OutputStream zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, PdfNoImg, Xlsx, Xml, Json, Rtf). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, SpellCheck.SpellCheckLanguage language)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten mit Rechtschreibkorrektur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) Enum-Wert. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |

### SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf) {#SaveMultipageDocument-java.lang.String-com.aspose.ocr.models.Format-java.util.ArrayList-com.aspose.ocr.RecognitionResult--java.lang.String-com.aspose.ocr.models.PdfOptimizationMode}
```
public static void SaveMultipageDocument(String fullFileName, Format saveFormat, ArrayList<RecognitionResult> results, String embeddedFontPath, PdfOptimizationMode optimizePdf)
```


Ermöglicht das Abrufen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format. |
| saveFormat | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat (Docx, Txt, Pdf, Xlsx, Xml, Json). |
| results | java.util.ArrayList<com.aspose.ocr.RecognitionResult> | Liste von [RecognitionResult](../../com.aspose.ocr/recognitionresult/). Objekten. |
| embeddedFontPath | java.lang.String | Optional. Vollständiger Pfad zur Benutzerschriftart. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### close() {#close}
```
public void close()
```