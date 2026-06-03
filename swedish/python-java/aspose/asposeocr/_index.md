---
title: "AsposeOcr"
second_title: "Aspose.OCR för Python via Java API-referens"
description: 
type: docs
weight: 11
url: /sv/python-java/aspose/asposeocr/
---


Modul asposeocr
================
Python-gränssnitt till Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
medan lättanvänd optisk teckenigenkänning (OCR)
motor för dina Python‑applikationer och anteckningsböcker.
På mindre än **10** kodrader, kan du känna igen
text på **28** språk baserade på latin, kyrilliska,
och asiatiska skript, returnerar resultat i de mest populära
dokument- och datautbytesformat.
Det är inte nödvändigt att lära sig komplexa matematiska modeller,
bygg maskininlärningsalgoritmer och träna neurala
nätverk — vårt enkla och robusta API gör allt åt dig.

Klasser
-------

`AsposeOcr()`
:
AsposeOcr huvudklass för igenkänning.
    
Detta exempel visar hur man känner igen en bild.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Statiska metoder

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Tillåter att hämta flersidigt dokument från en lista med RecognitionResult-objekt.
@param fullFileName: Filnamn med en sökväg för att spara igenkänningsresultatet i det valda formatet.
@param saveFormat: Dokumentformat (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Metoder

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Beräknar snedvinklarna för en bild.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans. Behållaren med källor.
@return: Lista med snedvinklar i grader - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Kontrollera om två bilder innehåller samma text.
@param fullPath1: Sökväg till den första bilden.
@param fullPath2: Sökväg till den andra bilden.
@param settings: Inställningar för igenkänning.
@param ignoreCase: True - betyder en skiftlägesokänslig sökning.
@return: True om bilderna har samma text (90 % likhet).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Korrigerar text (ersätter felstavade ord).
@param text: Text för korrigering.
@param language: Ordbok att använda SpellCheckLanguage.
@return: Text med ersatta ord.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Detekterar textområden på bilder.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param areasType: Bestämmer vilka rektanglar som ska returneras - rad, stycken eller ord.
@param isDetectAreas: Aktivera automatisk detektering av textområden.
@return: Lista med RectangleOutput med detekterade textområden eller rader.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Kontrollera om bilden innehåller den angivna textfragmentet.
@param fullPath: Sökväg till bilden.
@param text: Textfragment för sökning på bilden.
@param settings: Inställningar för igenkänning.
@param ignoreCase: True - betyder en skiftlägesokänslig sökning.
@return: True om bilden innehåller textfragmentet. False - bilden innehåller inte textfragmentet.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Jämför texterna på de två bilderna och returnera ett tal som representerar hur lika de är (0 till 1).
@param fullPath1: Sökväg till den första bilden.
@param fullPath2: Sökväg till den andra bilden.
@param settings: Inställningar för igenkänning.
@param ignoreCase: True - betyder en skiftlägesokänslig sökning.
@return: 0 betyder att texterna är helt olika; 1 betyder att texterna är identiska.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Identifierar bild med möjlighet att ange RecognitionSettings.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: RecognitionSettings-objekt.
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Identifierar registreringsskylt med möjlighet att ange CarPlateRecognitionSettings.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: CarPlateRecognitionSettings
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Identifierar text på bild av god kvalitet. Använder inte automatisk korrigering av bildskevhet och textområden
detektering.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Identifierar ID-kort med möjlighet att ange IDCardRecognitionSettings.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: IDCardRecognitionSettings
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Identifiera faktura med möjlighet att ange InvoiceRecognitionSettings
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: InvoiceRecognitionSettings
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Identifierar enkellinjebild med möjlighet att ange RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: RecognitionSettings-objekt.
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Känner igen pass med möjlighet att ange PassportRecognitionSettings.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: PassportRecognitionSettings
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Känn igen kvitton med möjlighet att ange ReceiptRecognitionSettings.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@param settings: ReceiptRecognitionSettings
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Känner igen text på gatufoton.
Extrahera text från gatufoton, trafikkamerabilder, ID-kort, körkort och andra bilder med gles text och brusiga/färgade bakgrunder.
Stöder GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, binärt fält, mapp, array, zip‑arkiv, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. instans.
@return: RecognitionResult-lista med bilders igenkänningsresultat.

`shutdown(self)`
:
Stäng av JVM-maskinen.

`ImageProcessing()`
:
Hjälparklass för Aspose OCR-biblioteket. Tillåter förbehandling och sparande av bilder.

### Statiska metoder

`save(images, folderPath)`
:
Använd bildbehandling för att förbättra OCR-noggrannheten.
Skapa en lista med filter som kommer att tillämpas på inmatningsbilden i den ordning du anger.
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
Du behöver inte alla. Ställ in bara det du behöver.
@param images: OcrInput-objekt som innehåller olika bilder OcrInput.
@param folderPath: Sökväg utan bildnamn för att spara bearbetade bilder.
@return: OcrInput-objekt som innehåller resultatet av bearbetade bilder OcrInput.


### Se även

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)