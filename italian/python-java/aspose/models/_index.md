---
title: "modelli"
second_title: "Riferimento API di Aspose.OCR per Python via Java"
description: 
type: docs
weight: 271
url: /it/python-java/aspose/models/
---

Modulo modelli
=============

Classi
-------

`AreasType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Determina il tipo di regioni rilevate dal modello.
Utilizzato in get_text_areas per indicare quale risultato verrà ottenuto – coordinate del paragrafo o coordinate della riga.

### Antenati (in MRO)

    * enum.Enum

### Variabili di classe

`LINES`
:   Imposta le regioni come righe

`PARAGRAPHS`
:   Imposta le regioni come paragrafi

`WORDS`
:   Imposta le regioni come parole

`DetectAreasMode(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Determina il tipo di rete neurale utilizzata per il rilevamento delle aree.
Utilizzato in RecognitionSettings per specificare quale tipo di immagine si desidera riconoscere.

### Antenati (in MRO)

    * enum.Enum

### Variabili di classe

`COMBINE`
:   Rileva paragrafi con testo e poi utilizza un altro modello NN per rilevare le aree all'interno dei paragrafi.
Meglio per immagini con struttura complessa.

`CURVED_TEXT`
:   Rileva linee e riconosce il testo su immagini curve.
Modalità preferita per foto di pagine di libri e riviste.

`DOCUMENT`
:   Rileva paragrafi usando un modello NN per documenti.
Meglio per documenti multicolonna, documenti con immagini o con altri oggetti non testuali.

`NONE`
:   Non rileva paragrafi.
Meglio per un semplice documento a una colonna senza immagini.

`PHOTO`
:   Rileva paragrafi usando un modello NN per foto.
Meglio per immagini con molte foto e altri oggetti non testuali.

`TABLE`
:   Rileva celle con testo.
Modalità preferibile per immagini con struttura a tabella.

`TEXT_IN_WILD`
:   Una rete neurale superpotente specializzata nell'estrazione di parole da immagini a bassa qualità come foto di strada, targhe, foto di passaporto, foto di contatori e foto con sfondi rumorosi.

`Format(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Formato per salvare il risultato del riconoscimento come documento.

### Antenati (in MRO)

    * enum.Enum

### Variabili di classe

`DOCX`
:   Salva il risultato come documento Office Open XML Word processing ML (senza macro).

`EPUB`
:   Salva il documento come file EPUB.

`HTML`
:   Salva il documento come file HTML.

`JSON`
:   Salva il risultato come testo semplice scritto in notazione oggetto JavaScript.

`PDF`
:   Salva il risultato come PDF (Adobe Portable Document) Documento.

`PDF_NO_IMG`
:   Salva il documento come PDF Ricercabile (Adobe Portable Document) Documento senza immagine.

`RTF`
:   Salva il documento come file rtf.

`TEXT`
:   Salva il risultato nel formato di testo semplice.

`XLSX`
:   Salva il risultato come documento cartella di lavoro Excel (2007 e successive).

`XML`
:   Salva il risultato come Documento XML.

`ImageData(javaClass)`
:

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Metodi

`initParams(self)`
:

`InputType(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Tipi di immagini/documenti per l'elaborazione/riconoscimento.

### Antenati (in MRO)

    * enum.Enum

### Variabili di classe

`BASE64`
:   stringa base64 con l'immagine o percorso al file .txt con il contenuto base64. Supporta GIF, PNG, JPEG, BMP, TIFF.

`DIRECTORY`
:   Percorso della directory. Archivi e cartelle nidificate non sono supportati.
Supporta GIF, PNG, JPEG, BMP, TIFF.
Il numero predefinito di immagini elaborate è tutte.

`PDF`
:   Documento PDF scansionato da file o da array binario.

`SINGLE_IMAGE`
:   Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF, array binario.

`TIFF`
:   Documento TIFF multipagina, TIF da file o da InputStream.

`URL`
:   Link sull'immagine. Supporta GIF, PNG, JPEG, BMP, TIFF.

`ZIP`
:   Nome completo dell'archivio ZIP. Gli archivi e le cartelle nidificate non sono supportati.
Supporta GIF, PNG, JPEG, BMP, TIFF, JFIF.
Il numero predefinito di immagini elaborate è tutte.

`Language(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Modello linguistico per il riconoscimento.

### Antenati (in MRO)

    * enum.Enum

### Variabili di classe

`BEL`
:   Alfabeto bielorusso

`BUL`
:   Alfabeto bulgaro

`CHI`
:   Alfabeto cinese

`CYRILLIC`
:   Supporto multilingua (alfabeto cirillico)

`CZE`
:   Alfabeto ceco

`DAN`
:   Alfabeto danese

`DEU`
:   alfabeto tedesco

`DUM`
:   alfabeto olandese

`ENG`
:   alfabeto inglese

`EST`
:   alfabeto estone

`FIN`
:   alfabeto finlandese

`FRA`
:   alfabeto francese

`HIN`
:   alfabeto hindi

`ITA`
:   alfabeto italiano

`KAZ`
:   alfabeto kazako

`LATIN`
:   Supporto multilingua (alfabeto latino)

`LAV`
:   alfabeto lettone

`LIT`
:   alfabeto lituano

`NONE`
:   Supporto multilingua

`NOR`
:   alfabeto norvegese

`POL`
:   alfabeto polacco

`POR`
:   alfabeto portoghese

`RUM`
:   alfabeto rumeno

`RUS`
:   alfabeto russo

`SLK`
:   alfabeto slovacco

`SLV`
:   alfabeto sloveno

`SPA`
:   alfabeto spagnolo

`SRP`
:   alfabeto serbo

`SRP_HRV`
:   alfabeto serbo-croato

`SWE`
:   alfabeto svedese

`UKR`
:   alfabeto ucraino

`ModelsConverter()`
:

### Metodi

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
:   Classe principale per raccogliere le immagini.
    
Costruttore per creare il contenitore e impostare il tipo di immagini / documenti e i filtri per l'elaborazione / riconoscimento successivi.
@param type: Imposta il tipo di immagini/documenti che verrà aggiunto al contenitore.
@param filters: Imposta i filtri di elaborazione che saranno applicati per l'elaborazione o il riconoscimento successivi.

### Metodi

`add(self, fullPath: str, startPage: int = None, pagesNumber: int = None)`
:   Aggiungi il percorso o l'URI contenente l'immagine per il riconoscimento / l'elaborazione.
Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.
@param fullPath: Percorso dell'immagine/documento/cartella/archivio.
@param startPage: La prima pagina/immagine per l'elaborazione / riconoscimento. Da usare per documenti, zip, cartelle.
@param pagesNumber: Il numero totale di pagine/immagini per l'elaborazione / riconoscimento. Da usare per documenti, zip, cartelle. Predefinito = tutte.

`addStream(self, image_data_binary, startPage: int = None, pagesNumber: int = None)`
:   Aggiungi l'InputStream contenente l'immagine per il riconoscimento / l'elaborazione.
Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.
        
\code
input = OcrInput(InputType.SINGLE_IMAGE)
file = open(imgPath, "rb")
image_data_binary = file.read()
file.close()
input.addStream(image_data_binary)
result = api.recognize(input, RecognitionSettings())
\endcode
        
@param image_data_binary: contenente l'immagine o il documento.
@param startPage: La prima pagina/immagine per l'elaborazione / riconoscimento. Da usare per documenti, zip, cartelle.
@param pagesNumber: Il numero totale di pagine/immagini per l'elaborazione / riconoscimento. Da usare per documenti, zip, cartelle. Predefinito = tutte.

`add_base64(self, base64: str)`
:   Aggiungi la stringa base64 contenente l'immagine per il riconoscimento / elaborazione.
Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore.
@param base64: Stringa Base64 con immagine singola.

`clear(self)`
:   Imposta il numero di elementi per l'elaborazione / riconoscimento a 0.
Cancella la collezione.

`clear_filters(self)`
:   Rimuovi tutti i filtri.

`get(self, index: int) ‑> models.ImageData`
:   Restituisce informazioni sull'immagine elaborata / riconosciuta.
@param index: Posizione dell'immagine nella Lista.
@return: L'oggetto ImageData.

`getJavaClass(self)`
:

`init(self, javaClass)`
:

`size(self)`
:   Numero di elementi per l'elaborazione / riconoscimento.
@return: Numero di elementi.

`PreprocessingFilter()`
:   Classe base per i comandi di elaborazione delle immagini.

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Variabili di classe

`JAVA_CLASS_NAME`
:

### Metodi statici

`auto_denoising()`
:   Consente l'uso di una rete neurale aggiuntiva per migliorare l'immagine - ridurre il rumore.
Utile per immagini con artefatti di scansione, distorsioni, macchie, bagliori, gradienti, elementi estranei.
@return: Oggetto AutoDenoisingFilter.

`auto_dewarping()`
:   Corregge automaticamente le distorsioni geometriche nell'immagine.
Estremamente intensivo in risorse!
@return: Oggetto AutoDewarpingFilter.

`auto_skew()`
:   Abilita la correzione automatica dell'inclinazione dell'immagine.
@return: oggetto AutoSkewFilter.

`binarize()`
:   Converte un'immagine in immagine in bianco e nero.
Le immagini binarie sono immagini i cui pixel hanno solo due possibili valori di intensità.
Sono normalmente visualizzate in bianco e nero. Numericamente, i due valori sono spesso 0 per il nero e 255 per il bianco.
Le immagini binarie sono prodotte mediante sogliatura automatica di un'immagine.
@return: oggetto BinarizeFilter.

`binarize_and_dilate()`
:   La dilatazione aggiunge pixel ai bordi degli oggetti in un'immagine.
@return: oggetto DilateFilter.

`contrast_correction()`
:   Filtro di correzione del contrasto.
@return: oggetto ContrastCorrectionFilter.

`invert()`
:   Inverte automaticamente i colori in un'immagine di documento.
@return: oggetto InvertFilter.

`median()`
:   Il filtro mediano attraversa ogni elemento dell'immagine e sostituisce ogni pixel con la mediana dei pixel vicini.
@return: oggetto MedianFilter.

`resize(width: int, height: int)`
:   Ridimensiona l'immagine - aumenta o diminuisce la risoluzione dell'immagine.
@param width: La nuova larghezza dell'immagine.
@param height: La nuova altezza dell'immagine.
@return: oggetto ResizeFilter.

`rotate(angle: float)`
:   Ruota l'immagine originale.
@param angle: Angolo di rotazione. Valore da -360 a 360.
@return: oggetto RotateFilter.

`scale(ratio: float)`
:   Ridimensiona l'immagine - Aumenta o diminuisce la risoluzione dell'immagine.
InterpolationFilterType bilineare o nearest neighbor.
@param ratio: Il fattore di scala. Valore consigliato da 0,1 a 1 per ridurre. Da 1 a 10 per ingrandire.
@return: oggetto ScaleFilter.

`threshold(value: int)`
:   Crea un'immagine binaria impostando un valore di soglia sull'intensità dei pixel dell'immagine originale.
@param value: Il valore massimo.
@return: oggetto BinarizeFilter.

`to_grayscale()`
:   Converte un'immagine in immagine in scala di grigi.
L'immagine in scala di grigi ha 256 livelli di luminosità (da 0 a 255).
@return: oggetto GrayscaleFilter.

### Metodi

`add(self, filter)`
:   Aggiunge il filtro alla collezione per ulteriori pre‑elaborazioni.
@param filter: oggetto PreprocessingFilter.

`getJavaClass(self)`
:

`SpellCheckError(javaClass)`
:   Rappresenta una parola errata con dati aggiuntivi.

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Metodi

`initParams(self)`
:

`SpellCheckLanguage(value, names=None, *, module=None, qualname=None, type=None, start=1)`
:   Lingua del dizionario per la correzione ortografica.

### Antenati (in MRO)

    * enum.Enum

### Variabili di classe

`CZE`
:   Dizionario ceco

`DAN`
:   Dizionario danese

`DEU`
:   Dizionario tedesco

`DUM`
:   Dizionario olandese

`ENG`
:   Dizionario inglese

`EST`
:   Dizionario estone

`FIN`
:   Dizionario finlandese

`FRA`
:   Dizionario francese

`ITA`
:   Dizionario italiano

`LAV`
:   Dizionario lettone

`LIT`
:   Dizionario lituano

`POL`
:   Dizionario polacco

`POR`
:   Dizionario portoghese

`RUM`
:   Dizionario rumeno

`SLK`
:   Dizionario slovacco

`SLV`
:   Dizionario sloveno

`SPA`
:   Dizionario spagnolo

`SWE`
:   Dizionario svedese

`SuggestedWord(javaClass)`
:   Suggerimento ortografico restituito da get_spell_check_error_list.

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Metodi

`initParams(self)`
:


### Vedi anche

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)