---
title: "RecognitionResult"
second_title: "Aspose.OCR för Python via Java API-referens"
description: 
type: docs
weight: 171
url: /sv/python-java/aspose/recognitionresult/
---

Modul recognitionresult
========================

Klasser
-------

`LinesResult(javaClass)`
:

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Metoder

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Resultaten av bildigenkänning. Innehåller element med igenkänning
information och metoder för export av resultat.

### Statiska metoder

`save_multipage_document(self, fullPath: str)`
:
Privat

### Instansvariabler

`recognition_areas_text`
:   Lista med igenkänningsresultat för en lista av områden (Rektanglar).

`recognition_lines_result`
:   Hämtar en lista med igenkänningsresultat med en lista av rader (Rektanglar).

### Metoder

`getJavaClass(self)`
:

`get_json(self)`
:
Skapa JSON-sträng med igenkänningsresultat.
@return: Igenkänningsresultat som JSON-sträng.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Korrigerar text (ersätter felstavade ord).
@param language: Ordbok att använda.
@return: Korrigerad igenkänningsresultatsträng.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Hitta felstavade ord med föreslagna stavningar för en given indatatext.
@param language: Ordbok att använda.
@return: Lista med SpellCheckError-objekt som representerar felstavade ord med listor av föreslagna korrekta stavningar för varje felstavat ord,
och med redigeringsavståndet.

`get_xml(self)`
:
Skapa JSON-sträng med igenkänningsresultat.
@return: Igenkänningsresultat som XML-sträng.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Sparar dokumentet i vanlig text eller annat dokumentformat.
@param fullFileName: Filnamn med sökväg för att spara igenkänningsresultatet.
@param format: Dokumentformatets enum-typ av Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Korrigerar text (ersätter felstavade ord).
Sparar den korrigerade texten i dokumentet i vanlig text eller annat format.
@param fullFileName: Filnamn med sökväg för att spara igenkänningsresultatet
@param format: Dokumentformatets enum-typ av Format.
@param language: Ordbok för stavningskontroll.

`use_user_dictionary(self, dictionaryPath: str)`
:
Tillåter att använda egen ordbok för stavningskorrigering.
@param dictionaryPath: Fullständig sökväg till användarordboken (frekvensordbok).
Ordboksfilformat:
Vanlig textfil i UTF-8-kodning.
Ord och ordfrekvens separeras med kommatecken, ordet förväntas i den första kolumnen och frekvensen i den andra kolumnen.
Varje ord-frekvenspar i en separat rad. En rad definieras som en sekvens av tecken följd av en radmatning ("
"), ett vagnretur ("
"),
eller ett vagnretur omedelbart följt av ett radmatning("

").
Varje ord förväntas vara i gemener.
Exempel:
\code
ord,5984819
hej,5761742
ned,5582768
\endcode

`RectangleOutput(javaClass)`
:
Data om upptäckta textområden eller rader.
\code
source - Den fullständiga sökvägen till filen eller URL:en, om någon. Tom för strömmar, byte-arrayer, base64.
page - Sidnummer.
image_index - Sekvensnummer för bilden på sidan.
rectangles - Lista över upptäckta textområden eller rader.
\endcode

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Metoder

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Data om snedvinkel i grader och filens namn.
\code
source - Den fullständiga sökvägen till filen eller URL:en, om någon. Tom för strömmar, byte-arrayer, base64.
page - Sidnummer.
image_index - Sekvensnummer för bilden på sidan.
angle - Snedvinkel i grader.
\endcode

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Metoder

`initParams(self)`
:


### Se även

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)