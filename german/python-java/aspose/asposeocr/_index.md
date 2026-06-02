---
title: "AsposeOcr"
second_title: "Aspose.OCR für Python via Java API-Referenz"
description: 
type: docs
weight: 11
url: /de/python-java/aspose/asposeocr/
---


Modul asposeocr
================
Python-Schnittstelle zu Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
bei gleichzeitig benutzerfreundlicher optischer Zeichenerkennung (OCR)
Engine für Ihre Python-Anwendungen und Notebooks.
In weniger als **10** Codezeilen können Sie erkennen
Text in **28** Sprachen basierend auf Lateinisch, Kyrillisch,
und asiatischen Schriften, die Ergebnisse in den beliebtesten
Dokument- und Datenaustauschformate.
Es ist nicht nötig, komplexe mathematische Modelle zu lernen,
Maschinelle Lernalgorithmen erstellen und neuronale
Netzwerke — unsere einfache und robuste API erledigt alles für Sie.

Klassen
-------

`AsposeOcr()`
:
AsposeOcr Hauptklasse für die Erkennung.
    
Dieses Beispiel zeigt, wie man ein Bild erkennt.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Statische Methoden

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Ermöglicht das Erstellen eines mehrseitigen Dokuments aus einer Liste von RecognitionResult-Objekten.
@param fullFileName: Dateiname mit Pfad zum Speichern des Erkennungsergebnisses im ausgewählten Format.
@param saveFormat: Dokumentformat (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Methoden

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Berechnet die Schrägwinkel eines Bildes.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz. Der Container mit Quellen.
@return: Liste der Schrägwinkel in Grad - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Prüft, ob zwei Bilder denselben Text enthalten.
@param fullPath1: Pfad zum ersten Bild.
@param fullPath2: Pfad zum zweiten Bild.
@param settings: Erkennungseinstellungen.
@param ignoreCase: True - bedeutet eine Groß-/Kleinschreibung-ignorierende Suche.
@return: True, wenn die Bilder denselben Text haben (90 % Ähnlichkeit).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Korrigiert Text (ersetzt falsch geschriebene Wörter).
@param text: Text zur Korrektur.
@param language: Wörterbuch, das SpellCheckLanguage verwendet.
@return: Text mit ersetzten Wörtern.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Erkennt Textbereiche in Bildern.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param areasType: Bestimmt, welche Rechtecke zurückgegeben werden - Zeile, Absätze oder Wörter.
@param isDetectAreas: Aktiviert die automatische Erkennung von Textbereichen.
@return: Liste von RectangleOutput mit erkannten Textbereichen oder Zeilen.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Prüft, ob das Bild das angegebene Textfragment enthält.
@param fullPath: Pfad zum Bild.
@param text: Textfragment zum Suchen im Bild.
@param settings: Erkennungseinstellungen.
@param ignoreCase: True - bedeutet eine Groß-/Kleinschreibung-ignorierende Suche.
@return: True, wenn das Bild das Textfragment enthält. False - das Bild enthält das Textfragment nicht.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Vergleiche die Texte auf den beiden Bildern und gib eine Zahl zurück, die angibt, wie ähnlich sie sind (0 bis 1).
@param fullPath1: Pfad zum ersten Bild.
@param fullPath2: Pfad zum zweiten Bild.
@param settings: Erkennungseinstellungen.
@param ignoreCase: True - bedeutet eine Groß-/Kleinschreibung-ignorierende Suche.
@return: 0 bedeutet, dass die Texte völlig unterschiedlich sind; 1 bedeutet, dass die Texte identisch sind.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Bild mit der Möglichkeit, RecognitionSettings anzugeben.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: RecognitionSettings-Objekt.
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt das Autokennzeichen mit der Möglichkeit, CarPlateRecognitionSettings anzugeben.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: CarPlateRecognitionSettings
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Text auf einem Bild von guter Qualität. Verwendet keine automatische Bildschräglagenkorrektur und Textbereiche
Erkennung.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Personalausweis mit der Möglichkeit, IDCardRecognitionSettings anzugeben.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: IDCardRecognitionSettings
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Rechnung mit der Möglichkeit, InvoiceRecognitionSettings anzugeben
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: InvoiceRecognitionSettings
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt einzeilige Bild mit der Möglichkeit, RecognitionSettings anzugeben.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: RecognitionSettings-Objekt.
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Reisepässe mit der Möglichkeit, PassportRecognitionSettings anzugeben.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: PassportRecognitionSettings
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Quittungen mit der Möglichkeit, ReceiptRecognitionSettings anzugeben.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@param settings: ReceiptRecognitionSettings
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Erkennt Text auf Straßenfotos.
Extrahiert Text aus Straßenfotos, Verkehrsüberwachungskamerabildern, Ausweisen, Führerscheinen und anderen Bildern mit spärlichem Text und verrauschten/farbigem Hintergrund.
Unterstützt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, Binär-Array, Ordner, Array, ZIP-Archiv, URL, Base64.
@param input: :py:any:`~aspose.models.OcrInput`. Instanz.
@return: RecognitionResult-Liste mit den Erkennungsergebnissen der Bilder.

`shutdown(self)`
:
Fährt die JVM-Maschine herunter.

`ImageProcessing()`
:
Hilfsklasse für die Aspose OCR-Bibliothek. Ermöglicht das Vorverarbeiten und Speichern von Bildern.

### Statische Methoden

`save(images, folderPath)`
:
Verwenden Sie die Bildverarbeitung, um die Genauigkeit der OCR zu verbessern.
Erstellen Sie eine Liste von Filtern, die in der von Ihnen angegebenen Reihenfolge auf das Eingabebild angewendet werden.
\code
filters = new PreprocessingFilter();
filters.add(PreprocessingFilter.auto_dewarping());
filters.add(PreprocessingFilter.invert());
filters.add(PreprocessingFilter.threshold(150));
filters.add(PreprocessingFilter.binarize());
filters.add(PreprocessingFilter.rotate(180));
filters.add(PreprocessingFilter.scale(6));
filters.add(PreprocessingFilter.dilate());
        
images = OcrInput(InputType.PDF, filters);
\endcode
Sie benötigen nicht alle. Legen Sie nur fest, was Sie benötigen.
@param images: OcrInput-Objekt, das verschiedene Bilder enthält OcrInput.
@param folderPath: Pfad ohne Bildnamen zum Speichern der verarbeiteten Bilder.
@return: OcrInput-Objekt, das das Ergebnis der verarbeiteten Bilder enthält OcrInput.


### Siehe auch

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)