---
title: "RecognitionResult"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 290
url: /it/python-net/aspose.ocr/recognitionresult/
---

## RecognitionResult class

I risultati del riconoscimento dell'immagine.<br/>            Contiene elementi con informazioni sul riconoscimento e metodi per l'esportazione dei risultati.

Il tipo RecognitionResult espone i seguenti membri:


## Proprietà
| Nome | Descrizione |
| :- | :- |
| recognition_regions_result | Restituisce un elenco di risultati di riconoscimento con un elenco di regioni (Rettangoli). |
| recognition_lines_result | Restituisce un elenco di risultati di riconoscimento con un elenco di righe (Rettangoli). |
| recognition_characters_list | Un insieme di caratteri trovati dall'algoritmo di riconoscimento e ordinati in ordine decrescente di probabilità. |
| recognition_text | Restituisce il risultato del riconoscimento in una stringa. |
| file_name | Percorso completo del file. |
| warnings | Restituisce un elenco dei messaggi di avviso che descrivono i difetti non critici comparsi durante la generazione. |
| serializable_image |  |
## Methods
| Nome | Descrizione |
| :- | :- |
| save(full_file_name, save_format, apply_spelling_correction, language, dictionary_path, embedded_font_path, optimize_pdf) | Salva il documento come testo semplice, PDF o documento Microsoft Word. |
| save(full_file_name, save_format, embedded_font_path, optimize_pdf) | Salva il documento come testo semplice, PDF o documento Microsoft Word. |
| save(full_file_name, save_format, optimize_pdf) | Salva il documento come testo semplice, PDF o documento Microsoft Word. |
| save(stream, save_format, optimize_pdf) | Salva il documento come testo semplice, PDF o documento Microsoft Word. |
| save(stream, save_format, apply_spelling_correction, language, dictionary_path) | Salva il documento come testo semplice, PDF o documento Microsoft Word. |
| get_spell_check_corrected_text(language, dictionary_path) | Corregge il testo (sostituisce le parole errate). |
| get_spell_check_error_list(language, dictionary_path) | Trova le parole errate con le ortografie suggerite per un testo di input fornito. |
| get_json(is_readable) | Crea una stringa JSON con i risultati di riconoscimento. |
| get_xml() | Crea una stringa XML con i risultati di riconoscimento. |
| get_keywords() | Ottieni parole chiave dal passaporto (Modalità test. Funziona solo per passaporti USA e MADAGASCAR). |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

