---
title: "AsposeOcr"
second_title: "Riferimento API di Aspose.OCR per Python via Java"
description: 
type: docs
weight: 11
url: /it/python-java/aspose/asposeocr/
---


Modulo asposeocr
================
Interfaccia Python per Aspose OCR

**Aspose.OCR for Python via .Java** is a powerful,
mentre il riconoscimento ottico dei caratteri (OCR) è facile da usare
motore per le tue applicazioni Python e notebook.
In meno di **10** righe di codice, puoi riconoscere
testo in **28** lingue basate su latino, cirillico,
e script asiatici, restituendo risultati nei formati più popolari
di documenti e formati di scambio dati.
Non è necessario apprendere modelli matematici complessi,
costruire algoritmi di machine learning e addestrare reti neurali
— la nostra API semplice e robusta farà tutto per te.

Classi
-------

`AsposeOcr()`
:
Classe principale AsposeOcr per il riconoscimento.
    
Questo esempio mostra come riconoscere un'immagine.
\code
api = AsposeOcr()
input = OcrInput(InputType.SINGLE_IMAGE)
input.add(os.path.join(self.dataDir, "SpanishOCR.bmp"))
result = api.recognize(input)
\endcode

### Metodi statici

`save_multipage_document(fullFileName: str, saveFormat: aspose.models.Format, results: List)`
:
Consente di ottenere un documento multipagina da un elenco di oggetti RecognitionResult.
@param fullFileName: Nome file con percorso per salvare il risultato del riconoscimento nel formato selezionato.
@param saveFormat: Formato del documento (Docx, Txt, Pdf, Xlsx, Xml, Json).
@param results:

### Metodi

`calculate_skew(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.SkewOutput]`
:
Calcola gli angoli di inclinazione di un'immagine.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza. Il contenitore con le sorgenti.
@return: Lista di angoli di inclinazione in gradi - SkewOutput.

`compare_image_texts(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Verifica se due immagini contengono lo stesso testo.
@param fullPath1: Percorso della prima immagine.
@param fullPath2: Percorso della seconda immagine.
@param settings: Impostazioni di riconoscimento.
@param ignoreCase: True - indica una ricerca senza distinzione tra maiuscole e minuscole.
@return: True se le immagini hanno lo stesso testo (similitudine del 90%).

`correct_spelling(self, text: str, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corregge il testo (sostituisce le parole errate).
@param text: Testo da correggere.
@param language: Dizionario da utilizzare SpellCheckLanguage.
@return: Testo con le parole sostituite.

`detect_rectangles(self, input: aspose.models.OcrInput, areasType: aspose.models.AreasType, isDetectAreas: bool) ‑> List[aspose.recognitionresult.RectangleOutput]`
:
Rileva le aree di testo nelle immagini.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param areasType: Determina quali rettangoli restituire - linea, paragrafi o parole.
@param isDetectAreas: Abilita il rilevamento automatico delle aree di testo.
@return: Lista di RectangleOutput con le aree di testo o le linee rilevate.

`image_has_text(self, fullPath: str, text: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> bool`
:
Verifica se l'immagine contiene il frammento di testo fornito.
@param fullPath: Percorso dell'immagine.
@param text: Frammento di testo da cercare nell'immagine.
@param settings: Impostazioni di riconoscimento.
@param ignoreCase: True - indica una ricerca senza distinzione tra maiuscole e minuscole.
@return: True se l'immagine contiene il frammento di testo. False - l'immagine non contiene il frammento di testo.

`image_text_diff(self, fullPath1: str, fullPath2: str, settings: aspose.recognitionsettings.RecognitionSettings = None, ignoreCase: bool = True) ‑> float`
:
Confronta i testi delle due immagini e restituisce un numero che rappresenta quanto sono simili (da 0 a 1).
@param fullPath1: Percorso della prima immagine.
@param fullPath2: Percorso della seconda immagine.
@param settings: Impostazioni di riconoscimento.
@param ignoreCase: True - indica una ricerca senza distinzione tra maiuscole e minuscole.
@return: 0 indica che i testi sono completamente diversi; 1 indica che i testi sono identici.

`recognize(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce l'immagine con la possibilità di specificare RecognitionSettings.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: oggetto RecognitionSettings.
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_car_plate(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.CarPlateRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce la targa con la possibilità di specificare CarPlateRecognitionSettings.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: CarPlateRecognitionSettings
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_fast(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce il testo su un'immagine di buona qualità. Non utilizza la correzione automatica dell'inclinazione dell'immagine e le aree di testo
rilevamento.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_id_card(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.IDCardRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce la carta d'identità con la possibilità di specificare IDCardRecognitionSettings.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: IDCardRecognitionSettings
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_invoice(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.InvoiceRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce la fattura con la possibilità di specificare InvoiceRecognitionSettings
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: InvoiceRecognitionSettings
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_lines(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.RecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce un'immagine a riga singola con la possibilità di specificare RecognitionSettings.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: oggetto RecognitionSettings.
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_passport(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.PassportRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce i passaporti con la possibilità di specificare PassportRecognitionSettings.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: PassportRecognitionSettings
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_receipt(self, input: aspose.models.OcrInput, settings: aspose.recognitionsettings.ReceiptRecognitionSettings = None) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosci le ricevute con la possibilità di specificare ReceiptRecognitionSettings.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@param settings: ReceiptRecognitionSettings
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`recognize_street_photo(self, input: aspose.models.OcrInput) ‑> List[aspose.recognitionresult.RecognitionResult]`
:
Riconosce il testo nelle foto di strada.
Estrai il testo da foto di strada, immagini di telecamere del traffico, carte d'identità, patenti di guida e altre immagini con testo sparso e sfondi rumorosi/colorati.
Supporta GIF, PNG, JPEG, WBMP, TIFF, JFIF, TIFF, PDF, array binario, cartella, array, archivio zip, URL, base64.
@param input: :py:any:`~aspose.models.OcrInput`. istanza.
@return: elenco di RecognitionResult con i risultati del riconoscimento delle immagini.

`shutdown(self)`
:
Arresta la macchina JVM.

`ImageProcessing()`
:
Classe di supporto per la libreria Aspose OCR. Consente di pre-elaborare e salvare le immagini.

### Metodi statici

`save(images, folderPath)`
:
Utilizza l'elaborazione delle immagini per migliorare l'accuratezza dell'OCR.
Crea un elenco di filtri che verranno applicati all'immagine di input nell'ordine specificato.
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
Non hai bisogno di tutti. Imposta solo ciò di cui hai bisogno.
@param images: oggetto OcrInput contenente diverse immagini OcrInput.
@param folderPath: Percorso senza i nomi delle immagini per salvare le immagini elaborate.
@return: oggetto OcrInput contenente le immagini elaborate risultanti OcrInput.


### Vedi anche

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)