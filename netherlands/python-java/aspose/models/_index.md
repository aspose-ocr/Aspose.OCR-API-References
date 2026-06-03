---
title: "modellen"
second_title: "Aspose.OCR voor Python via Java API-referentie"
description: 
type: docs
weight: 271
url: /nl/python-java/aspose/models/
---

Module modellen
=============

Klassen
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bepaalt het type regio's dat door het model wordt gedetecteerd.
Gebruikt in get_text_areas om aan te geven welk resultaat wordt verkregen – alinea‑coördinaten of regel‑coördinaten.

### Voorouders (in MRO)

    * enum.Enum

### Klassevariabelen

`LINES`
:   Stelt regio's in als regels

`PARAGRAPHS`
:   Stelt regio's in als alinea's

`WORDS`
:   Stelt regio's in als woorden

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bepaalt het type neuraal netwerk dat wordt gebruikt voor gebiedsdetectie.
Gebruikt in RecognitionSettings om het type afbeelding op te geven dat u wilt herkennen.

### Voorouders (in MRO)

    * enum.Enum

### Klassevariabelen

`COMBINE`
:   Detecteert alinea's met tekst en gebruikt vervolgens een ander NN-model om gebieden binnen de alinea's te detecteren.
Beter voor afbeeldingen met een complexe structuur.

`CURVED_TEXT`
:   Detecteert lijnen en herkent tekst op gebogen afbeeldingen.
Voorkeursmodus voor foto’s van boek- en tijdschriftpagina’s.

`DOCUMENT`
:   Detecteert alinea's met behulp van een NN-model voor documenten.
Beter voor meerkolomsdocumenten, documenten met afbeeldingen of met andere niet-tekstobjecten.

`NONE`
:   Detecteert geen alinea's.
Beter voor een eenvoudig éénkolomsdocument zonder afbeeldingen.

`PHOTO`
:   Detecteert alinea's met een NN-model voor foto’s.
Beter voor afbeeldingen met veel afbeeldingen en andere niet-tekstobjecten.

`TABLE`
:   Detecteert cellen met tekst.
Aanbevolen modus voor afbeeldingen met een tabelstructuur.

`TEXT_IN_WILD`
:   Een superkrachtig neuraal netwerk gespecialiseerd in het extraheren van woorden uit afbeeldingen van lage kwaliteit, zoals straatfoto’s, kentekenplaten, paspoortfoto’s, meterfoto’s en foto’s met ruisrijke achtergronden.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Formaat om herkenningsresultaat op te slaan als document.

### Voorouders (in MRO)

    * enum.Enum

### Klassevariabelen

`DOCX`
:   Slaat het resultaat op als een Office Open XML Word-verwerkings‑ML‑document (macro‑vrij).

`EPUB`
:   Slaat het document op als een EPUB‑bestand.

`HTML`
:   Slaat het document op als een HTML‑bestand.

`JSON`
:   Slaat het resultaat op als platte tekst geschreven in JavaScript‑objectnotatie.

`PDF`
:   Slaat het resultaat op als een PDF (Adobe Portable Document) Document.

`PDF_NO_IMG`
:   Slaat het document op als een doorzoekbare PDF (Adobe Portable Document) Document zonder afbeelding.

`RTF`
:   Slaat het document op als een rtf‑bestand.

`TEXT`
:   Slaat het resultaat op in het platte‑tekstformaat.

`XLSX`
:   Slaat het resultaat op als een Excel (2007 en later) werkboek Document.

`XML`
:   Slaat het resultaat op als een XML‑Document.

`ImageData(javaClass)`
:

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Types van afbeelding-/documenten voor verwerking / herkenning.

### Voorouders (in MRO)

    * enum.Enum

### Klassevariabelen

`BASE64`
:   base64‑string met de afbeelding of pad naar het .txt‑bestand met de base64‑inhoud. Ondersteunt GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Pad naar de map. Geneste archieven en mappen worden niet ondersteund.
Ondersteunt GIF, PNG, JPEG, BMP, TIFF.
Standaard aantal verwerkte afbeeldingen is alle.

`PDF`
:   Gescand PDF-document van bestand of van binaire array.

`SINGLE_IMAGE`
:   Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF, binaire array.

`TIFF`
:   Meervoudige pagina TIFF, TIF-document van bestand of van InputStream.

