---
title: "RecognitionResult"
second_title: "Aspose.OCR för Java API-referens"
description: "Resultaten av bildigenkänning"
type: docs
weight: 26
url: /sv/java/com.aspose.ocr/recognitionresult/
---

**Inheritance:**
java.lang.Object
```
public class RecognitionResult
```

Resultaten av bildigenkänning. Innehåller element med igenkänningsinformation och metoder för export av resultat.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RecognitionResult()](#RecognitionResult) | Initierar en ny instans av |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [language](#language) | Språket för den igenkända texten i bilden. |
| [recognitionCharactersList](#recognitionCharactersList) | En uppsättning tecken som hittats av igenkänningsalgoritmen och ordnade i fallande sannolikhetsordning. |
| [recognitionLinesResult](#recognitionLinesResult) | Hämtar en lista med igenkänningsresultat med en lista över rader (rektanglar). |
| [recognitionRegionsResult](#recognitionRegionsResult) | Hämtar en lista med igenkänningsresultat med en lista över regioner (rektanglar). |
| [recognitionText](#recognitionText) | Igenkänningsresultat för hela sidan eller ett område. |
| [warnings](#warnings) | Hämtar eller anger en lista med varningsmeddelanden som beskriver icke‑kritiska fel som uppstod under generering. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [GetJson()](#GetJson) | Skapa JSON-sträng med igenkänningsresultat. |
| [GetKeywords()](#GetKeywords) | Hämta nyckelord från pass (testläge). |
| [GetXml()](#GetXml) | Skapa JSON-sträng med igenkänningsresultat. |
| [SetKeyword(String key, RecognitionResult.LinesResult result)](#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult) |  |
| [getSpellCheckCorrectedText()](#getSpellCheckCorrectedText) | Korrigerar text (ersätter felstavade ord). |
| [getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)](#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Korrigerar text (ersätter felstavade ord). |
| [getSpellCheckErrorList()](#getSpellCheckErrorList) | Hitta de felstavade orden med föreslagna stavningar för en given indatatext. |
| [getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)](#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Hitta de felstavade orden med föreslagna stavningar för en given indatatext. |
| [save(String fullFileName)](#save-java.lang.String) | Sparar dokumentet i vanlig text |
| [save(String fullFileName, Format format)](#save-java.lang.String-com.aspose.ocr.models.Format) | Sparar dokumentet i vanlig text eller annat dokumentformat. |
| [save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)](#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode) | Sparar dokumentet i vanlig text eller annat dokumentformat. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format) | Sparar den korrigerade texten med engelsk ordbok i dokumentet i vanlig text eller Microsoft Word Text Document-format. |
| [saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)](#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage) | Sparar den korrigerade texten i dokumentet i vanlig text eller annat format. |
| [toString()](#toString) |  |
| [useUserDictionary(String dictionaryPath)](#useUserDictionary-java.lang.String) | Tillåter att använda egen ordbok för stavningskontrollkorrektion. |
### RecognitionResult() {#RecognitionResult}
```
public RecognitionResult()
```


Initierar en ny instans av

### language {#language}
```
public Language language
```


Språket för den igenkända texten i bilden. Detta värde bestäms automatiskt om  Language.AUTO ,  Language.MULTILANGUAGE , eller  Language.UNIVERSAL  är valt.

### recognitionCharactersList {#recognitionCharactersList}
```
public ArrayList<char[]> recognitionCharactersList
```


En uppsättning tecken som hittats av igenkänningsalgoritmen och ordnade i fallande sannolikhetsordning.

### recognitionLinesResult {#recognitionLinesResult}
```
public ArrayList<RecognitionResult.LinesResult> recognitionLinesResult
```


Hämtar en lista med igenkänningsresultat med en lista över rader (rektanglar).

### recognitionRegionsResult {#recognitionRegionsResult}
```
public ArrayList<RecognitionResult.RegionResult> recognitionRegionsResult
```


Hämtar en lista med igenkänningsresultat med en lista över regioner (rektanglar).

### recognitionText {#recognitionText}
```
public String recognitionText
```


Igenkänningsresultat för hela sidan eller ett område.

### warnings {#warnings}
```
public ArrayList<String> warnings
```


Hämtar eller anger en lista med varningsmeddelanden som beskriver icke‑kritiska fel som uppstod under generering.

### GetJson() {#GetJson}
```
public String GetJson()
```


Skapa JSON-sträng med igenkänningsresultat.

**Returns:**
java.lang.String - Igenkänningsresultat som JSON-sträng.
### GetKeywords() {#GetKeywords}
```
public HashMap<String,RecognitionResult.LinesResult> GetKeywords()
```


Hämta nyckelord från pass (Testläge. Fungerar endast för USA- och MADAGASKAR-pass).

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.ocr.RecognitionResult.LinesResult> - Ordbok med nyckelord som nyckel och LinesResult som värde.
### GetXml() {#GetXml}
```
public String GetXml()
```


Skapa JSON-sträng med igenkänningsresultat.

**Returns:**
java.lang.String - Igenkänningsresultat som XML-sträng.
### SetKeyword(String key, RecognitionResult.LinesResult result) {#SetKeyword-java.lang.String-com.aspose.ocr.RecognitionResult.LinesResult}
```
public void SetKeyword(String key, RecognitionResult.LinesResult result)
```



### getSpellCheckCorrectedText() {#getSpellCheckCorrectedText}
```
public String getSpellCheckCorrectedText()
```


Korrigerar text (ersätter felstavade ord).

**Returns:**
java.lang.String - Korrigerad igenkänningsresultatsträng. Standard engelsk ordbok.
### getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language) {#getSpellCheckCorrectedText-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public String getSpellCheckCorrectedText(SpellCheck.SpellCheckLanguage language)
```


Korrigerar text (ersätter felstavade ord).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Ordbok att använda. |

**Returns:**
java.lang.String - Korrigerad igenkänningsresultatsträng.
### getSpellCheckErrorList() {#getSpellCheckErrorList}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList()
```


Hitta de felstavade orden med föreslagna stavningar för en given indatatext. Standard engelsk ordbok.

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList av SpellCheckError-objekt som representerar felstavade ord med listor över föreslagna korrekta stavningar för varje felstavat ord, samt med avståndet för redigering.
### getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language) {#getSpellCheckErrorList-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public List<SpellCheck.SpellCheckError> getSpellCheckErrorList(SpellCheck.SpellCheckLanguage language)
```


Hitta de felstavade orden med föreslagna stavningar för en given indatatext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Ordbok att använda. |

**Returns:**
java.util.List<com.aspose.ocr.SpellCheck.SpellCheckError> - ArrayList av SpellCheckError-objekt som representerar felstavade ord med listor över föreslagna korrekta stavningar för varje felstavat ord, samt med avståndet för redigering.




### save(String fullFileName) {#save-java.lang.String}
```
public void save(String fullFileName)
```


Sparar dokumentet i vanlig text

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultat |

### save(String fullFileName, Format format) {#save-java.lang.String-com.aspose.ocr.models.Format}
```
public void save(String fullFileName, Format format)
```


Sparar dokumentet i vanlig text eller annat dokumentformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat enum-typ av Format. |

### save(String fullFileName, Format format, PdfOptimizationMode optimizePdf) {#save-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.models.PdfOptimizationMode}
```
public void save(String fullFileName, Format format, PdfOptimizationMode optimizePdf)
```


Sparar dokumentet i vanlig text eller annat dokumentformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat enum-typ av Format. |
| optimizePdf | [PdfOptimizationMode](../../com.aspose.ocr.models/pdfoptimizationmode/) | Minska PDF-filens storlek genom att sänka kvaliteten på bakgrundsbilder. Som standard bevaras den ursprungliga bildkvaliteten. |

### saveSpellCheckCorrectedText(String fullFileName, Format format) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format)
```


Sparar den korrigerade texten med engelsk ordbok i dokumentet i vanlig text eller Microsoft Word Text Document-format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat enum-typ av Format. |

### saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language) {#saveSpellCheckCorrectedText-java.lang.String-com.aspose.ocr.models.Format-com.aspose.ocr.SpellCheck.SpellCheckLanguage}
```
public void saveSpellCheckCorrectedText(String fullFileName, Format format, SpellCheck.SpellCheckLanguage language)
```


Sparar den korrigerade texten i dokumentet i vanlig text eller annat format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fullFileName | java.lang.String | Filnamn med en sökväg för att spara igenkänningsresultat. |
| format | [Format](../../com.aspose.ocr.models/format/) | Dokumentformat enum-typ av Format. |
| language | [SpellCheckLanguage](../../com.aspose.ocr.spellcheck/spellchecklanguage/) | Ordbok för stavningskontroll. |
### useUserDictionary(String dictionaryPath) {#useUserDictionary-java.lang.String}
```
public void useUserDictionary(String dictionaryPath)
```


Tillåter att använda egen ordbok för stavningskontrollkorrektion.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dictionaryPath | java.lang.String | Fullständig sökväg till användarordboken (frekvensordbok). Filformat för ordboken: Vanlig textfil i UTF-8‑kodning. Ord och ordfrekvens separeras med kommatecken, ordet förväntas i den första kolumnen och frekvensen i den andra kolumnen. Varje ord‑frekvens‑par på en separat rad. En rad definieras som en sekvens av tecken följd av en radmatning ("\\n"), ett vagnretur ("\\r"), eller ett vagnretur omedelbart följt av en radmatning ("\\r\\n"). Alla ord förväntas vara i gemener. |
