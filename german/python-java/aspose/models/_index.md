---
title: "Modelle"
second_title: "Aspose.OCR für Python via Java API-Referenz"
description: 
type: docs
weight: 271
url: /de/python-java/aspose/models/
---

Modulmodelle
=============

Klassen
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bestimmt den Typ der vom Modell erkannten Regionen.
Wird in get_text_areas verwendet, um anzugeben, welches Ergebnis erhalten wird – Absatzkoordinaten oder Zeilenkoordinaten.

### Vorfahren (in MRO)

    * enum.Enum

### Klassenvariablen

`LINES`
:   Setzt Regionen als Zeilen

`PARAGRAPHS`
:   Setzt Regionen als Absätze

`WORDS`
:   Setzt Regionen als Wörter

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bestimmt den Typ des für die Flächenerkennung verwendeten neuronalen Netzwerks.
Wird in RecognitionSettings verwendet, um anzugeben, welchen Bildtyp Sie erkennen möchten.

### Vorfahren (in MRO)

    * enum.Enum

### Klassenvariablen

`COMBINE`
:   Erkennt Absätze mit Text und verwendet dann ein anderes NN-Modell, um Bereiche innerhalb der Absätze zu erkennen.
Besser für Bilder mit komplexer Struktur.

`CURVED_TEXT`
:   Erkennt Zeilen und erkennt Text auf gekrümmten Bildern.
Bevorzugter Modus für Fotos von Buch- und Zeitschriftenseiten.

`DOCUMENT`
:   Erkennt Absätze und nutzt ein NN-Modell für Dokumente.
Besser für mehrspaltige Dokumente, Dokumente mit Bildern oder mit anderen Nicht-Text-Objekten.

`NONE`
:   Erkennt keine Absätze.
Besser für ein einfaches einspaltiges Dokument ohne Bilder.

`PHOTO`
:   Erkennt Absätze und nutzt ein NN-Modell für Fotos.
Besser für ein Bild mit vielen Bildern und anderen Nicht-Text-Objekten.

`TABLE`
:   Erkennt Zellen mit Text.
Bevorzugter Modus für Bilder mit Tabellenstruktur.

`TEXT_IN_WILD`
:   Ein super-leistungsfähiges neuronales Netzwerk, das auf das Extrahieren von Wörtern aus Bildern niedriger Qualität spezialisiert ist, wie Straßenfotos, Kennzeichen, Passfotos, Zählerfotos und Fotos mit verrauschten Hintergründen.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Format zum Speichern des Erkennungsergebnisses als Dokument.

### Vorfahren (in MRO)

    * enum.Enum

### Klassenvariablen

`DOCX`
:   Speichert das Ergebnis als Office Open XML Word-Verarbeitungs-ML-Dokument (makrofrei).

`EPUB`
:   Speichert das Dokument als EPUB-Datei.

`HTML`
:   Speichert das Dokument als HTML‑Datei.

`JSON`
:   Speichert das Ergebnis als Klartext, geschrieben in JavaScript‑Objektnotation.

`PDF`
:   Speichert das Ergebnis als PDF (Adobe Portable Document) Dokument.

`PDF_NO_IMG`
:   Speichert das Dokument als durchsuchbares PDF (Adobe Portable Document) Dokument ohne Bild.

`RTF`
:   Speichert das Dokument als RTF‑Datei.

`TEXT`
:   Speichert das Ergebnis im Klartextformat.

`XLSX`
:   Speichert das Ergebnis als Excel (2007 und später) Arbeitsmappendokument.

`XML`
:   Speichert das Ergebnis als XML‑Dokument.

`ImageData(javaClass)`
:

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Typen von Bild‑/Dokumenten für Verarbeitung / Erkennung.

### Vorfahren (in MRO)

    * enum.Enum

### Klassenvariablen

`BASE64`
:   base64‑Zeichenkette mit dem Bild oder Pfad zur .txt‑Datei mit dem base64‑Inhalt. Unterstützt GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Pfad zum Verzeichnis. Verschachtelte Archive und Ordner werden nicht unterstützt.
Unterstützt GIF, PNG, JPEG, BMP, TIFF.
Standardmäßig ist die Anzahl der verarbeiteten Bilder alle.

`PDF`
:   Gescanntes PDF-Dokument aus Datei oder aus Binär-Array.

`SINGLE_IMAGE`
:   Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF, Binär-Array.

`TIFF`
:   Mehrseitiges TIFF-, TIF-Dokument aus Datei oder aus InputStream.

`URL`
:   Link zum Bild. Unterstützt GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Vollständiger Name des ZIP-Archivs. Verschachtelte Archive und Ordner werden nicht unterstützt.
Unterstützt GIF, PNG, JPEG, BMP, TIFF, JFIF.
Standardmäßig ist die Anzahl der verarbeiteten Bilder alle.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Sprachmodell für die Erkennung.