`URL`
:   Link op de afbeelding. Ondersteunt GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Volledige naam van het ZIP-archief. Geneste archieven en mappen worden niet ondersteund.
Ondersteunt GIF, PNG, JPEG, BMP, TIFF, JFIF.
Standaard aantal verwerkte afbeeldingen is alle.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Taalmodel voor de herkenning.

### Voorouders (in MRO)

    * enum.Enum

### Klassevariabelen

`BEL`
:   Wit-Russisch alfabet

`BUL`
:   Bulgaars alfabet

`CHI`
:   Chinees alfabet

`CYRILLIC`
:   Multi - taal (cyrillisch alfabet) ondersteuning

`CZE`
:   Tsjechisch alfabet

`DAN`
:   Deens alfabet

`DEU`
:   Duitse alfabet

`DUM`
:   Nederlands alfabet

`ENG`
:   Engelse alfabet

`EST`
:   Estse alfabet

`FIN`
:   Finse alfabet

`FRA`
:   Franse alfabet

`HIN`
:   Hindi-alfabet

`ITA`
:   Italiaanse alfabet

`KAZ`
:   Kazachse alfabet

`LATIN`
:   Multi - taal(latijns alfabet) ondersteuning

`LAV`
:   Letse alfabet

`LIT`
:   Litouwse alfabet

`NONE`
:   Multi - taal ondersteuning

`NOR`
:   Noorse alfabet

`POL`
:   Poolse alfabet

`POR`
:   Portugese alfabet

`RUM`
:   Roemeense alfabet

`RUS`
:   Russische alfabet

`SLK`
:   Slowaakse alfabet

`SLV`
:   Sloveense alfabet

`SPA`
:   Spaanse alfabet

`SRP`
:   Servische alfabet

`SRP_HRV`
:   Servokroatische alfabet

`SWE`
:   Zweedse alfabet

`UKR`
:   Oekraïense alfabet

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
:   Hoofdklasse om afbeeldingen te verzamelen.
    
Constructor om een container te maken en het type afbeeldingen / documenten en filters in te stellen voor verdere verwerking / herkenning.
@param type: Stel het type afbeeldingen/documenten in dat aan de container wordt toegevoegd.
@param filters: Stel verwerkingsfilters in die worden toegepast voor verdere verwerking of herkenning.

### Methoden

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Voeg het pad of de URI toe die de afbeelding bevat voor herkenning / verwerking.
Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.
@param fullPath: Pad naar de afbeelding / document / map / archief.
@param startPage: De eerste pagina/afbeelding voor verwerking / herkenning. Gebruik voor documenten, zip, mappen.
@param pagesNumber: Het totale aantal pagina's/afbeeldingen voor verwerking / herkenning. Gebruik voor documenten, zip, mappen. Standaard = allemaal.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Voeg de InputStream toe die de afbeelding bevat voor herkenning / verwerking.
Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: bevat de afbeelding of het document.
@param startPage: De eerste pagina/afbeelding voor verwerking / herkenning. Gebruik voor documenten, zip, mappen.
@param pagesNumber: Het totale aantal pagina's/afbeeldingen voor verwerking / herkenning. Gebruik voor documenten, zip, mappen. Standaard = allemaal.

`add_base64(self, base64: str)`
:   Voeg de base64‑string toe die de afbeelding voor herkenning / verwerking bevat.
Het type van de afbeelding moet overeenkomen met het type dat in de constructor is opgegeven.
@param base64: Base64‑string met één afbeelding.

`clear(self)`
:   Stel het aantal items voor verwerking / herkenning in op 0.
Maak de collectie leeg.

`clear_filters(self)`
:   Verwijder alle filters.

`get(self, index: int) ‑> models.ImageData`
:   Retourneert informatie over de verwerkte / herkende afbeelding.
@param index: Positie van de afbeelding in de lijst.
@return: Het object van ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Aantal items voor verwerking / herkenning.
@return: Aantal items.

`PreprocessingFilter()`
:   Basisklasse voor afbeeldingsverwerkingsopdrachten.

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Klassevariabelen

`JAVA_CLASS_NAME`
:

### Statische methoden

