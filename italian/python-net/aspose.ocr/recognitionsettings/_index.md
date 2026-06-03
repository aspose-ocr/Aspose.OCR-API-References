---
title: "RecognitionSettings"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 330
url: /it/python-net/aspose.ocr/recognitionsettings/
---

## RecognitionSettings class

Impostazioni per il riconoscimento delle immagini.<br/>            Contiene elementi che consentono di personalizzare il processo di riconoscimento.

Il tipo RecognitionSettings espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| RecognitionSettings() | Inizializza una nuova istanza di |
| RecognitionSettings(language, recognition_areas, recognize_single_line) | Inizializza una nuova istanza della classe RecognitionSettings |
## Proprietà
| Nome | Descrizione |
| :- | :- |
| recognize_vertical_lines |  |
| threads_count | Ottiene o imposta il numero di thread per l'elaborazione. |
| language | Ottiene o imposta la lingua utilizzata per l'OCR. |
| ignored_symbols | Imposta la lista nera per i simboli di riconoscimento. |
| allowed_symbols | Imposta i caratteri consentiti con la proprietà alphabet. |
| allowed_characters | Insieme di caratteri consentiti. Determina il tipo di caratteri ammessi per il risultato del riconoscimento. |
| automatic_color_inversion | Rileva immagini con testo bianco su sfondo scuro/nero e sceglie automaticamente un algoritmo OCR speciale per esse. |
| recognition_areas | Ottiene o imposta l'elenco delle aree di testo per l'elaborazione. |
| recognize_single_line | Imposta il riconoscimento di immagini a riga singola. <br/>            Disabilitato (false) per impostazione predefinita. <br/>            Disabilita tutti i passaggi di elaborazione associati alla suddivisione in righe. <br/>            Imposta questo parametro su true se la tua immagine contiene una sola riga. Disabilita le impostazioni di RecognitionAreas, quindi tutte le impostazioni delle aree verranno ignorate. |
| language_detection_level |  |
| lines_filtration | Consente di riconoscere il testo nelle tabelle (regioni circondate da linee). |
| detect_areas_mode | Consente di selezionare la modalità ottimale per le aree di tipo documento: documento, foto, testo semplice, colonna, immagine. |
| upscale_small_font | Consente di utilizzare algoritmi aggiuntivi specifici per il riconoscimento di caratteri di piccola dimensione.<br/>            Utile per immagini con caratteri di piccole dimensioni. |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

