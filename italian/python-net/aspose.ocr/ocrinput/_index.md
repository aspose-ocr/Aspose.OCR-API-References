---
title: "OcrInput"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 240
url: /it/python-net/aspose.ocr/ocrinput/
---

## OcrInput class

Contenitore per raccogliere tutte le immagini / documenti per il pre‑elaborazione / riconoscimento.

Il tipo OcrInput espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| OcrInput(type, filters) | Inizializza una nuova istanza della classe OcrInput |
| OcrInput(type) | Inizializza una nuova istanza della classe OcrInput |
## Indexer
| Nome | Descrizione |
| :- | :- |
| [index] | Restituisce informazioni sull'immagine elaborata / riconosciuta. |
## Methods
| Nome | Descrizione |
| :- | :- |
| add(full_path) | Aggiunge il percorso o l'URI contenente l'immagine per il riconoscimento / l'elaborazione.<br/>            Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore. |
| add(stream) | Aggiunge lo stream di memoria contenente l'immagine per il riconoscimento / l'elaborazione.<br/>            Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore. |
| add(full_path, start_page, pages_count) | Aggiunge le immagini / documenti multipagina per il riconoscimento / l'elaborazione.<br/>            Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore. |
| add(stream, start_page, pages_count) | Aggiunge lo stream di memoria contenente l'immagine multipagina per il riconoscimento / l'elaborazione.<br/>            Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore. |
| add(arr, width, height, pixel_format) | Aggiungi l'immagine decodificata all'elenco per il riconoscimento / l'elaborazione.<br/>            Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore (SingleImage). |
| replace_filters(filters) | Rimuovi i filtri vecchi e imposta quelli nuovi. |
| clear_filters() | Rimuovi tutti i filtri. |
| add_base64(base64) | Aggiungi la stringa base64 contenente l'immagine per il riconoscimento / l'elaborazione.<br/>            Il tipo dell'immagine deve corrispondere al tipo specificato nel costruttore. |
| clear() | Rimuovi tutti i filtri. |
| count() | Numero di elementi per l'elaborazione / il riconoscimento. |
| get_input_type() | Tipo di immagini consentite per il riconoscimento. |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

