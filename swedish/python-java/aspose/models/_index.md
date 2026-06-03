---
title: "modeller"
second_title: "Aspose.OCR för Python via Java API-referens"
description: 
type: docs
weight: 271
url: /sv/python-java/aspose/models/
---

Modulmodeller
=============

Klasser
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bestämmer typen av regioner som detekteras av modellen.
Används i get_text_areas för att ange vilket resultat som kommer att erhållas – stycke‑koordinater eller rad‑koordinater.

### Förfäder (i MRO)

    * enum.Enum

### Klassvariabler

`LINES`
:   Anger regioner som rader

`PARAGRAPHS`
:   Anger regioner som stycken

`WORDS`
:   Anger regioner som ord

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Bestämmer typen av neuralt nätverk som används för områdesdetektering.
Används i RecognitionSettings för att ange vilken typ av bild du vill känna igen.

### Förfäder (i MRO)

    * enum.Enum

### Klassvariabler

`COMBINE`
:   Detekterar stycken med text och använder sedan en annan NN-modell för att upptäcka områden inom styckena.
Bättre för bilder med komplex struktur.

`CURVED_TEXT`
:   Detekterar rader och känner igen text på böjda bilder.
Föredragen läge för foton av bok- och magasinblad.

`DOCUMENT`
:   Detekterar stycken och använder NN-modell för dokument.
Bättre för flerkolumnsdokument, dokument med bilder eller med andra icke-textobjekt.

`NONE`
:   Detekterar inte stycken.
Bättre för ett enkelt enkolsdokument utan bilder.

`PHOTO`
:   Detekterar stycken och använder NN-modell för foton.
Bättre för bild med många bilder och andra icke-textobjekt.

`TABLE`
:   Detekterar celler med text.
Föredraget läge för bilder med tabellstruktur.

`TEXT_IN_WILD`
:   Ett superkraftfullt neuralt nätverk specialiserat på att extrahera ord från lågkvalitativa bilder såsom gatufoton, registreringsskyltar, passfoton, mätarfoton och foton med bullriga bakgrunder.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Format för att spara igenkänningsresultat som dokument.

### Förfäder (i MRO)

    * enum.Enum

### Klassvariabler

`DOCX`
:   Sparar resultatet som ett Office Open XML Word-behandlings-ML-dokument (utan makron).

`EPUB`
:   Sparar dokumentet som en EPUB-fil.

`HTML`
:   Sparar dokumentet som en HTML-fil.

`JSON`
:   Sparar resultatet som vanlig text skriven i JavaScript-objektnotation.

`PDF`
:   Sparar resultatet som en PDF (Adobe Portable Document) dokument.

`PDF_NO_IMG`
:   Sparar dokumentet som en sökbar PDF (Adobe Portable Document) dokument utan bild.

`RTF`
:   Sparar dokumentet som en rtf-fil.

`TEXT`
:   Sparar resultatet i vanligt textformat.

`XLSX`
:   Sparar resultatet som ett Excel (2007 och senare) arbetsbokdokument.

`XML`
:   Sparar resultatet som ett XML-dokument.

`ImageData(javaClass)`
:

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Metoder

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Typer av bild-/dokument för bearbetning / igenkänning.

### Förfäder (i MRO)

    * enum.Enum

### Klassvariabler

`BASE64`
:   base64-sträng med bilden eller sökväg till .txt-filen med base64-innehållet. Stöder GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Sökväg till katalogen. Inbäddade arkiv och mappar stöds inte.
Stöder GIF, PNG, JPEG, BMP, TIFF.
Standardantalet bearbetade bilder är alla.

`PDF`
:   Skannad PDF-dokument från fil eller från binärt fält.

`SINGLE_IMAGE`
:   Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF, binärt fält.

`TIFF`
:   Multipage TIFF, TIF-dokument från fil eller från InputStream.

`URL`
:   Länk på bilden. Stöder GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Fullständigt namn på ZIP-arkivet. Inbäddade arkiv och mappar stöds inte.
Stöder GIF, PNG, JPEG, BMP, TIFF, JFIF.
Standardantalet bearbetade bilder är alla.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Språkmodell för igenkänning.