### Vorfahren (in MRO)

    * enum.Enum

### Klassenvariablen

`BEL`
:   Belarussisches Alphabet

`BUL`
:   Bulgarisches Alphabet

`CHI`
:   Chinesisches Alphabet

`CYRILLIC`
:   Mehrsprachige Unterstützung (kyrillisches Alphabet)

`CZE`
:   Tschechisches Alphabet

`DAN`
:   Dänisches Alphabet

`DEU`
:   Deutsches Alphabet

`DUM`
:   Niederländisches Alphabet

`ENG`
:   Englisches Alphabet

`EST`
:   Estnisches Alphabet

`FIN`
:   Finnisches Alphabet

`FRA`
:   Französisches Alphabet

`HIN`
:   Hindi-Alphabet

`ITA`
:   Italienisches Alphabet

`KAZ`
:   Kasachisches Alphabet

`LATIN`
:   Mehrsprachige Unterstützung (lateinisches Alphabet)

`LAV`
:   Lettisches Alphabet

`LIT`
:   Litauisches Alphabet

`NONE`
:   Mehrsprachige Unterstützung

`NOR`
:   Norwegisches Alphabet

`POL`
:   Polnisches Alphabet

`POR`
:   Portugiesisches Alphabet

`RUM`
:   Rumänisches Alphabet

`RUS`
:   Russisches Alphabet

`SLK`
:   Slowakisches Alphabet

`SLV`
:   Slowenisches Alphabet

`SPA`
:   Spanisches Alphabet

`SRP`
:   Serbisches Alphabet

`SRP_HRV`
:   Serbokroatisches Alphabet

`SWE`
:   Schwedisches Alphabet

`UKR`
:   Ukrainisches Alphabet

`ModelsConverter()`
:

### Methoden

`convertInputTypeToJava(jType)`
:

`convertToJavaAreasMode(jType)`
:

`convertToJavaAreasType(jType)`
:

`convertToJavaFormat(jType)`
:

`convertToJavaLanguage(jType)`
:

`convertToJavaSpellCheckLanguage(jType)`
:

`OcrInput(type: models.InputType, filters: models.PreprocessingFilter = None)`
:   Hauptklasse zum Sammeln von Bildern.
    
Konstruktor zum Erstellen des Containers und Festlegen des Typs von Bildern/Dokumenten sowie Filter für die weitere Verarbeitung/Erkennung.
@param type: Legt den Typ der Bilder/Dokumente fest, die dem Container hinzugefügt werden.
@param filters: Legt Verarbeitungsfilter fest, die für die weitere Verarbeitung oder Erkennung angewendet werden.

### Methoden

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Fügt den Pfad oder die URI hinzu, die das Bild für die Erkennung/Verarbeitung enthält.
Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen.
@param fullPath: Pfad zum Bild/Dokument/Ordner/Archiv.
@param startPage: Die erste Seite/das erste Bild für die Verarbeitung/Erkennung. Wird für Dokumente, ZIPs, Ordner verwendet.
@param pagesNumber: Die Gesamtanzahl der Seiten/Bilder für die Verarbeitung/Erkennung. Wird für Dokumente, ZIPs, Ordner verwendet. Standard = alle.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Fügt den InputStream hinzu, der das Bild für die Erkennung/Verarbeitung enthält.
Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: enthält das Bild oder Dokument.
@param startPage: Die erste Seite/das erste Bild für die Verarbeitung/Erkennung. Wird für Dokumente, ZIPs, Ordner verwendet.
@param pagesNumber: Die Gesamtanzahl der Seiten/Bilder für die Verarbeitung/Erkennung. Wird für Dokumente, ZIPs, Ordner verwendet. Standard = alle.

`add_base64(self, base64: str)`
:   Fügen Sie die Base64-Zeichenkette hinzu, die das Bild für die Erkennung / Verarbeitung enthält.
Der Typ des Bildes muss dem im Konstruktor angegebenen Typ entsprechen.
@param base64: Base64-Zeichenkette mit einem einzelnen Bild.

`clear(self)`
:   Setzen Sie die Anzahl der Elemente für die Verarbeitung / Erkennung auf 0.
Löschen Sie die Sammlung.

`clear_filters(self)`
:   Entfernt alle Filter.

`get(self, index: int) -> models.ImageData`
:   Gibt Informationen über das verarbeitete / erkannte Bild zurück.
@param index: Position des Bildes in der Liste.
@return: Das Objekt von ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Anzahl der Elemente für die Verarbeitung / Erkennung.
@return: Anzahl der Elemente.

`PreprocessingFilter()`
:   Basisklasse für Bildverarbeitungsbefehle.

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Klassenvariablen

