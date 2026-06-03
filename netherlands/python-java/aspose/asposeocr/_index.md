---
title: "AsposeOcr"
second_title: "Aspose.OCR voor Python via Java API-referentie"
description: 
type: docs
weight: 11
url: /nl/python-java/aspose/asposeocr/
---


Module asposeocr
================
Python-interface voor de Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
terwijl gebruiksvriendelijke optische tekenherkenning (OCR)
engine voor uw Python-toepassingen en notebooks.
In minder dan **10** regels code kunt u herkennen
tekst in **28** talen gebaseerd op Latijn, Cyrillisch,
en Aziatische scripts, waarbij resultaten worden geretourneerd in de meest populaire
document- en gegevensuitwisselingsformaten.
Het is niet nodig om complexe wiskundige modellen te leren,
machine-learning-algoritmen te bouwen en neurale
netwerken — onze eenvoudige en robuuste API doet alles voor u.

Klassen
-------

`AsposeOcr()`
:
AsposeOcr hoofdklasse voor herkenning.
    
Dit voorbeeld toont hoe een afbeelding te herkennen.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Statische methoden

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Staat toe een meerpagina-document te verkrijgen uit een lijst van RecognitionResult-objecten.
@param fullFileName: Bestandsnaam met pad voor het opslaan van het herkenningsresultaat in het geselecteerde formaat.
@param saveFormat: Documentformaat (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Methoden

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Berekent de scheefstandhoeken van een afbeelding.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie. De container met bronnen.
@return: Lijst van scheefstandhoeken in graden - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Controleer of twee afbeeldingen dezelfde tekst bevatten.
@param fullPath1: Pad naar de eerste afbeelding.
@param fullPath2: Pad naar de tweede afbeelding.
@param settings: Herkenningsinstellingen.
@param ignoreCase: True - betekent een hoofdletterongevoelige zoekopdracht.
@return: True als afbeeldingen dezelfde tekst hebben (90 % overeenkomst).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corrigeert tekst (vervangt verkeerd gespelde woorden).
@param text: Tekst voor correctie.
@param language: Woordenboek om SpellCheckLanguage te gebruiken.
@return: Tekst met vervangen woorden.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Detecteert tekstgebieden op afbeeldingen.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param areasType: Bepaalt welke rechthoeken moeten worden geretourneerd - regel, alinea's of woorden.
@param isDetectAreas: Schakel automatische detectie van tekstgebieden in.
@return: Lijst van RectangleOutput met gedetecteerde tekstgebieden of regels.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Controleer of de afbeelding het opgegeven tekstfragment bevat.
@param fullPath: Pad naar de afbeelding.
@param text: Tekstfragment voor zoeken op de afbeelding.
@param settings: Herkenningsinstellingen.
@param ignoreCase: True - betekent een hoofdletterongevoelige zoekopdracht.
@return: True als de afbeelding het tekstfragment bevat. False - afbeelding bevat het tekstfragment niet.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Vergelijk de teksten op de twee afbeeldingen en retourneer een getal dat aangeeft hoe vergelijkbaar ze zijn (0 tot 1).
@param fullPath1: Pad naar de eerste afbeelding.
@param fullPath2: Pad naar de tweede afbeelding.
@param settings: Herkenningsinstellingen.
@param ignoreCase: True - betekent een hoofdletterongevoelige zoekopdracht.
@return: 0 betekent dat de teksten volledig verschillend zijn; 1 betekent dat de teksten identiek zijn.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herkent afbeelding met de mogelijkheid om RecognitionSettings op te geven.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: RecognitionSettings-object.
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herkent kentekenplaat met de mogelijkheid om CarPlateRecognitionSettings op te geven.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: CarPlateRecognitionSettings
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herkent tekst op een afbeelding van goede kwaliteit. Gebruikt geen automatische correctie van beeldscheefstand en tekstgebieden
detectie.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herkent identiteitskaart met de mogelijkheid om IDCardRecognitionSettings op te geven.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: IDCardRecognitionSettings
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herken factuur met de mogelijkheid om InvoiceRecognitionSettings op te geven
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: InvoiceRecognitionSettings
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herkent een eenregelige afbeelding met de mogelijkheid om RecognitionSettings op te geven.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: RecognitionSettings-object.
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herken paspoorten met de mogelijkheid om PassportRecognitionSettings op te geven.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: PassportRecognitionSettings
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herken bonnen met de mogelijkheid om ReceiptRecognitionSettings op te geven.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@param settings: ReceiptRecognitionSettings
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Herken tekst op straatfoto's.
Extraheer tekst uit straatfoto's, verkeerscamera-afbeeldingen, ID-kaarten, rijbewijzen en andere afbeeldingen met weinig tekst en ruisvolle/kleurige achtergronden.
Ondersteunt GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binaire array, map, array, zip‑archief, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instantie.
@return: RecognitionResult-lijst met herkenningsresultaten van afbeeldingen.

`shutdown(self)`
:
Schakel de JVM-machine uit.

`ImageProcessing()`
:
Helperklasse voor de Aspose OCR-bibliotheek. Stelt in staat om afbeeldingen voor te verwerken en op te slaan.

### Statische methoden

`save(images, folderPath)`
:
Gebruik beeldverwerking om de nauwkeurigheid van OCR te verbeteren.
Maak een lijst met filters die op de invoerafbeelding worden toegepast in de volgorde die je opgeeft.
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
Je hebt ze niet allemaal nodig. Stel alleen in wat je nodig hebt.
@param images: OcrInput object dat verschillende afbeeldingen bevat OcrInput.
@param folderPath: Pad zonder afbeeldingsnamen voor het opslaan van verwerkte afbeeldingen.
@return: OcrInput object dat de verwerkte afbeeldingen bevat OcrInput.


### Zie ook

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)