### Förfäder (i MRO)

    * enum.Enum

### Klassvariabler

`BEL`
:   Vitryskt alfabet

`BUL`
:   Bulgariskt alfabet

`CHI`
:   Kinesiskt alfabet

`CYRILLIC`
:   Flerspråkigt (kyrilliskt alfabet) stöd

`CZE`
:   Tjeckiskt alfabet

`DAN`
:   Danskt alfabet

`DEU`
:   tyska alfabetet

`DUM`
:   nederländska alfabetet

`ENG`
:   engelska alfabetet

`EST`
:   estniska alfabetet

`FIN`
:   finska alfabetet

`FRA`
:   franska alfabetet

`HIN`
:   Hindi-alfabetet

`ITA`
:   italienska alfabetet

`KAZ`
:   kazakiska alfabetet

`LATIN`
:   Flerspråkigt (latin alfabet) stöd

`LAV`
:   lettiska alfabetet

`LIT`
:   litauiska alfabetet

`NONE`
:   Flerspråkigt stöd

`NOR`
:   norskt alfabet

`POL`
:   polskt alfabet

`POR`
:   portugisiskt alfabet

`RUM`
:   rumänskt alfabet

`RUS`
:   ryskt alfabet

`SLK`
:   slovakiskt alfabet

`SLV`
:   slovenskt alfabet

`SPA`
:   spanskt alfabet

`SRP`
:   serbiskt alfabet

`SRP_HRV`
:   serbokroatisk alfabet

`SWE`
:   svenskt alfabet

`UKR`
:   ukrainskt alfabet

`ModelsConverter()`
:

### Metoder

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
:   Huvudklass för att samla bilder.
    
Konstruktör för att skapa behållare och ange typen av bilder / dokument samt filter för vidare bearbetning / igenkänning.
@param type: Ange vilken typ av bilder/dokument som ska läggas till i behållaren.
@param filters: Ange bearbetningsfilter som kommer att tillämpas för vidare bearbetning eller igenkänning.

### Metoder

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Lägg till sökvägen eller URI:n som innehåller bilden för igenkänning / bearbetning.
Bildens typ måste motsvara den typ som angavs i konstruktören.
@param fullPath: Sökväg till bilden/dokumentet/mappen/arkivet.
@param startPage: Den första sidan/bilden för bearbetning / igenkänning. Använd för dokument, zip-filer, mappar.
@param pagesNumber: Det totala antalet sidor/bilder för bearbetning / igenkänning. Använd för dokument, zip-filer, mappar. Standard = alla.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Lägg till InputStream som innehåller bilden för igenkänning / bearbetning.
Bildens typ måste motsvara den typ som angavs i konstruktören.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: innehåller bilden eller dokumentet.
@param startPage: Den första sidan/bilden för bearbetning / igenkänning. Använd för dokument, zip-filer, mappar.
@param pagesNumber: Det totala antalet sidor/bilder för bearbetning / igenkänning. Använd för dokument, zip-filer, mappar. Standard = alla.

`add_base64(self, base64: str)`
:   Lägg till base64-strängen som innehåller bilden för igenkänning / bearbetning.
Bildens typ måste motsvara den typ som angavs i konstruktören.
@param base64: Base64-sträng med en enda bild.

`clear(self)`
:   Ställ in antalet objekt för bearbetning / igenkänning till 0.
Rensa samlingen.

`clear_filters(self)`
:   Ta bort alla filter.

`get(self, index: int) ‑> models.ImageData`
:   Returnerar information om bearbetad / igenkänd bild.
@param index: Bildens position i listan.
@return: Objektet av ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Antal objekt för bearbetning / igenkänning.
@return: Antal objekt.

`PreprocessingFilter()`
:   Basklass för bildbehandlingskommandon.

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Klassvariabler

`JAVA_CLASS_NAME`
:

### Statiska metoder