`auto_denoising()`
:   Maakt het gebruik van een extra neuraal netwerk mogelijk om de afbeelding te verbeteren - ruis te verminderen.
Handig voor afbeeldingen met scanartefacten, vervormingen, vlekken, schitteringen, verlopen, vreemde elementen.
@return: AutoDenoisingFilter‑object.

`auto_dewarping()`
:   Corrigeert automatisch geometrische vervormingen in de afbeelding.
Zeer intensief in middelen!
@return: AutoDewarpingFilter‑object.

`auto_skew()`
:   Schakelt de automatische beeldscheefcorrectie in.
@return: AutoSkewFilter object.

`binarize()`
:   Converteert een afbeelding naar een zwart-wit afbeelding.
Binaire afbeeldingen zijn afbeeldingen waarvan de pixels slechts twee mogelijke intensiteitswaarden hebben.
Ze worden normaal weergegeven als zwart en wit. Numeriek zijn de twee waarden vaak 0 voor zwart en 255 voor wit.
Binaire afbeeldingen worden geproduceerd door automatische drempelbepaling van een afbeelding.
@return: BinarizeFilter object.

`binarize_and_dilate()`
:   Dilatatie voegt pixels toe aan de randen van objecten in een afbeelding.
@return: DilateFilter object.

`contrast_correction()`
:   Contrastcorrectiefilter.
@return: ContrastCorrectionFilter object.

`invert()`
:   Keert automatisch de kleuren in een documentafbeelding om.
@return: InvertFilter object.

`median()`
:   Het medianfilter loopt door elk element van de afbeelding en vervangt elke pixel door de mediaan van de naburige pixels.
@return: MedianFilter object.

`resize(width: int, height: int)`
:   Schaal afbeelding opnieuw - verhoog of verlaag de resolutie van de afbeelding.
@param width: De nieuwe breedte van de afbeelding.
@param height: De nieuwe hoogte van de afbeelding.
@return: ResizeFilter object.

`rotate(angle: float)`
:   Roteer originele afbeelding.
@param angle: Hoek van rotatie. Waarde van -360 tot 360.
@return: RotateFilter object.

`scale(ratio: float)`
:   Schaal afbeelding opnieuw - Vergroot of verklein de resolutie van de afbeelding.
InterpolationFilterType bilineair of dichtstbijzijnde buur.
@param ratio: De schaalfactor. Aanbevolen waarde van 0,1 tot 1 om te verkleinen. Van 1 tot 10 om te vergroten.
@return: ScaleFilter object.

`threshold(value: int)`
:   Maak een binaire afbeelding op basis van het instellen van een drempelwaarde op de pixelintensiteit van de originele afbeelding.
@param value: De maximale waarde.
@return: BinarizeFilter object.

`to_grayscale()`
:   Converteert een afbeelding naar een grijswaardenafbeelding.
Grijswaardenafbeelding heeft 256 niveaus van licht in de afbeelding (0 tot 255).
@return: GrayscaleFilter object.

### Methoden

`add(self, filter)`
:   Voeg filter toe aan collectie voor verdere voorbewerking.
@param filter: PreprocessingFilter object.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Vertegenwoordigt een verkeerd gespeld woord met extra gegevens.

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Taal van het woordenboek voor spellingscorrectie.

### Voorouders (in MRO)

    * enum.Enum

### Klassevariabelen

`CZE`
:   Tsjechisch woordenboek

`DAN`
:   Deens woordenboek

`DEU`
:   Duits woordenboek

`DUM`
:   Nederlands woordenboek

`ENG`
:   Engels woordenboek

`EST`
:   Estisch woordenboek

`FIN`
:   Fins woordenboek

`FRA`
:   Frans woordenboek

`ITA`
:   Italiaans woordenboek

`LAV`
:   Lets woordenboek

`LIT`
:   Litouws woordenboek

`POL`
:   Pools woordenboek

`POR`
:   Portugees woordenboek

`RUM`
:   Roemeens woordenboek

`SLK`
:   Slowaaks woordenboek

`SLV`
:   Sloveens woordenboek

`SPA`
:   Spaans woordenboek

`SWE`
:   Zweeds woordenboek

`SuggestedWord(javaClass)`
:   Spelling suggestie geretourneerd door get_spell_check_error_list.

### Voorouders (in MRO)

    * aspose.helper.BaseJavaClass

### Methoden

`initParams(self)`
:


### Zie ook

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)