---
title: "RecognitionResult"
second_title: "Aspose.OCR für Java API-Referenz"
description: "Die Ergebnisse der Bilderkennung"
type: docs
weight: 26
url: /de/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Die Ergebnisse der Bilderkennung. Enthält Elemente mit Erkennungsinformationen und Methoden zum Exportieren der Ergebnisse.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Initialisiert eine neue Instanz von |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [language](#language) | Die Sprache des erkannten Textes im Bild. |
| [recognitionCharactersList](#recognitionCharactersList) | Eine Menge von Zeichen, die vom Erkennungsalgorithmus gefunden wurden und nach absteigender Wahrscheinlichkeit sortiert sind. |
| [recognitionLinesResult](#recognitionLinesResult) | Liefert eine Liste von Erkennungsergebnissen mit einer Liste von Zeilen (Rechtecke). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Liefert eine Liste von Erkennungsergebnissen mit einer Liste von Bereichen (Rechtecke). |
| [recognitionText](#recognitionText) | Erkennungsergebnis aller Seiten oder eines Bereichs. |
| [warnings](#warnings) | Liefert oder setzt die Liste der Warnmeldungen, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [GetJson()](#GetJson) | Erstelle JSON-String mit Erkennungsergebnissen. |
| [GetKeywords()](#GetKeywords) | Schlüsselwörter aus dem Pass extrahieren (Testmodus. |
| [GetXml()](#GetXml) | Erstelle JSON-String mit Erkennungsergebnissen. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Korrigiert Text (ersetzt falsch geschriebene Wörter). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Korrigiert Text (ersetzt falsch geschriebene Wörter). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Finden Sie die falsch geschriebenen Wörter mit vorgeschlagenen Rechtschreibungen für einen gegebenen Eingabetext. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Finden Sie die falsch geschriebenen Wörter mit vorgeschlagenen Rechtschreibungen für einen gegebenen Eingabetext. |
| [save(String fullFileName)](#save-java.lang.String) | Speichert das Dokument im Nur-Text-Format |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Speichert das Dokument im Nur-Text-Format oder in einem anderen Dokumentformat. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Speichert das Dokument im Nur-Text-Format oder in einem anderen Dokumentformat. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Speichert den mit dem englischen Wörterbuch korrigierten Text im Dokument im Nur-Text-Format oder im Microsoft Word Textdokument-Format. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Speichert den korrigierten Text im Dokument im Nur-Text-Format oder in einem anderen Format. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Ermöglicht die Verwendung eines eigenen Wörterbuchs für die Rechtschreibkorrektur. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Initialisiert eine neue Instanz von

### language {#language}
```
public Language language
```


Die Sprache des im Bild erkannten Textes. Dieser Wert wird automatisch bestimmt, wenn  Language.AUTO ,  Language.MULTILANGUAGE  oder  Language.UNIVERSAL  ausgewählt ist.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


Eine Menge von Zeichen, die vom Erkennungsalgorithmus gefunden wurden und nach absteigender Wahrscheinlichkeit sortiert sind.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Liefert eine Liste von Erkennungsergebnissen mit einer Liste von Zeilen (Rechtecke).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Liefert eine Liste von Erkennungsergebnissen mit einer Liste von Bereichen (Rechtecke).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Erkennungsergebnis aller Seiten oder eines Bereichs.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Liefert oder setzt die Liste der Warnmeldungen, die nicht kritische Fehler beschreiben, die während der Generierung aufgetreten sind.

### GetJson() {#GetJson}
```
public String GetJson()
```


Erstelle JSON-String mit Erkennungsergebnissen.

**Returns:**
java.lang.String – Erkennungsergebnisse als JSON‑String.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Abrufen von Schlüsselwörtern aus dem Pass (Testmodus. Funktioniert nur für USA‑ und MADAGASKAR‑Pässe).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> – Wörterbuch mit dem Schlüsselwort als Schlüssel und LinesResult als Wert.
### GetXml() {#GetXml}
```
public String GetXml()
```


Erstelle JSON-String mit Erkennungsergebnissen.

**Returns:**
java.lang.String – Erkennungsergebnisse als XML‑String.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Korrigiert Text (ersetzt falsch geschriebene Wörter).

**Returns:**
java.lang.String – Korrigierter Erkennungsresultat‑String. Standard‑Englisches Wörterbuch.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Korrigiert Text (ersetzt falsch geschriebene Wörter).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Zu verwendendes Wörterbuch. |

**Returns:**
java.lang.String – Korrigierter Erkennungsresultat‑String.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Finden Sie die falsch geschriebenen Wörter mit vorgeschlagenen Rechtschreibungen für einen gegebenen Eingabetext. Standard‑Englisches Wörterbuch.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> – ArrayList von SpellCheckError‑Objekten, die falsch geschriebene Wörter mit Listen vorgeschlagener korrekter Schreibweisen für jedes falsche Wort sowie mit der Editierdistanz darstellen.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Finden Sie die falsch geschriebenen Wörter mit vorgeschlagenen Rechtschreibungen für einen gegebenen Eingabetext.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Zu verwendendes Wörterbuch. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> – ArrayList von SpellCheckError‑Objekten, die falsch geschriebene Wörter mit Listen vorgeschlagener korrekter Schreibweisen für jedes falsche Wort sowie mit der Editierdistanz darstellen.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Speichert das Dokument im Nur-Text-Format

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Speichert das Dokument im Nur-Text-Format oder in einem anderen Dokumentformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat‑Enum‑Typ von Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Speichert das Dokument im Nur-Text-Format oder in einem anderen Dokumentformat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat‑Enum‑Typ von Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Reduzieren Sie die PDF-Dateigröße, indem Sie die Qualität von Hintergrundbildern verringern. Standardmäßig wird die ursprüngliche Bildqualität beibehalten. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Speichert den mit dem englischen Wörterbuch korrigierten Text im Dokument im Nur-Text-Format oder im Microsoft Word Textdokument-Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat‑Enum‑Typ von Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Speichert den korrigierten Text im Dokument im Nur-Text-Format oder in einem anderen Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fullFileName | java.lang.String | Dateiname mit Pfad zum Speichern des Erkennungsergebnisses. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentenformat‑Enum‑Typ von Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Wörterbuch für die Rechtschreibprüfung. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Ermöglicht die Verwendung eines eigenen Wörterbuchs für die Rechtschreibkorrektur.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Vollständiger Pfad zum Benutzerdictionary (Häufigkeitsdictionary). Dateiformat des Dictionaries: Klartextdatei in UTF-8-Kodierung. Wort und Wortfrequenz sind durch ein Komma getrennt, das Wort steht in der ersten Spalte und die Frequenz in der zweiten Spalte. Jedes Wort‑Frequenz‑Paar befindet sich in einer eigenen Zeile. Eine Zeile ist definiert als eine Zeichenfolge, gefolgt von einem Zeilenumbruch ("\\n"), einem Wagenrücklauf ("\\r") oder einem Wagenrücklauf, dem sofort ein Zeilenumbruch folgt ("\\r\\n"). Jedes Wort wird in Kleinbuchstaben erwartet. |
