---
title: "RecognitionResult"
second_title: "Aspose.OCR voor Python via Java API-referentie"
description: 
type: docs
weight: 171
url: /nl/python-java/aspose/recognitionresult/
---

Module recognitionresult
========================

Klassen
-------

`LinesResult(javaClass)`
:

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
De resultaten van de beeldherkenning. Bevat elementen met herkenning
informatie en methoden voor het exporteren van resultaten.

### Statische methoden

`save_multipage_document(self, fullPath: str)`
:
Privé

### Instantievariabelen

`recognition_areas_text`
:   Lijst herkenningsresultaten van een lijst met gebieden (Rechthoeken).

`recognition_lines_result`
:   Haalt een lijst met herkenningsresultaten op met een lijst met rijen (Rechthoeken).

### Methoden

`getJavaClass(self)`
:

`get_json(self)`
:
Maak JSON‑string met herkenningsresultaten.
@return: Herkenningsresultaten als JSON‑string.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corrigeert tekst (vervangt verkeerd gespelde woorden).
@param language: Te gebruiken woordenboek.
@return: Gecorrigeerde herkenningsresultaten als tekenreeks.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Zoek de verkeerd gespelde woorden met voorgestelde spellingen voor een gegeven invoertekst.
@param language: Te gebruiken woordenboek.
@return: Lijst van SpellCheckError‑objecten die verkeerd gespelde woorden vertegenwoordigen met lijsten van voorgestelde correcte spellingen voor elk verkeerd gespeld woord,
en met de bewerkingsafstand.

`get_xml(self)`
:
Maak JSON‑string met herkenningsresultaten.
@return: Herkenningsresultaten als XML‑tekenreeks.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Slaat het document op in platte tekst of een ander documentformaat.
@param fullFileName: Bestandsnaam met pad voor het opslaan van het herkenningsresultaat.
@param format: Documentformaat‑enumtype van Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Corrigeert tekst (vervangt verkeerd gespelde woorden).
Slaat de gecorrigeerde tekst op in het document in platte tekst of een ander formaat.
@param fullFileName: Bestandsnaam met pad voor het opslaan van het herkenningsresultaat
@param format: Documentformaat‑enumtype van Format.
@param language: Woordenboek voor spellingscontrole.

`use_user_dictionary(self, dictionaryPath: str)`
:
Staat toe een eigen woordenboek te gebruiken voor spellingscontrole‑correctie.
@param dictionaryPath: Volledig pad naar het gebruikerswoordenboek (frequentiewoordenboek).
Bestandsformaat van woordenboek:
Platte‑tekstbestand in UTF-8‑codering.
Woord en woordfrequentie worden gescheiden door een komma; het woord wordt verwacht in de eerste kolom en de frequentie in de tweede kolom.
Elk woord‑frequentie‑paar in een aparte regel. Een regel wordt gedefinieerd als een reeks tekens gevolgd door een regeleinde (\"
\"), een carriage‑return (\"
"),
of een carriage return die onmiddellijk gevolgd wordt door een line feed("

").
Elk woord moet in kleine letters zijn.
Voorbeeld:
\code
word,5984819
hello,5761742
down,5582768
\endcode

`RectangleOutput(javaClass)`
:
Gegevens over gedetecteerde tekstgebieden of -regels.
\code
source - Het volledige pad naar het bestand of de URL, indien aanwezig. Leeg voor streams, byte‑arrays, base64.
page - Paginanummer.
image_index - Volgnummer van de afbeelding op de pagina.
rectangles - Lijst van gedetecteerde tekstgebieden of lijnen.
\endcode

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Gegevens over de scheefhellingshoek in graden en de bestandsnaam.
\code
source - Het volledige pad naar het bestand of de URL, indien aanwezig. Leeg voor streams, byte‑arrays, base64.
page - Paginanummer.
image_index - Volgnummer van de afbeelding op de pagina.
angle - Scheefhellingshoek in graden.
\endcode

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:


### Zie ook

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)