`JAVA_CLASS_NAME`
:

### Statische Methoden

`auto_denoising()`
:   Aktiviert die Verwendung eines zusätzlichen neuronalen Netzwerks, um das Bild zu verbessern – Rauschen zu reduzieren.
Nützlich für Bilder mit Scan-Artefakten, Verzerrungen, Flecken, Lichthöfen, Farbverläufen, fremden Elementen.
@return: AutoDenoisingFilter-Objekt.

`auto_dewarping()`
:   Korrigiert automatisch geometrische Verzerrungen im Bild.
Extrem ressourcenintensiv!
@return: AutoDewarpingFilter-Objekt.

`auto_skew()`
:   Aktiviert die automatische Bildschrägstellungskorrektur.
@return: AutoSkewFilter-Objekt.

`binarize()`
:   Konvertiert ein Bild in ein Schwarz‑Weiß‑Bild.
Binärbilder sind Bilder, deren Pixel nur zwei mögliche Intensitätswerte haben.
Sie werden normalerweise als Schwarz‑Weiß angezeigt. Numerisch sind die beiden Werte häufig 0 für Schwarz und 255 für Weiß.
Binärbilder werden durch automatische Schwellenwertbestimmung eines Bildes erzeugt.
@return: BinarizeFilter-Objekt.

`binarize_and_dilate()`
:   Die Dilatation fügt Pixel zu den Grenzen von Objekten in einem Bild hinzu.
@return: DilateFilter-Objekt.

`contrast_correction()`
:   Kontrastkorrekturfilter.
@return: ContrastCorrectionFilter-Objekt.

`invert()`
:   Invertiert automatisch die Farben in einem Dokumentenbild.
@return: InvertFilter-Objekt.

`median()`
:   Der Medianfilter durchläuft jedes Element des Bildes und ersetzt jeden Pixel durch den Median seiner Nachbarpixel.
@return: MedianFilter-Objekt.

`resize(width: int, height: int)`
:   Bild skalieren – Auf- oder Abskalieren der Bildauflösung.
@param width: Die neue Breite des Bildes.
@param height: Die neue Höhe des Bildes.
@return: ResizeFilter-Objekt.

`rotate(angle: float)`
:   Originalbild drehen.
@param angle: Drehwinkel. Wert von -360 bis 360.
@return: RotateFilter-Objekt.

`scale(ratio: float)`
:   Bild skalieren - Auf- oder Abskalieren der Bildauflösung.
InterpolationFilterType bilinear oder nächster Nachbar.
@param ratio: Der Skalierungsfaktor. Empfohlener Wert von 0,1 bis 1 zum Verkleinern. Von 1 bis 10 zum Vergrößern.
@return: ScaleFilter-Objekt.

`threshold(value: int)`
:   Erstelle ein Binärbild, indem ein Schwellenwert für die Pixelintensität des Originalbildes festgelegt wird.
@param value: Der Maximalwert.
@return: BinarizeFilter-Objekt.

`to_grayscale()`
:   Konvertiert ein Bild in ein Graustufenbild.
Graustufenbilder haben 256 Helligkeitsstufen (0 bis 255).
@return: GrayscaleFilter-Objekt.

### Methoden

`add(self, filter)`
:   Filter zur Sammlung hinzufügen für weitere Vorverarbeitung.
@param filter: PreprocessingFilter-Objekt.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Darstellung eines falsch geschriebenen Wortes mit zusätzlichen Daten.

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Wörterbuchsprache für die Rechtschreibkorrektur.

### Vorfahren (in MRO)

    * enum.Enum

### Klassenvariablen

`CZE`
:   Tschechisches Wörterbuch

`DAN`
:   Dänisches Wörterbuch

`DEU`
:   Deutsches Wörterbuch

`DUM`
:   Niederländisches Wörterbuch

`ENG`
:   Englisches Wörterbuch

`EST`
:   Estnisches Wörterbuch

`FIN`
:   Finnisches Wörterbuch

`FRA`
:   Französisches Wörterbuch

`ITA`
:   Italienisches Wörterbuch

`LAV`
:   Lettisches Wörterbuch

`LIT`
:   Litauisches Wörterbuch

`POL`
:   Polnisches Wörterbuch

`POR`
:   Portugiesisches Wörterbuch

`RUM`
:   Rumänisches Wörterbuch

`SLK`
:   Slowakisches Wörterbuch

`SLV`
:   Slowenisches Wörterbuch

`SPA`
:   Spanisches Wörterbuch

`SWE`
:   Schwedisches Wörterbuch

`SuggestedWord(javaClass)`
:   Rechtschreibvorschlag zurückgegeben von get_spell_check_error_list.

### Vorfahren (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:


### Siehe auch

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)