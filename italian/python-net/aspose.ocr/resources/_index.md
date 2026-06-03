---
title: "Resources"
second_title: "Riferimento API di Aspose.OCR per Python via .NET"
description: 
type: docs
weight: 360
url: /it/python-net/aspose.ocr/resources/
---

## Resources class

Gestisci le risorse scaricabili che migliorano le capacità di riconoscimento di Aspose.OCR.

Il tipo Resources espone i seguenti membri:
## Costruttori
| Nome | Descrizione |
| :- | :- |
| Resources() | Inizializza una nuova istanza della classe Resources |
## Methods
| Nome | Descrizione |
| :- | :- |
| set_local_path(path) | Specifica un percorso assoluto o relativo alla directory in cui le risorse saranno scaricate.<br/>            Se la directory non esiste, verrà creata automaticamente.<br/>            Per impostazione predefinita, le risorse vengono scaricate nella directory aspose_data nella directory di lavoro dell'applicazione. |
| set_local_path(path, create) | Specifica un percorso assoluto o relativo alla directory in cui le risorse saranno scaricate.<br/>            Passa `false` al parametro `create` per impedire che la directory venga creata automaticamente.<br/>            Se la directory fornita non esiste e la creazione non è consentita, le risorse verranno caricate nella directory aspose_data nella directory di lavoro dell'applicazione. |
| set_repository(url) | Specificare l'URL del repository online da cui verranno scaricati i resource di Aspose.OCR.<br/>            Per impostazione predefinita, le risorse vengono scaricate da https://github.com/aspose-ocr/resources/. |
| get_repository() | Restituisce l'URL del repository online da cui vengono scaricate le risorse di Aspose.OCR. |
| list_remote() | Elenca tutte le risorse compatibili dal repository online. |
| get_local_path() | Restituisce il percorso completo della directory in cui verranno scaricate le risorse. |
| list_local() | Elenca tutte le risorse di Aspose.OCR memorizzate nella directory locale. |
| allow_automatic_downloads(allow) | Consente (true) o blocca (false) il download automatico delle risorse richieste dal repository online.<br/>             Per impostazione predefinita, una risorsa viene scaricata automaticamente quando viene chiamato un metodo che dipende da essa. |
| fetch_resources(names) | Scarica le risorse specificate nel parametro `names` dal repository online. Se una o più risorse sono già state scaricate, verranno sovrascritte.<br/>            È possibile omettere l'estensione .OCR e utilizzare solo i nomi dei file. |
| fetch_resource(name) | Scarica le risorse specificate nel parametro `names` dal repository online. Se una o più risorse sono già state scaricate, verranno sovrascritte.<br/>            È possibile omettere l'estensione .OCR e utilizzare solo i nomi dei file. |
| fetch_all() | Scarica tutte le risorse compatibili dal repository online. I file delle risorse esistenti verranno sovrascritti. |
| remove_local(name) | Rimuove la risorsa di Aspose.OCR memorizzata localmente. |
| release_memory() |  |

### Vedi anche

* namespace [aspose.ocr](/ocr/python-net/aspose.ocr/)
* assembly [Aspose.ocr](/ocr/python-net/)

