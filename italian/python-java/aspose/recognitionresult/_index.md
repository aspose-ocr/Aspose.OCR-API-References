---
title: "RecognitionResult"
second_title: "Riferimento API di Aspose.OCR per Python via Java"
description: 
type: docs
weight: 171
url: /it/python-java/aspose/recognitionresult/
---

Modulo recognitionresult
========================

Classi
-------

`LinesResult(javaClass)`
:

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Metodi

`initParams(self)`
:

`RecognitionResult(javaClass)`
:
I risultati del riconoscimento delle immagini. Contiene elementi con riconoscimento
informazioni e metodi per l'esportazione dei risultati.

### Metodi statici

`save_multipage_document(self, fullPath: str)`
:
Privato

### Variabili di istanza

`recognition_areas_text`
:   Elenco dei risultati di riconoscimento di una lista di aree (Rettangoli).

`recognition_lines_result`
:   Ottiene un elenco di risultati di riconoscimento con un elenco di righe (Rettangoli).

### Metodi

`getJavaClass(self)`
:

`get_json(self)`
:
Crea stringa JSON con i risultati di riconoscimento.
@return: Risultati di riconoscimento come stringa JSON.

`get_spell_check_corrected_text(self, language: aspose.models.SpellCheckLanguage) ‑> str`
:
Corregge il testo (sostituisce le parole errate).
@param language: Dizionario da utilizzare.
@return: Stringa dei risultati di riconoscimento corretti.

`get_spell_check_error_list(self, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Trova le parole errate con le ortografie suggerite per un testo di input fornito.
@param language: Dizionario da utilizzare.
@return: Elenco di oggetti SpellCheckError che rappresentano le parole errate con elenchi di ortografie corrette suggerite per ciascuna parola errata,
e con la distanza di modifica.

`get_xml(self)`
:
Crea stringa JSON con i risultati di riconoscimento.
@return: Risultati di riconoscimento come stringa XML.

`init(self)`
:

`save(self, fullFileName: str, format: aspose.models.Format)`
:
Salva il documento in testo semplice o in altri formati di documento.
@param fullFileName: Nome file con percorso per salvare il risultato del riconoscimento.
@param format: Tipo enum del formato documento di Format.

`save_spell_check_corrected_text(self, fullFileName: str, format: aspose.models.Format, language: aspose.models.SpellCheckLanguage = SpellCheckLanguage.ENG)`
:
Corregge il testo (sostituisce le parole errate).
Salva il testo corretto nel documento in testo semplice o in altri formati.
@param fullFileName: Nome file con percorso per salvare il risultato del riconoscimento
@param format: Tipo enum del formato documento di Format.
@param language: Dizionario per il controllo ortografico.

`use_user_dictionary(self, dictionaryPath: str)`
:
Consente di utilizzare un dizionario personale per la correzione ortografica.
@param dictionaryPath: Percorso completo al dizionario utente (dizionario di frequenza).
Formato del file dizionario:
File di testo semplice con codifica UTF-8.
Parola e frequenza della parola sono separate da una virgola, la parola è prevista nella prima colonna e la frequenza nella seconda colonna.
Ogni coppia parola‑frequenza in una linea separata. Una linea è definita come una sequenza di caratteri seguita da un ritorno a capo ("
"), un ritorno a capo ("
"),
o un ritorno a capo immediatamente seguito da un avanzamento di riga("

").
Ogni parola deve essere in minuscolo.
Esempio:
\code
word,5984819
ciao,5761742
giù,5582768
\endcode

`RectangleOutput(javaClass)`
:
Dati sulle aree di testo o linee rilevate.
\code
source - Il percorso completo del file o URL, se presente. Vuoto per stream, array di byte, base64.
page - Numero di pagina.
image_index - Numero di sequenza dell'immagine nella pagina.
rectangles - Elenco delle aree di testo o linee rilevate.
\endcode

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Metodi

`initParams(self)`
:

`SkewOutput(javaClass)`
:
Dati sull'angolo di inclinazione in gradi e sul nome del file.
\code
source - Il percorso completo del file o URL, se presente. Vuoto per stream, array di byte, base64.
page - Numero di pagina.
image_index - Numero di sequenza dell'immagine nella pagina.
angle - Angolo di inclinazione in gradi.
\endcode

### Antenati (in MRO)

    * aspose.helper.BaseJavaClass

### Metodi

`initParams(self)`
:


### Vedi anche

* namespace [aspose](/ocr/python-java/aspose/)
* assembly [Aspose](/ocr/python-java/)