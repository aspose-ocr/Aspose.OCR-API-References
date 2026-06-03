---
title: "DetectAreasMode"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 540
url: /it/python-net/aspose.ocr/detectareasmode/
---

## DetectAreasMode enumeration

Determina il tipo di rete neurale utilizzata per il rilevamento delle aree.

## Members
| Nome membro | Descrizione |
| :- | :- |
| LEAN | Prioritizza la velocità e riduce il consumo di risorse omettendo il supporto per layout complessi. Adatto solo a immagini semplici con poche righe di testo, senza illustrazioni o formattazione. |
| MULTICOLUMN | Rileva grandi blocchi di testo formattati in colonne. La scelta migliore per layout a più colonne come pagine di libri, articoli o contratti. |
| UNIVERSAL | Rileva tutti i blocchi di testo nell'immagine, inclusi testo sparso e irregolare nelle foto. Un'opzione versatile per la maggior parte delle immagini, eccetto tabelle e layout a più colonne. |
| TABLE | Rileva strutture tabulari nell'immagine ed estrae il testo dalle singole celle. Consigliato per fogli di calcolo scansionati, report e altri documenti basati su tabelle. |
| CURVED_TEXT | Raddrizza automaticamente le linee di testo curve nell'immagine, migliorando l'accuratezza del riconoscimento e consentendo di recuperare ed estrarre più testo. Richiede una notevole potenza di elaborazione e RAM. |
| FORMULA |  |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.OCR](/ocr/python-net/)

