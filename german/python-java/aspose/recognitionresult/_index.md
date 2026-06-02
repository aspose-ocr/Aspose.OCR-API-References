---
title: "RecognitionResult"
second_title: "Aspose.OCR für Python via Java API-Referenz"
description: 
type: docs
weight: 171
url: /de/python-java/aspose/recognitionresult/
---

Modul recognitionresult
========================

Klassen
-------

`LinesResult(javaClass)`
:

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
Die Ergebnisse der Bilderkennung. Enthält Elemente mit Erkennung
Informationen und Methoden zum Exportieren der Ergebnisse.

### Statische Methoden

`save_multipage_document(self, fullPath: str)`
:
Privat

### Instanzvariablen

`recognition_areas_text`
:   Liste von Erkennungsergebnissen einer Liste von Bereichen (Rechtecke).

`recognition_lines_result`
:   Gibt eine Liste von Erkennungsergebnissen mit einer Liste von Zeilen (Rechtecke) zurück.

### Methoden

`getJavaClass(self)`
:

`get_json(self)`
:
Formatiere JSON-String mit Erkennungsergebnissen.
@return: Erkennungsergebnisse als JSON-String.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Korrigiert Text (ersetzt falsch geschriebene Wörter).
@param language: Zu verwendendes Wörterbuch.
@return: Korrigierter Erkennungsergebnis-String.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Finde die falsch geschriebenen Wörter mit vorgeschlagenen Schreibweisen für einen gegebenen Eingabetext.
@param language: Zu verwendendes Wörterbuch.
@return: Liste von SpellCheckError-Objekten, die falsch geschriebene Wörter darstellen, mit Listen vorgeschlagener korrekter Schreibweisen für jedes falsche Wort,
und mit der Editierdistanz.

`get_xml(self)`
:
Formatiere JSON-String mit Erkennungsergebnissen.
@return: Erkennungsergebnisse als XML-String.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Speichert das Dokument im Nur-Text-Format oder in einem anderen Dokumentformat.
@param fullFileName: Dateiname mit Pfad zum Speichern des Erkennungsergebnisses.
@param format: Dokumentformat-Enum-Typ von Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Korrigiert Text (ersetzt falsch geschriebene Wörter).
Speichert den korrigierten Text im Dokument im Nur-Text-Format oder in einem anderen Format.
@param fullFileName: Dateiname mit Pfad zum Speichern des Erkennungsergebnisses
@param format: Dokumentformat-Enum-Typ von Format.
@param language: Wörterbuch für die Rechtschreibprüfung.

`use_user_dictionary(self, dictionaryPath: str)`
:
Ermöglicht die Verwendung eines eigenen Wörterbuchs für die Rechtschreibkorrektur.
@param dictionaryPath: Vollständiger Pfad zum Benutzerdictionary (Häufigkeitsdictionary).
Dateiformat des Wörterbuchs:
Klartextdatei in UTF-8-Kodierung.
Wort und Wortfrequenz sind durch ein Komma getrennt, das Wort wird in der ersten Spalte und die Frequenz in der zweiten Spalte erwartet.
Jedes Wort‑Frequenz‑Paar befindet sich in einer eigenen Zeile. Eine Zeile ist definiert als eine Zeichenfolge, gefolgt von einem Zeilenumbruch (", " ), einem Wagenrücklauf ("
"), a carriage return ("
\"),
oder ein Wagenrücklauf, dem sofort ein Zeilenumbruch folgt(\"

\").
Jedes Wort muss in Kleinbuchstaben geschrieben sein.
Beispiel:
\code
word,5984819
hello,5761742
down,5582768
\endcode

`RectangleOutput(javaClass)`
:
Daten zu erkannten Textbereichen oder Zeilen.
\code
source - Der vollständige Pfad zur Datei oder URL, falls vorhanden. Leer für Streams, Byte-Arrays, Base64.
page - Seitennummer.
image_index - Sequenznummer des Bildes auf der Seite.
rectangles - Liste der erkannten Textbereiche oder Zeilen.
\endcode

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Daten zum Schräglagewinkel in Grad und zum Dateinamen.
\code
source - Der vollständige Pfad zur Datei oder URL, falls vorhanden. Leer für Streams, Byte-Arrays, Base64.
page - Seitennummer.
image_index - Sequenznummer des Bildes auf der Seite.
angle - Schrägwinkel in Grad.
\endcode

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:


### Siehe auch

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)