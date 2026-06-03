---
title: "Metered"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 190
url: /it/python-net/aspose.ocr/metered/
---

## Metered class

Fornisce metodi per impostare la chiave a consumo.

Il tipo Metered espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Metered() | Inizializza una nuova istanza di questa classe. |
## Methods
| Nome | Descrizione |
| :- | :- |
| set_metered_key(public_key, private_key) | Imposta la chiave pubblica e privata a consumo.<br/>            Se acquisti una licenza a consumo, all'avvio dell'applicazione questa API dovrebbe essere chiamata; normalmente è sufficiente. <br/>            Tuttavia, se fallisce continuamente il caricamento dei dati di consumo e supera le 24 ore, la licenza verrà impostata in stato di valutazione, <br/>            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API. |
| get_consumption_quantity() | Ottiene la dimensione del file di consumo. |
| get_consumption_credit() | Ottiene il credito di consumo. |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