`auto_denoising()`
:   Aktiverar användning av ett extra neuralt nätverk för att förbättra bilden - minska brus.
Användbart för bilder med skanningsartefakter, förvrängning, fläckar, bländningar, gradienter, främmande element.
@return: AutoDenoisingFilter-objekt.

`auto_dewarping()`
:   Korrigerar automatiskt geometriska förvrängningar i bilden.
Extremt resurskrävande!
@return: AutoDewarpingFilter-objekt.

`auto_skew()`
:   Aktiverar den automatiska korrigeringen av bildskevhet.
@return: AutoSkewFilter-objekt.

`binarize()`
:   Konverterar en bild till svart‑vit bild.
Binära bilder är bilder vars pixlar endast har två möjliga intensitetsvärden.
De visas normalt som svart och vit. Numeriskt är de två värdena ofta 0 för svart och 255 för vitt.
Binära bilder skapas genom automatisk tröskelvärdesbestämning av en bild.
@return: BinarizeFilter-objekt.

`binarize_and_dilate()`
:   Dilatation lägger till pixlar på gränserna av objekt i en bild.
@return: DilateFilter-objekt.

`contrast_correction()`
:   Filter för kontrastkorrigering.
@return: ContrastCorrectionFilter-objekt.

`invert()`
:   Inverterar automatiskt färger i en dokumentbild.
@return: InvertFilter-objekt.

`median()`
:   Medianfiltret går igenom varje element i bilden och ersätter varje pixel med medianen av dess närliggande pixlar.
@return: MedianFilter-objekt.

`resize(width: int, height: int)`
:   Skala om bilden – förstora eller förminska bildens upplösning.
@param width: Bildens nya bredd.
@param height: Bildens nya höjd.
@return: ResizeFilter-objekt.

`rotate(angle: float)`
:   Rotera originalbilden.
@param angle: Rotationsvinkel. Värde från -360 till 360.
@return: RotateFilter-objekt.

`scale(ratio: float)`
:   Skala om bilden - Höj eller sänk bildens upplösning.
InterpolationFilterType bilinjär eller närmaste granne.
@param ratio: Skalningsfaktorn. Rekommenderat värde från 0,1 till 1 för att krympa. Från 1 till 10 för att förstora.
@return: ScaleFilter-objekt.

`threshold(value: int)`
:   Skapa en binär bild genom att sätta ett tröskelvärde på pixelintensiteten i originalbilden.
@param value: Maxvärdet.
@return: BinarizeFilter-objekt.

`to_grayscale()`
:   Konverterar en bild till en gråskalebild.
Gråskalebild har 256 ljusnivåer (0 till 255).
@return: GrayscaleFilter-objekt.

### Metoder

`add(self, filter)`
:   Lägg till filter i samlingen för vidare förbehandling.
@param filter: PreprocessingFilter-objekt.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Representerar felstavat ord med ytterligare data.

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Metoder

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Ordboksspråk för stavningskorrigering.

### Förfäder (i MRO)

    * enum.Enum

### Klassvariabler

`CZE`
:   Tjeckisk ordbok

`DAN`
:   Dansk ordbok

`DEU`
:   Tysk ordbok

`DUM`
:   Nederländsk ordbok

`ENG`
:   Engelsk ordbok

`EST`
:   Estnisk ordbok

`FIN`
:   Finsk ordbok

`FRA`
:   Fransk ordbok

`ITA`
:   Italiensk ordbok

`LAV`
:   Lettisk ordbok

`LIT`
:   Litauisk ordbok

`POL`
:   Polsk ordbok

`POR`
:   Portugisisk ordbok

`RUM`
:   Rumänsk ordbok

`SLK`
:   Slovakisk ordbok

`SLV`
:   Slovensk ordbok

`SPA`
:   Spansk ordbok

`SWE`
:   Svensk ordbok

`SuggestedWord(javaClass)`
:   Stavningsförslag returnerat från get_spell_check_error_list.

### Förfäder (i MRO)

    * aspose.helper.BaseJavaClass

### Metoder

`initParams(self)`
:


### Se även

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)